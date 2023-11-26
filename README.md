# redox-reality-promo

### 🎨‍ Tailwind CSS

Only the Tailwind CSS classes that are actually used are included in the project (in [dist/styles.css](dist/styles.css)). So make sure you include any new classes you want to use with the below commands.

Generate styles during development
```
npx tailwindcss -o dist/styles.css --watch
```
Generate optimized styles for production
```
npx tailwindcss -o dist/styles.css --minify
```