# RGBSplitFilter

PixiJS filter to split and shift red, green or blue channels.

## Installation

```bash
npm install @pixi/filter-rgb-split
```

## Usage

```js
import {RGBSplitFilter} from '@pixi/filter-rgb-split';
import {Container} from 'pixi.js';

const container = new Container();
container.filters = [new RGBSplitFilter()];
```

## Documentation

See https://filters.pixijs.download/main/docs/PIXI.filters.RGBSplitFilter.html