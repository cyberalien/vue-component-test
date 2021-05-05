# Iconify for Vue

Test: `npm run build`

Build order:

1. `tsc` will compile .ts files to .js from `src` to `lib`.

2. `rollup` will bundle it all in `dist`.

3. `api-extractor` will bundle `.d.ts` files in `dist` (this step fails).

Component is in `src/icon.ts`.
