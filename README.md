# Chain Assets

We collected the logos of the most common cryptos. It's free, you can use the assets, too 🦾

## How to Use

We followed a simple naming convention. Please check the following code snippet.

```ts
// example: usdc
const normalizedTokenSymbol = tokenSymbol.trim().toLowerCase().replace(/[^\w\d-]/g, '-');

// example: https://raw.githubusercontent.com/neobase-one/chain-assets/main/images/usdc/usdc.webp
const tokenLogoUrl = `https://raw.githubusercontent.com/neobase-one/chain-assets/main/images/${normalizedTokenSymbol}/${normalizedTokenSymbol}.webp`
```

**Note:** We decided to use `webp` for all image assets.


