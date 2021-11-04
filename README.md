# Twitter Spaces

## 2021-10-28

### Djed paper

 1. Features
	1. Algorithmically stabilized by a dynamic basket of goods.
	2. Requires a market crash of 60% or more in order to lose its peg.
	3. Minimal Djed
		1. There is a set target price.
		2. Djed evaluates the actual price: the quotient of the
           reserve and the number of stablecoins in circulation.
	    3. Djed maintains a minimum reserve ratio to reduce the risk
           of adversarial buying and selling. Thus, there is a
           threshold that will prevent people from purchasing or
           selling Djed back to the issuer.
	    4. Provided that the exchange rate remains constant, the
           equity per reservecoin always increases. Thus, the token
           will never be subject to draining.
	    5. Limitations
			1. If malicious user can predict exchange rate, the user
               can drain the reserves.
		    2. Every action changes the value, so many could be
               purchased at one time at a discount.
		    3. If the reserve ratio falls to one, the equity falls to
               zero making the target price of the reserve also zero.
		    4. Fees must be rigid.
			5. When the peg is lost, the coin holders suffer losses.
		    6. If the reserve ratio is close to the minimum, users may
               race to sell reserve coins, and future users can be
               barred from sale until the reserve ratio increases
               again.
	4. Extended Djed
		1. A nominal price is defined with a constant.
		2. The reserve ratio is dynamically adjusted.
		3. Liabilities are normalized.
		4. When it approaches what would have been the minimum reserve
           ratio, some of the liabiliities are converted to equity.
    5. Then they did model checking and dynamic analysis.
 2. Role in the ecosystem
	1. Babel fees
 3. Concerns and discussion

Notes:

> Lack of liquidity of these investments may cause the operator to be
> unable to react quickly enough to changes in demand, compromising
> the stability in the short-term. Another source of revenue are the
> fees or spread practiced when buying and selling the stablecoin. For
> example, if the operator sells USDT for 1.005 USD and buys USDT for
> 0.995 USD, it has a revenue of 1 cent for every USDT that it buys
> and then sells, while keeping the price stable within the range from
> 0.995 and 1.005.

![actions](djed actions.png)

> Minimal Djed enjoys several stability properties. The first one is
> that, in the normal reserve ratio range where purchases and sales
> are not restricted, users have no incentive to trade stablecoins
> outside the peg range in a secondary market. (In practice, there are
> other factors beyond the reserve ratio that may restrict inter-
> action of the user with the bank, such as blockchain congestion and
> high blockchain transaction fees. Such factors would have an effect
> on the ability of the bank to maintain the peg range in secondary
> markets.)

> The second stability property is that stablecoins remain pegged
> despite market crashes up to a magnitude that depends on the reserve
> ratio.

> Another crucial property is that the bank never becomes insolvent,
> which is a condition defined by having negative equity.

> Another important property is that, provided that the exchange
> remains constant, the bank is never in a state susceptible to bank
> runs where stablecoin holders would feel incentivized to race
> against each other to sell their stablecoins.

> The following theorem shows that, provided that the exchange rate
> remains constant, the equity per reservecoin always increases.


 
### Revolution in Scientific Transparency

 1. Pasteur put in his will not to let anyone see his lab notebook.
 2. Fraud and abuse in science as shown by [Elisabeth
    Bik](https://www.nature.com/articles/d41586-020-01363-z) in [her
    twitter](https://twitter.com/MicrobiomDigest) along with
    @mortenoxe, @TigerBB8 and @SmutClyde
 3. The field is pushing for more transparency, rigor, and reproducibility.
	1. [NIH policies and guidelines](https://www.niaid.nih.gov/grants-contracts/rigor-and-reproducibility-forms-f)
	2. [FlowRepository](https://flowrepository.org/) and the [role of Flow Cytometry](https://onlinelibrary.wiley.com/doi/10.1002/cyto.a.23940)
	3. [Journals](https://www.nature.com/articles/533452a)
	4. [Ngram](https://books.google.com/ngrams/graph?content=rigor+and+reproducibility&year_start=1800&year_end=2019&corpus=26&smoothing=3&direct_url=t1%3B%2Crigor%20and%20reproducibility%3B%2Cc0)
	5. [How-to guide](https://journals.asm.org/doi/10.1128/mBio.01902-16)
 4. Potential strategies to get started
	1. Hash data automatically and store hashes in NFTs on the blockchain.
	2. [Publishing](https://www.nature.com/articles/533452a)
	3. Publishing anonymously and verifying data authenticity
	4. VABrandon's note that QC and reagents could be stored
       on-chain. I should say that probably hashes will be sufficient,
       but we can do side-chains.
 5. Action items
	1. Task force to identify current projects and implement
       proof-of-concept for data hashing
	2. Task force to imagine how an academic system of anonymous or
       pseudonymous publishing would work (apropos of Charles Hoskinson)
    3. We should speak with FlowJo at BD. 

## Decentralised Autonomous Organization (DAO) Models

 1. Compare against business models.
 2. Found excellent articles on dows in general.
 3. Inefficiencies in trad. companies DAOs can slove.
