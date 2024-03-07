# action-pnpm-setup

Combined action to set up nodejs and pnpm

## Usage

Use inside your github workflow job steps

```
//...
steps:
 - id: foo
   uses: My-Property-Business/action-pnpm-setup@v1
   with:
    node-version: 21.x // optional, defaults to 16.x
    pnpm-version: 7.x // optional, defaults to 7.30.x
```
