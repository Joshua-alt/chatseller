# chatseller

> chat seller help you to improve custom  experence

[![NPM](https://img.shields.io/npm/v/chatseller.svg)](https://www.npmjs.com/package/chatseller) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save chatseller
```

## Usage

```jsx
import React, { Component } from 'react'
import {Chatseller} from 'chatseller'
import 'chatseller/dist/index.css';


const App = () => {
   let key = "x5u76ussvqdc" // replace with you key
  return(
    <div>
        ....
       <Chatseller secretkey={key} />  
    </div>
    )
}

export default App
```

## License

MIT © [Joshua-alt](https://github.com/Joshua-alt)
