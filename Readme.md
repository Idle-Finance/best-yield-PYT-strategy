# Idle Best yield strategy for Idle PYTs
This strategy allows [Idle Best yield](https://github.com/Idle-Labs/idle-contracts) to deploy capital in [Idle Perpetual Yield Tranches](https://github.com/Idle-Labs/idle-tranches).

Clearpool USDC PYT instance deployed at `0xd3af1317450d291c328525a8eb183d5cca45553d`

## Install

`forge install`

## Tests
run tests with the pinned block (although this should not be strictly required):

`forge test --fork-url https://eth-mainnet.alchemyapi.io/v2/$ALCHEMY_API_KEY --fork-block-number 15040750 -vvv`