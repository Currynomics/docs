# Overview
All smart contracts will be developed on an EVM compatible blockchain. Redcurry and DAO governance tokens will be implemented using the ERC20 standard the asset reporting smart contracts using the ERC720 standard.

The product has to successfully carry out the following requirements:
* Meet the requirements defined in the Currynomics cybersecurity principles.
* Allow secure and transparent reporting of Redcurry token reserve assets (making up the NAV) on-chain. The assets making up the NAV can be the following:
    * Cash
        * Cash on accounts
        * RedCurry Holding or subsidiary company receivables and liabilities
    * Non-cash
        * Real estate portfolio
        * Fund shares or equity
        * Consolidated asset group
* Allow for secure and transparent pegging of Redcurry tokens to Treasury NAV. This includes:
    * NAV reporting and updates (update assets on-chain).
    * Token supply updates (minting and burning of Redcurry tokens).
    * Both NAV and Supply change has to be an atomic operation (with exceptions).
    * Smart contract management framework for managing access, keeping logs, and monitoring the activity of smart contracts.
    * Public dashboard as a window into the on-chain data (Redcurry explorer).
    * Development and security operations of smart contracts
    * Institutional grade MPC wallet management.


[Next: Architecture](/asset/technology/architecture.md)