# Asset tracking
Redcurry accounting methods and principles follow local GAAP and International Financial Reporting Standards (IFRS) respectively to track all assets under management (AUM). These assets can be cash (liabilities, receivables, cash on account) or non-cash (shares in funds, equity, SPVs with their nested accounting, tokens of tokenized property, etc), all generating large amounts of accounting data.

This data is managed using off-chain tools and processes following the above-mentioned standards. Software is similar to Inveniam.io, MS Power BI, Excel, known accounting software, and others.

For calculating the NAV, which ultimately affects the actual value of the currency, essential information is derived from the entire set of accounting data and reported on blockchain by accountants and asset managers belonging to separate organizations across geography and countries with independent interests, goals, and liabilities - decentralized actors.

## Essential information
According to the above-mentioned standards, the following information per asset is considered essential in calculating the net value of the total treasury assets. In other words, each asset is represented by its own set of essential information:

* Original acquisition value (OAV).
* OAV Impairment (OAV-I).
* OAV Revaluation (OAV-R).
* Other long-term assets (OLTA).
* Other short-term assets (OSTA).
* Receivables (REC).
* Liabilities (LIA).
* Cash on accounts (COA).
* Asset group:
* Long term
* Short term
* Receivable
* Liability
* Market Value (MAV) - this is informative and encrypted at rest (due to the difference in methods and how MAV is to be used in calculating NAV if at all.)

This information is used to calculate the NAV per asset. The sum of all asset NAVs makes up the total NAV used to calculate the currency value.

## Asset NAV calculation
Total NAV is made up of all the individual asset NAVs and is calculated using the formula below.
> NAV<small>total</small> = NAV<small>asset 1</small>+ NAV<small>asset 2</small>+ ... + NAV<small>asset N</small>

Net Asset Value Per Token (NAPT)
> NAPT = NAV<small>total</small> / SUPPLY<small>token</small>

This aggregation and derivation of essential information is done by accountants and asset managers belonging to separate organizations across geography and countries with independent interests, goals and liabilities - decentralized actors.

Each actor works on their own asset portfolio to derive the correct set of essential information and to publish that on-chain. This process introduces a natural level of decentralization. 

The actors responsible for deriving this essential information from the accounting data of their portfolio and ultimately signing it off by publishing it on blockchain are called essential actors.

[Next: Legal Structure](/asset/legal/overview.md)
