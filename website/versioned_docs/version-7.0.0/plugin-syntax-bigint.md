---
id: version-7.0.0-babel-plugin-syntax-bigint
title: @babel/plugin-syntax-bigint
sidebar_label: syntax-bigint
original_id: babel-plugin-syntax-bigint
---


## Installation

```sh
npm install --save-dev @babel/plugin-syntax-bigint
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["@babel/plugin-syntax-bigint"]
}
```

### Via CLI

```sh
babel --plugins @babel/plugin-syntax-bigint script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["@babel/plugin-syntax-bigint"]
});
```

