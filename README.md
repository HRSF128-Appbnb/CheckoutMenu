# ReservationMenu

> Reservation portion of vacation rental application

## Related Projects

  - https://github.com/HRSF128-Appbnb/photo-carousel
  - https://github.com/HRSF128-Appbnb/Proxy0
  - https://github.com/HRSF128-Appbnb/PhotoGallery


## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

> Start mongo (Linux: sudo service mongod start | Mac: mongod)\
> npm run seed\
> npm run server-dev\
> (separate terminal) npm run react-dev\
> (in browser) url: http://localhost:3004 \
> (if eslint v7.3.0) line 236 of node_modules/eslint-config-airbnb-base/rules/imports.js needs to be changed from 'import/no-cycle': ['error', { maxDepth: Infinity }], to 'import/no-cycle': ['error', { maxDepth: 10 }],
## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node 6.13.0
- Eslint 7.3.1

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install
```
