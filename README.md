# Typescript - Mocha - Chai Boilerplate

> Boilerplate for typescript with testing using mocha and chai (this is not intended to be used in production)

## Prerequisites

```
npm install -g mocha istanbul
npm install
```

## Build

```
npm install -g typescript
# and build using VScode
```

## Testing

```
source env
test <dir>
cover <dir>
```

Or, manually,

```
mocha --no-timeouts --recursive --require=source-map-support/register <dir>
istanbul cover node_modules/mocha/bin/_mocha -- --no-timeouts --recursive --require=source-map-support/register <dir>
```

You must install `mocha` locally in order to use `istanbul` properly.
