# Ionic test

## How use cli ionic
```
npm install -g @ionic/cli
```
```
ionic start
```

## How install tailwind

### Step 1: Install Tailwind CSS
```
npm install -D tailwindcss postcss autoprefixer
```
### Step 2: Generate Configuration Files
```
npx tailwindcss init -p
```

### Step 4: Configure Path To Template Files

```
module.exports = {
   content: [
     "./src/**/*.{js,jsx,ts,tsx}",
   ],
   theme: {
     extend: {},
   },
   plugins: [],
 }
```
### Step 5: Add Tailwind Directives
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## How install Daisy-ui
##### This repo using [Daisy-ui](https://daisyui.com/).

### Step 1: Install Daisy-ui:
```
npm i daisyui
```
### Step 2: Then add daisyUI to your tailwind.config.js files:
```
module.exports = {
  //...
  plugins: [require("daisyui")],
}
```

## How install react-aria
### Step 1: Install react-aria:

```
npm i react-aria
```
