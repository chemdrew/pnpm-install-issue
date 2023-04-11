# pnpm-install-issue

> Bug popped up when using pnpm and created this repo to highlight it as simple as possible

### resolution

this ended up being an issue on my machine with core-js@2.6.12 messed up in the cache. Running `pnpm store prune` resolved it.

#### npm

```
> npm run test:npm
```

#### pnpm

```
> npm run test:pnpm
```
