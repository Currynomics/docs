# Price Stability
> Redcurry Token stabilization methods.

The phenomena of manipulation of a token economy can be mitigated by introducing a mechanism for limiting the volumes of tokens moved, in part similar to those implemented by the regulated stock markets, where the excess and fall of a stock price determines the suspension of the same.

Moving tokens between accounts in a trade determines a token price and what is called a token velocity.

In order to obtain a stabilizing effect for the economy of a token, there can be two approaches:

### How arbitrage keeps Redcurry Token price stable

In a stable environment, Redcurry Token is only minted during token generation events (TGEs) which are initiated by Redcurry Holding and facilitated by the financial distribution partners.

Based on on-chain data, if Redcurry Token is trading above NAV, the protocol creates arbitrage opportunity by opening up Redcurry Token mintery. Investors can now buy Redcurry Token at NAV without having to wait for a TGE. Cash collateral goes up. When market price returns to NAV, mintery is closed. This allows for market makers to buy Redcurry Token at NAV from mintery and sell at a higher price on the market, stabilitstabilizing the price at NAV.

In the case of cash collateral growing above 10% of the total assets under management, pipelined real estate investments leads are realized and cash is invested increasing the AUM.

[INSERT MINTERY FORMULA]

Based on on-chain data, if Redcurry Token is trading below NAV, the protocol creates arbitrage opportunity by opening claims. Investors can swap Redcurry Token back against cash (stablecoin) at NAV. Cash collateral goes down. When price returns to NAV, claiming is closed. This allows for market makers to buy Redcurry Token from secondary market at a lower price and sell it to treasury at NAV stabilitstabilizing the market price at NAV.

Here we need to designs a system that incentivices investors not to run for the bank. The system also needs to guarantee, that in a hypothetical bank run scenario, the first one selling and the last one selling will receive the same. As they FRAX has constant buy-back option, they solve this by algorithmically controlling how much collateral vs goverrnance token the seller gets. Will this be a topic now or future?

In the case of cash collateral goes below XX% RE liquidation event will happen. This can happen in two conditions:
When market distribution partners have a selling pressure on us. We’ll buy the tokens back and fill our treasury first. When treasury has been filled on a threshold then we’ll start initiating the RE selling process. 
When RE selling process is initiated by the fund managers side. In whatever reason if the RE selling process is started we’ll lock NAV based on the amount of Redcurry Token from the treasury and burn them when the selling process is finished or unlock them back to treasury when selling process is cancelled.

[Next](minting/minting.md)
