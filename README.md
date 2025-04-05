# essexcountymoths
essexcountymoths.com

An old legacy site (soon to be updated?)

## Old Build

npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

tailwind.config.js:

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
