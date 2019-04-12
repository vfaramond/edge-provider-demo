# Edge Provider demo

### Steps to reproduce wallet address issue

First you need to serve the `index.html` file. To do that, I'm using [serve](https://github.com/zeit/serve).

If you have [npm](https://www.npmjs.com/) installed, you can simply run:

```
npx serve -s .
```

1. Load the server URL using Edge Wallet developer mode
2. Click on “Select wallet“
3. Choose ETH wallet
4. Everything is OK 👍
5. Click a second time on "Select wallet"
6. Choose BTC wallet
7. The wallet address is the ETH address

Other way to reproduce:

1. Load the server URL using Edge Wallet developer mode
2. Click on “Select wallet“
3. Choose ETH wallet
4. Everything is OK, the wallet address is the ETH address 👍
5. Click on "Back"
6. Re-open the server URL
7. Click on “Select wallet“
8. Choose BTC wallet
9. The wallet address is the ETH address
