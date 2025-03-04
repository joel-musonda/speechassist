# Speech Assist

[![npm version][npm-badge]][npm-url]
[![npm downloads][downloads-badge]][npm-url]
[![npm bundle size][size-badge]][size-url]
[![Open issues][issues-badge]][issues-url]
[![TypeScript][typescript-badge]][typescript-url]
[![semantic-release][semantic-badge]][semantic-url]

[![CI][lint-badge]][lint-url]
[![CI][tsc-badge]][tsc-url]
[![CI][build-badge]][build-url]
[![CI][test-badge]][test-url]
[![CI][test-e2e-badge]][test-e2e-url]
[![Codecov Coverage][coverage-badge]][coverage-url]

[![CI][deploy-storybook-badge]][deploy-storybook-url]
[![CI][npm-release-badge]][npm-release-url]

_👀 Giving Voice to everyone!!!

[![](misc/demo.gif)](https://mkosir.github.io/react-parallax-tilt/?path=/story/react-parallax-tilt--glare-effect)


## Install

```bash
npm install
npm run dev
```

## Features

- Lightweight 3kB, zero dependencies 📦
- AI voices integration🌳
- Works with React v15 onwards
- Supports **mouse** and **touch** events
- Support for device tilting (**gyroscope**)
- **Glare** effect 🌟 with custom props (color, position, etc.) 
- **Event tracking** for component values 📐 (tilt, glare, mousemove, etc.) [🔗demo](https://mkosir.github.io/react-parallax-tilt/?path=/story/react-parallax-tilt--event-params)


## Code

```jsx
import react from 'react';

const App = () => {
  return (
    <Tilt>
      <div style={{ height: '300px', backgroundColor: 'darkgreen' }}>
        <h1>Speech assist👀</h1>
      </div>
    </Tilt>
  );
};
```

## screenshots

![Screenshot 2025-03-04 7 01 32 AM](https://github.com/user-attachments/assets/8cdf2876-65f9-4656-8d5e-fc2b8622dc32)

![Screenshot 2025-03-04 7 02 14 AM](https://github.com/user-attachments/assets/aaf5189c-5bcf-46e0-a0ab-68174b849b5d)



![Uploading Screenshot 2025-03-04 7.02.51 AM.png…]()



Note: User interaction (like tapping a button) is required to output a sound- it cannot be triggered automatically on page load.

</details>

## Development

_Easily set up a local development environment!_

Build project and start storybook on [localhost](http://localhost:9009):

- clone
- `npm install`
- `npm start`

**Happy Hacking!** 🎉

<details>
<summary>Alternative setup using npm link</summary>

1. Clone this repository and navigate to its location
2. Run the following commands:

   ```bash
   npm install
   npm link # link your local repo to your global packages
   npm run build:watch # build the files and watch for changes
   ```

3. Clone the project you want to test with react-parallax-tilt and run:

   ```bash
   npm install
   npm link react-parallax-tilt # link your local copy into this project's node_modules
   npm start
   ```

</details>

## Contributing

All contributions are welcome!  


[npm-url]: https://www.npmjs.com/package/react-parallax-tilt
[npm-badge]: https://img.shields.io/npm/v/react-parallax-tilt.svg
[size-url]: https://bundlephobia.com/package/react-parallax-tilt
[size-badge]: https://badgen.net/bundlephobia/minzip/react-parallax-tilt
[downloads-badge]: https://img.shields.io/npm/dm/react-parallax-tilt.svg?color=blue
[lint-badge]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/lint.yml/badge.svg
[lint-url]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/lint.yml
[tsc-badge]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/tsc.yml/badge.svg
[tsc-url]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/tsc.yml
[build-badge]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/build.yml/badge.svg
[build-url]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/build.yml
[test-badge]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/test.yml/badge.svg
[test-url]: https://react-parallax-tilt-test-unit-report.netlify.app/
[test-e2e-badge]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/test-e2e.yml/badge.svg
[test-e2e-url]: https://react-parallax-tilt-test-e2e-report.netlify.app/
[deploy-storybook-badge]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/deploy-storybook.yml/badge.svg
[deploy-storybook-url]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/deploy-storybook.yml
[npm-release-badge]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/npm-release.yml/badge.svg
[npm-release-url]: https://github.com/mkosir/react-parallax-tilt/actions/workflows/npm-release.yml
[coverage-badge]: https://codecov.io/gh/mkosir/react-parallax-tilt/branch/main/graph/badge.svg
[coverage-url]: https://app.codecov.io/github/mkosir/react-parallax-tilt/tree/main
[issues-badge]: https://img.shields.io/github/issues/mkosir/react-parallax-tilt
[issues-url]: https://github.com/mkosir/react-parallax-tilt/issues
[semantic-badge]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[semantic-url]: https://github.com/semantic-release/semantic-release
[typescript-badge]: https://badges.frapsoft.com/typescript/code/typescript.svg?v=101
[typescript-url]: https://github.com/microsoft/TypeScript
