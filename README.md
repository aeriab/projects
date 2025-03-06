
Hello, this is me playing around with framer-motion, tailwindcss, and next.js


You may be able to access this prototype from: https://aeriab.github.io/fancy-website-project/


## Getting Started For Developers

Setup your dev environment:

```bash
cd fancy-website-project    # If not already at project directory
npm install next@latest react@latest react-dom@latest
npm install three
npm install react-icons
npm install @react-three/fiber three
```

To run the development server:

Lines 7 & 8  on next.config.js must be commented out.

```bash
npm run dev
```

If successful, the project will run at:
http://localhost:3000


To deploy the product using github pages, you must first ensure:

Lines 7 & 8  on next.config.js are not commented out.

Then you can run:
```bash
npm run build
npm run deploy
```

testing change