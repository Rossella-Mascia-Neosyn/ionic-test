# Ionic test

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