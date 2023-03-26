# 11ty-webc-no-rebuild-repro

> Changes to 11ty `_components/**/*.webc` do not cause a site rebuild.

## Repro

1. Install dependencies and run development server
   ```sh
   npm install && npm run dev
   ```
2. Modify `_components/my-header.webc`
3. Changes will not be applied until manually restarting the server
