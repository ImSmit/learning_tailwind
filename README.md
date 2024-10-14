## Get Started [🔗](https://tailwindcss.com/docs/installation/using-postcss)

**1. Install Tailwind**
```npm install -D tailwindcss postcss autoprefixer```

**2. Install Vite** 
```npm i vite```

**3. Init Tailwind** 
```npx tailwindcss init -p```

**4. Inside Tailwind tailwind.config.js** 
``` content: ["*"] ```

**5. Create style.css File And Add Diractives** 
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

**6. Inside Package.js Add** 
``` 
  "scripts": { 
    "start":"vite"
  },
```

**7. Inside index.HTML Add** 
``` <link rel="stylesheet" href="style.css">```