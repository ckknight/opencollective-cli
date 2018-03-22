# opencollective-cli

For the official `opencollective-cli` project, see https://github.com/opencollective/opencollective-cli

The purpose of this repository is to provide a "compatible" `opencollective-cli`
project that does not have any dependencies.

Given the CLI nature of `opencollective-cli`, as long as the `oc` and
`opencollective` binaries are available and the script exits with a status code
of 0, that is "compatible" enough.

## How to use with Yarn

If your project has a dependency that relies on `opencollective-cli`, add
the following to your `package.json`:

```json
"resolutions": {
  "opencollective": "ckknight/opencollective-cli"
}
```

If you already have `"resolutions"`, then only the `"opencollective"` line
needs to be added.
