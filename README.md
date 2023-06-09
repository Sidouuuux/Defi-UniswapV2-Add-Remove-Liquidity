
# ✨ Uniswap V2 Add/Remove Liquidity ✨
This contract allows users to add and remove liquidity from the Uniswap V2 pool
# Requirements 🔧

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [Foundry](https://book.getfoundry.sh/getting-started/installation)
  - You'll know you've installed Foundry right if you can run:
    - `forge --version` and get an output like: `forge x.x.x`

# Usage 📝

## Deploy 🚀

```
forge create --rpc-url INSERT_RPC_API_ENDPOINT \
--private-key YOUR_PRIVATE_KEY \
src/UniswapV2Swap.sol:UniswapV2Swap
```

### Compile 📝

```
forge build
```

## Testing 🧪

```
forge test --fork-url FORK_URL -vvv
```


## Generate Documentation 📝

You can generate documemtation by adding NatSpecs to your contract and run:

```
forge doc --serve --port 4000
```
## Estimate gas 💸

You can estimate gas running:

```
forge test --fork-url FORK_URL -vvv --gas-report
```