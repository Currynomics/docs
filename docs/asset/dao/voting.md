# Voting mechanisms
Among the five main types of voting mechanisms, **Currynomics will utilise time-weighted voting**. The selection process began by eliminating 1-token-1-vote as the least innovative and practical option. Reputation-weighted voting was deemed too complex due to the need for separate reputation evaluation mechanisms. Quadratic voting, which has yet to demonstrate a clear advantage for smaller stakeholders (Dimitri, 2022), requires further research to determine whether its utility justifies the complexity involved in implementing and explaining it to the community. 

Within the time-weighted voting category, **Currynomics will adopt conviction voting**, as simplicity is a crucial aspect for the ecosystem. It is important to note that bond voting is considered inflexible, and the ve-token model necessitates the creation of special-purpose ve-tokens, which would add unnecessary complexity to the governance processes.

## Conviction voting example
Let's consider two Currynomics members: Alice, who holds 100 tokens, and Bob, who holds 10,000 tokens. There are three proposals on the table: Proposal A, Proposal B, and Proposal C.

Alice stakes her 100 tokens on Proposal A for two weeks.
Bob stakes his 10,000 tokens on Proposal B for one day.

With time-weighted Conviction Voting, Alice's vote weight will increase over time as she keeps her tokens staked on Proposal A. Let's assume the voting mechanism has a 7-day halving period. After 7 days, her vote weight will double, giving her a vote weight of 200. After another 7 days (2 weeks in total), her vote weight will double again to 400.

Bob's vote weight starts at a higher value because he has more tokens. However, since he only staked his tokens for one day, his vote weight will not increase with time. His total vote weight will remain 10,000 for the duration of his stake.

Now, let's see how the proposals fare in this voting scenario:

Proposal A: 400 vote weight (from Alice's time-weighted stake)
Proposal B: 10,000 vote weight (from Bob's stake)
Proposal C: 0 vote weight (no one has staked tokens on this proposal)


In this example, even though Alice holds fewer tokens than Bob, her time-weighted Conviction Voting has increased her impact on the decision-making process. Although Proposal B still has the highest vote weight and would be favored to pass, Alice's support for Proposal A has become more significant over time. This encourages longer-term commitment from voters and can potentially reduce the risk of plutocracy and Sybil attacks.


<a href="https://redcurry.co/manifesto" target="_blank">
    <button class="nextButton" >
        <div class="copy">
            <p class="title">Next</p>
            <p class="value">Manifesto</p>
        </div>
        <div class="icon"><i class="material-icons">open_in_new</i></div>
    </button>
</a>
<!-- [Next: DAO Economics](/asset/dao/economics.md) -->
