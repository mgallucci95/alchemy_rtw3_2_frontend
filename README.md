## Getting Started

`npm install` to install dependencies

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Everything you need is inside `pages/index.js`.

To customize the website to load info from your own contract, change the following:

- Update `contractAddress` in `pages/index.js` to your own BuyMeACoffee contract on the Goerli testnet.
- Update `utils/BuyMeACoffee.json` to match the json artifact for your contract after compilation.
- Update the name and footer text in `pages/index.js` to your own name and info.
