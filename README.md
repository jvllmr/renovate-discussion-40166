# Discussion 40166

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

With `uv` rangeStrategy set to `bump` the `pytest` range is bumped to latest v9 version because v9 is locked, but the original range is `>=8.4.2`

## Expected behavior

`pytest` range is bumped to latest v8 or not at all.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/40166
