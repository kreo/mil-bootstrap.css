# mil-boostrap.css

Lit-Element Bootstrap stylesheet.

## Installation

```bash
npm i mil-bootstrap.css --save
```

## Usage

2 versions of bootstrap.css are available.
Files comparison details are available here:
https://getbootstrap.com/docs/4.4/getting-started/contents/#css-files

```html
import { bootstrap } from 'path/to/mil-bootstrap.css/bootstrap.js';
import { bootstrapGrid } from 'path/to/mil-bootstrap.css/bootstrap-grid.js';

```
```html

  static get styles() {
    return [
      bootstrap,
      bootstrapGrid
    ];
  
```
