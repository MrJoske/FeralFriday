## Local Development

1. Install dependencies:
   ```sh
   npm install
   ```
2. Start the dev server:
   ```sh
   npm run dev
   ```

## Build for Production

```sh
npm run build
```
The output will be in the `dist` folder.

## Deploying to Cloudflare Pages

1. Push this repository to GitHub (or another supported git provider).
2. In Cloudflare Pages, create a new project and connect your repository.
3. Set the build settings:
   - **Framework preset:** Vite
   - **Build command:** npm run build
   - **Output directory:** dist
4. Deploy!

The site will be served from the built `dist` directory.

