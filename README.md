<p align="center">
  <img alt="Mezrmouse" src="https://image.ibb.co/fhYWuU/1286733997-982bf490-c49b-41dc-80e9-b7b4fc7a22db.png">
</p>

> measure distance between your mouse and object to make an interactive user interface

[![NPM](https://img.shields.io/npm/v/Mezrmouse.svg)](https://www.npmjs.com/package/Mezrmouse) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FNirBerko%2FMezrmouse.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FNirBerko%2FMezrmouse?ref=badge_shield)

## Install

```bash
npm install --save mezrmouse
```

## Usage

```jsx
import React, { Component } from 'react'

import Measure from 'mezrmouse'

class Example extends Component {
  render () {
    return (
      <Measure distance={100} onCloseUp={(percent) => this.distance = percent} />
    )
  }
}
```

## License

MIT © [NirBerko](https://github.com/NirBerko)


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FNirBerko%2FMezrmouse.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FNirBerko%2FMezrmouse?ref=badge_large)