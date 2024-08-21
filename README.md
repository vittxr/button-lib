# Summary 

Learning how to create a component lib

npm-link: https://www.npmjs.com/package/@vittxr/button-lib

# Usage

1. Run `yarn add @vittxr/button-lib` or `npm i @vittxr/button-lib`
2. Sample code:
```tsx
import './App.css'
import { Button } from '@vittxr/button-lib'

function App() {
  return (
    <>
      <Button variant='filled'>
        testing @vittxr/button-lib button
      </Button>
    </>
  )
}

export default App

```

# Publish 

`npm publish --access public`

# References: 

- [Youtube - Build Your Own Component Library Using React, Tailwind, Storybook and TypeScript](https://www.youtube.com/watch?v=Fh-xdSf9uH0)
- [Github - tailwind-typescript-component-library](https://github.com/unhingedmagikarp/tailwind-typescript-component-library)
- [TSDX - docs](https://tsdx.io)
- [Stackoverflow - How to install an npm package from GitHub directly](https://stackoverflow.com/a/17509764/18432809)
- [Stackovewflow - Error running storybook - sh: 1: start-storybook: not found](https://stackoverflow.com/a/76613854/18432809)
- [Storybook 8](https://storybook.js.org/blog/storybook-8/)
- [Vite - Install vite](https://vitejs.dev/guide/#manual-installation)