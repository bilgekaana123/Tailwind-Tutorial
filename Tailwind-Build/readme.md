[a link](https://github.com/user/repo/blob/branch/other_file.md)

### Create package.json

```
npm init -y
```

### Install tailwind

```
pm install -D tailwindcss
npx tailwindcss init
```

### Change tailwind.config.js

```
content: ["./src/**/*.{html,js}"],
```

### Create src/input.css

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Build

```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

### If you want to open another folder dist/.html

```
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```

### You create html with output.css

```
<link href="output.css" rel="stylesheet">
```
