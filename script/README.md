# WETH-only deployment scripts

Only the WETH branch is retained in the deployment and setup scripts.
The USDaf deployment script and non-WETH branch configuration have been removed.

These are still upstream BOLD deployment addresses, NOT Florin deployment
configuration. Do not broadcast these scripts as a Florin deployment. FUSD
addresses, administrative roles and pause propagation remain a separate step.
The generic strategy/factory contracts are not restricted to WETH by this cleanup.
Historical broadcast artifacts are retained unchanged as provenance.

## Upstream WETH deployment reference

** yBOLD **

Factories/Periphery:
- accountantFactory:  0xDeCAFB666eE4F9c5E9F5B26Dc02E443035717D55
- stakerFactory:  0x4219A2084e77865Ed94607412a96f5e503278869
- strategyFactory:  0x73dfCc4fB90E6e252E5D41f6588534a8043dBa58
- auctionFactory: 0xa3A3702d81Fd317FA1B8735227e29dc756C976C5
- accountant: 0x53acEBB9470Cfc9D231075154f5dcF1586A4c6fa
- aprOracle: 0x555f3FFe6c5c6C65609d8627ef30dA0aF9060B3D
- aprOracle (new, sp yield fix): 0x7a7F1C839cf7807D788Da5276A0174Fc2Bb14409
- vaultReportTrigger: 0xFdfEbEE8eD1Ae9Fed6b5b23FfE6dFa14E84c9B3A
- strategyReportTrigger: 0xb9F57B62Cbe9463da16E5b75e3B809321a0eA871
- zapper: 0xE7099092533A3FB693Bb123cD96B8e53b4d83C58
- OnLossDepositLimitModule: 0x746C238E34a6dBFE1d35d50471467Bd7Bf898f62
- Factory (with Auction 1.0.4): 0xbf7A38C6de0831916301B8dD09BD72FBd0C547D1
- referral zapper: 0xaACE12d8e8B8BCD16212CB656C912dBC36EFD782

yBOLD:
- yBOLD: 0x9F4330700a36B29952869fac9b33f45EEdd8A3d8
- WETH Strategy:  0x2048A730f564246411415f719198d6f7c10A7961

WITH AUCTION 1.0.4:
- WETH Strategy:  0xc5e7D3F76a03006540f17668A0267C668FFb5b75

st-yBOLD:
- 0x23346B04a7f55b8760E5860AA5A77383D63491cD
