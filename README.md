# Steps to Reproduce

```sh
pnpm i
pnpm dev --turbo
```

It should generate a `layout` file, but it doesn't.

For comparison, run the following command:

```sh
pnpm dev
```

Regular `pnpm dev` will generate the `layout` file as expected.
