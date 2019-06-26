# useWithViewbox React Hook

[![Build Status](https://travis-ci.org/the-road-to-learn-react/use-with-viewbox.svg?branch=master)](https://travis-ci.org/the-road-to-learn-react/use-with-viewbox) [![Slack](https://slack-the-road-to-learn-react.wieruch.com/badge.svg)](https://slack-the-road-to-learn-react.wieruch.com/) [![Greenkeeper badge](https://badges.greenkeeper.io/the-road-to-learn-react/use-with-viewbox.svg)](https://greenkeeper.io/) ![NPM](https://img.shields.io/npm/l/use-with-viewbox.svg)

Custom hook to add a viewbox attribute to your SVG in case it's missing. It calculates the viewbox based on the rendered svg element with its height and width. [Read more about it here.](https://www.robinwieruch.de/react-svg-icon-components/)

## Installation

`npm install use-with-viewbox`

## Usage

```
import useWithViewbox from 'use-with-viewbox';

const MySvg = (props) => {
  const ref = React.createRef();

  useViewbox(ref);

  return (
    <svg ref={ref} {...props}>
      // SVG Content ...
    </svg>
  );
};

export default MySvg;
```

## Contribute

- `git clone git@github.com:the-road-to-learn-react/use-with-viewbox.git`
- `cd use-with-viewbox`
- `npm install`

### More

- [Publishing a Node Package to NPM](https://www.robinwieruch.de/publish-npm-package-node/)
- [Node.js Testing Setup](https://www.robinwieruch.de/node-js-testing-mocha-chai/)
- [React Testing Setup](https://www.robinwieruch.de/react-testing-tutorial/)
