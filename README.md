# DigiLab Pro — flattened source layout

The original `src/` directory has been removed. Its source files are placed in the project root:
- `App.tsx`, `main.tsx`, `index.css`
- `components` files are named `components_*.tsx`
- `hooks` files are named `hooks_*.ts`
- `lib` files are named `lib_*.ts`
- `utils` files are named `utils_*.ts`

Imports were rewritten to point to the flattened filenames. The original project configuration,
package manifest, lockfile, and all source contents are retained.

## Run
1. Install Node.js (LTS).
2. Run `npm ci`.
3. Run `npm run dev`.
4. For a production build, run `npm run build`.

Note: This is a source-layout conversion; it does not claim that all application features
have been runtime-tested or that pending simulations have been implemented.
