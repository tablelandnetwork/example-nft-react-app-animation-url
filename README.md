# NFT React app for animation_url

This is a simple React app that you can build, push to web3.storage, and then include in your NFT metadata for dynamic rendering. 

### Example

https://testnets.opensea.io/assets/mumbai/0xb5fa5f64f811df209ef7cc431575870860b29cfb/2

You can see multiple examples of open and completed games. Chose any open ones (white background) from the collection https://testnets.opensea.io/collection/tableland-game-state-example-v2 to make your own guesses. 


### Smart contract

This app was used as part of the Polygon and Arbitrum NFT game state example, found here: 

https://github.com/tablelandnetwork/example-game-state-management

### Development

```
npm install
```

#### Build

```
npm run build
```

#### Deploy

We use the [Web3.Storage CLI](https://github.com/web3-storage/w3cli) for easy & fast deployment.

```
w3 up build/
```

https://bafybeicdh35zz4lrcfrkovuoicfjkwmbqdw5duvqxrjy7mhvdqa6panovq.ipfs.w3s.link/?table=game_store_80001_4448&token=2

