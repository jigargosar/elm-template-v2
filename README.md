# Elm + Parcel Template

This project is a starter template for building Elm applications using [Parcel](https://parceljs.org/) as the bundler.

## Project Structure

```
elm.json         # Elm project configuration
index.html       # Main HTML file
package.json     # Node.js dependencies and scripts
src/
  index.js       # JavaScript entry point (for Elm interop)
  Main.elm       # Main Elm application file
```

## Getting Started

1. **Install dependencies:**
   ```sh
   pnpm install
   ```

2. **Start the development server:**
   ```sh
   pnpm start
   ```
   This will launch Parcel, which will compile your Elm code and serve the app at `http://localhost:1234`.

3. **Edit your Elm code:**
   - Make changes in `src/Main.elm`.
   - Parcel will automatically reload the browser when you save changes.

## Building for Production

To create an optimized build for deployment:

```sh
pnpm exec parcel build index.html
```

The output will be in the `dist/` directory.

## Notes
- Elm is configured via `elm.json`.
- Parcel handles Elm compilation and hot reloading.
- You can add more pnpm or Parcel plugins as needed.

## License

MIT
