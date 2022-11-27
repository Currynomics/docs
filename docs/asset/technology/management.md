# Data Management
This section describes in detail Redcurry’s asset tracking, reporting, NAV calculations, and system actors.

## Asset tracking
Redcurry accounting methods and principles follow local GAAP and International Financial Reporting Standards (IFRS) respectively, to track all assets under management (AUM). These assets can be cash (liabilities, receivables, cash on account) or non-cash shares in funds, securities, other long-term assets, etc.), all generating large amounts of accounting data.

This data is managed using off-chain tools and processes following the above-mentioned standards. Software similar to Inveniam.io, MS Power BI, Excel, and other known accounting software is used by the respective asset and property management companies.

For calculating the NAV, which ultimately affects the real value of Redcurry token, essential information is derived from the larger set of accounting data and is reported on blockchain by accountants and asset managers belonging to separate organizations in various regions and countries with independent interests, goals, and responsibilities - truly decentralized actors.

## Essential information
According to the above-mentioned standards, the following information per asset is considered essential in calculating the total net value of the treasury. In other words, each asset is represented by its own set of essential information:

* Original acquisition value (OAV).
* OAV Impairment (OAV-I).
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

This information is used to calculate the NAV per asset. The sum of all asset NAVs makes up the total NAV defining the Redcurry token value.

This aggregation and derivation of essential information is done by accountants and asset managers belonging to separate organizations in various regions and countries with independent interests, goals, and responsibilities.

Each actor works on their asset portfolio to derive the correct set of essential information and to publish that on-chain. This process introduces a natural level of decentralization. 

The actors responsible for deriving this essential information from the accounting data of their portfolio and ultimately signing it off by publishing it on the blockchain are called essential actors.    

## NAV calculation
Using the essential information defined above, the net asset value of individual assets are calculated usign the following formula.

> NAV<small>asset</small>= OAV - OAVI + OLTA + OSTA + REC - LIA + COA

Total NAV is made up of all the individual asset NAVs and is calculated using the formula below.
> NAV<small>total</small> = NAV<small>asset 1</small> + NAV<small>asset 2</small> + ... + NAV<small>asset N</small>

Net asset per token is calculated by dividing the total NAV with the total supply. This is also the officially reported price of the token.
> NAPT = NAV<small>total</small> / SUPPLY<small>token</small>

## Essential Actors
Each set of assets has an unrelated asset manager and accountants. For each asset, the essential actors need to derive and publish (sign off) all essential information and the consecutive NAV to a public blockchain. Redcurry, although owning all, seldomly fulfills this manager role. 

Essential actors are people fulfilling the following roles:
* Property Manager (usually per building)
* Asset manager (usually per fund)
* Accountant
* Redcurry executive member
* Auditors (both internal and external)

There will be many people fulfilling these roles at once and they are made up of often unrelated groups of people each belonging to separate organizations.

The interaction needed to be done on blockchain is facilitated by the technology developed by Currynomics. The open-source smart contracts, web3 interface, doxxed MPC wallets, approval chains, and other necessary technology is institutional grade highly secure solutions combined, developed, or taken into use by Currynomics.

## Asset Reporting
Each asset with its essential information is reported on the public blockchain once a week or month depending on the asset. For each asset update, essential actors need to sign the transaction with wallets assigned to them through an MPC wallet system.

The publishing of each asset and the consecutive updates can only be done by the people who were assigned as the assets' essential people during the creation of the said asset. This is enforced by the smart contract source code which is also open source allowing for public auditability.

### Reporting Period
As a rule, asset updates are reported once a month. As exceptions, there may be assets that need more frequent reporting (like cash positions of SPV) and they will be done according to the needs of the asset in question.

During normal reporting, a report can only be published when it is signed off by the essential actors assigned to the respective asset. Once a year, an end-of-the-year (EOY) report is published. The content and structure of the EOY report are the same as any other report with the difference that here, an auditor and Redcurry board member is added to the essential actors' list needed to publish the report and the update will get a respective “audited” flag.

This enforces an immutable and transparent chain of asset data evolving throughout the year and culminating in a logical summary once per year. If there is any large deviation in the EOY report, it will stand out from the other reports enhancing the ability to quickly and publicly detect irregularities and faults in reporting of the NAV. What is more, all reported data can be linked to official registries off-chain (e.g. governmental property, business, or land registry).

### Reporting Technology
For a transparent and immutable reporting, Redcurry uses low transaction fee EVM compatible public blockchain.

Each asset is on-chain as an ERC721 token storing the assets essential information and changelog. The smart contract responsible for tracking the assets and their NAV is called Proof of Reserves (POR) Smart Contract

Any transaction with the smart contracts, be that initial publishing or later updates, can only be done through the Governor Smart Contract. This design principle enforces that any changes to the NAV and Supply is atomic - one cannot change without the other. In addition to facilitating NAV and supply change, the Governor contract is responsible for the following:
* Defines access control and roles
* Define rules on NAV and supply change, enforcing the Foundation rules.
* Enable public auditability for the rules defined can be easily checked by anyone.
* Track total system NAV and supply for ease of access.
* Conduct AML checks using third party oracle (e.g. Chainalysis) and block suspicious wallet activity in the Reducrry system.
* Validate user input to spot errors and asymmetries in NAV or Supply change expectations.
* Calculate true supply change according to NAV updates to maintain peg and avoid human errors.
* Gateway to third party oracles - help with Supply and NAV validation.

## Transaction fee
From all Redcurry transactions, there will be a transaction fee of **0.02%** which goes into the DAO treasury and will be distributed to pools following current DAO tokenomics.

<a href="/#/asset/technology/oracle">
    <button class="nextButton" >
        <div class="copy">
            <p class="title">Next</p>
            <p class="value">Oracles</p>
        </div>
        <div class="icon"><i class="material-icons">arrow_forward</i></div>
    </button>
</a>

<!-- [Next: Oracles](/asset/technology/oracle.md) -->