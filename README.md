<div align="center">
<img height="180" src="https://app.parcl.co/favicon.png"/>
<h1>Parcl Keeper</h1>
</div>

Example parcl-v3 keeper bots written in Rust and TypeScript.

## Keepers

| Keeper Name | Info                                                                                                                                                                                                                                                                             |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Liquidator  | Watches margin accounts for liquidatable accounts and accounts currently in liquidation. If an account is found, then the service attempts to liquidate the account. Liquidator's margin account earns the liquidation fee rate applied to the total notional liquidated amount. |
| Settler     | Watches settlement requests and processes the mature requests. Each settlement request has a optional tip that goes to the settler keeper.                                                                                                                                       |
