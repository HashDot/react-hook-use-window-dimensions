# React Hook - useWindowDimensions

[![NPM](https://badgen.net/npm/v/react-hook-use-window-dimensions)](https://www.npmjs.com/package/react-hook-use-window-dimensions)

Get Browser Window Dimensions

## Install

```
npm i react-hook-use-window-dimensions
```

## Usage

Simply use the hook and get the dimensions.

**Demo:**

[![Edit Demo](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/react-hook-use-window-dimensions-dqf07)

**Example.js**

```javascript
import React from "react"
import useWindowDimensions from "react-hook-use-window-dimensions"

export default function ExampleComponent({ children }) {
  const { width, height } = useWindowDimensions()
  return (
    <>
      <p>width: {width}</p>
      <p>height: {height}</p>
    </>
  )
}
```
