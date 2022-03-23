# Cryptolaw Resources and Repos

[Blockchain 2021](https://practiceguides.chambers.com/practice-guides/blockchain-2021) - DLx Law guide to blockchain and cryptocurrency law and regulation in 18 jurisdictions

[LexDAO's Lex Corpus](https://github.com/lexDAO/LexCorpus) - contract library for legal engineering

[lex_node's Cryptolaw Emporium](https://github.com/lex-node/lex_node_cryptoLaw_emporium)

[Cryptolaw News Aggregator](https://news.octal.one/) by Octal

[Open Source Law Repo](https://github.com/ErichDylus/Open-Source-Law) - open source templates, forms, and other materials for DAOs, devs, and incentive programmers

# Smart Contracts v. Traditional Contracts
Smart/Ricardian contracts and traditional, written contracts may be used together to provide an optimized level of security and efficiency in enforceability, while leaving flexibility for sensitive "meatspace" terms and mutual amendments in the parties' preferences. 

 •  if a participant is able to execute a smart contract through its construction, this could be deemed an offer; if the smart contract is sent to a counterparty directly, that smart contract likely constitutes an offer solely to that counterparty; 

 •  by signing their private signature to the smart contract, the counterparty has effectively given acceptance to the agreement; and 

 •  the element of consideration may be satisfied provided each party in the smart contract exchanges some form of value.

Depending on numerous factors, there may be elements of direct [legal contract formation in smart contracts](https://lexdao.substack.com/p/legal-contract-formation-in-smart) by the Solidity code's construction, intended interactions, etc. 

Governance and Dispute Resolution in blockchain-native entities are constantly iterating. [Kleros](https://kleros.io/static/whitepaper_en-8bd3a0480b45c39899787e17049ded26.pdf) and others seek to establish frameworks for decentralized justice, and generally dispute resolution is being researched to [bridge the governance gap](http://www3.weforum.org/docs/WEF_WP_Dispute_Resolution_for_Blockchain_2020.pdf). 


## "Code is Law" v. Code Deference 

Parties may want to eschew the Ricardian, unqualified ‘code is law’ approach in their contracting, and instead document the agreed level of deference to code's execution, perhaps adapting a form similar to the following: [Simple Code Deference Agreement](https://github.com/ErichDylus/SCoDA-Simple-Code-Deference-Agreement-). In this instance, parties are agreeing that, except in certain narrow express circumstances, they will defer to (or, refrain from legal dispute over) the results of the underlying smart contract's operation. Code deference has limitations, as examined in [this article](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3889630) by Drew Hinkes, who notes it may best be viewed as a mechanism to "rebalance incentives by increasing the opportunity costs for a decentralized venture participant to sue over a smart contract outcome and providing efficient alternatives to litigation."

# Cryptocurrency and Blockchain Laws and Regulations
For crypto- or blockchain-based entities, it is imperative to consult local counsel for the jurisdiction or jurisdictions in which you are based, conducting business, soliciting funds or usage, the governing law of any underlying agreements, and any other pertinent law - especially so if any type of coin or token offering is contemplated. Here's a non-exhaustive list of example laws, regulations, and other legal constructs to consider:

• The GDPR sets out data privacy and data protection rules under EU law, as outlined in the [GDPR Compliance Checklist](https://gdpr.eu/checklist/)

• The Uniform Commercial Code ("UCC"), Uniform Electronic Transactions Act ("UETA"), and Electronic Signatures in Global and National Commerce Act ( the "E-Sign Act") generally govern American digital commerce agreements, absent a treaty or federal preemption. 
   UCC Exclusions under E-Sign Act and UETA: all sections except 1-107 (Waiver of Renunciation of Claim or Right After Breach), 1-206, (Statute of Frauds for Kinds of Personal Property Not Otherwise Covered), Article 2 (Sales) and Article 2A (Leases)
   UCC Article 9 security agreements are excluded, but Article 9 already allows for "electronic records" and electronic "authentication." Article 3 negotiable instruments are excluded, but safe harbor rule allows for electronic "transferable records" that are unique and identifiable, with a single authoritative copy identifying controller.
   UCC has certain "possession" and "control" provisions that have so far been untested in the context of private keys and "ownable" smart contracts

• The US's 21st Century IDEA Act (Integrated Digital Experience Act) establishes deadlines for federal government agencies to provide mobile and accessible versions of their websites, digital forms and services, and electronic signatures, greatly streamlining potential integration into smart contract processes.

• Commodity Exchange Act and U.S. SEC and CFTC regulations may apply to digital currency transfers and purchases via smart contracts.

• The Bank Secrecy Act, the Patriot Act, and other Anti-Money Laundering and Money Transmission laws and regulations are imperative US laws to follow in remittance of cryptocurrencies and/or fiat currencies through public blockchain technologies and in determining KYC requirements. 

• [0x Legal Wiki and Library](https://0x.org/wiki#Legal-Wiki) provides useful US law resources especially applicable to exchanges and DEXs, but also for OFAC and AML concerns 

• Tax laws and regulations (International treaties, Federal, State, and local) must always be addressed in transfers of value.

• Money transmission laws and regulations (International treaties, Federal, and State) apply to digital currency transfers.

• GDPR: extraterritoriality (the operation of laws outside the boundary of a state or country) may affect an international company that collects data on EU citizens - it is under the same legal obligation it would be if  headquartered in the EU, even without presence there. Generally, Cravath, Swaine & Moore LLP recommends "four guiding principles for entities hosting GDPR‑compliant blockchains: Use a private, permissioned blockchain; avoid, if possible, the storing of personal data on the blockchain; establish a detailed governance framework; and employ innovative solutions to data protection problems." While ongoing security and privacy implementations may invalidate some of these points, they should not be ignored.

The UK Jurisdiction Task Force has released a [statement](https://35z8e83m1ih83drye280o9d1-wpengine.netdna-ssl.com/wp-content/uploads/2019/11/6.6056_JO_Cryptocurrencies_Statement_FINAL_WEB_111119-1.pdf) on the legal treatment of cryptoassets and smart contracts, more clearly defining the UK position on enforceability and classifications. Linklaters notes that the legal statement provides that the asset is "not any of the public or private keys, or the distributed ledger data itself. None of those constitute property but rather they are mere information. Instead, the asset is something that arises from their combination with the relevant system rules (including the embedded cryptography): the exclusive ability to update or spend transaction data." Further, the statement acknowledges that security over a cryptoasset may be accomplished by way of charge or mortgage, but not pledge or lien.

Security Token Laws and Regulations
For any token issuance or transactions through smart contracts that may involved a security changing hands, it is crucial to seek legal advice regarding applicable securities laws and regulations (including but not limited to International, Federal and State jurisdictions) beforehand. Examples of American regulations include:

 - Reg D (Private Placement Exemption): "accredited investors" only, as defined by the SEC

 - Reg A (Limited Amount Exemption)  non-accredited investors for maximum $50 million 

 - Reg S (International Exemption)

 - Reg CF (Crowdfunding)

In the EU, token issuers generally have to submit a prospectus and comply with local security laws, except when qualified by certain exceptions, such as:

 - Qualified investors’ exemption (private placement): solicit "qualified investors" only for the STO, as defined by EU regulations.

 - Large investments exemption: companies may sell their securities freely if every investor buys at least a statutory minimum amount each.

 - Limited network exemption: Companies may issue security tokens to up to a certain number of individual people or entities per EU member state without submitting a prospectus.

 - Limited amount exemption: companies may sell securities valued up to a certain threshold amount over a one year period without submitting a prospectus.  Individual EU Member States may exempt domestic offers where the total amount offered in the EU is between a certain range of amounts. 

- Growth Prospectus:  starting July 21, 2019, SMEs (companies with a market cap of up to €43 million, turnover of up to €5 million or fewer than 250 employees) and mid-sized companies admitted to an SME Growth Market may use a simplified document when offering securities to the public, provided that their securities are not traded on a regulated market.

When an EU Prospectus is submitted, the PR requires that summaries set out the 15 most material risk factors specific to the issuer, and the guarantor (if applicable). Possible risk factors for token issuers and smart contract-related entities may include errors in code, protocol forks, crypto market volatility, technological obsolescence, and security. It is important to note that civil liability could arise in respect of a summary that is misleading, inaccurate or missing material information when read along with the rest of the prospectus.


Morrison Cohen's [Cryptocurrency Litigation Tracker](https://www.morrisoncohen.com/news-page?itemid=471) tracks SEC, CFTC, and criminal litigation; other public regulatory proceedings and summary orders; class action and private litigation; and major pronouncements by U.S. regulators about cryptocurrency. 

# Digital Signatures and Click-Wrap Transactions
Courts have already looked upon digital signatures and click-wrap agreements with overwhelming favor, and smart contracts in their simplest form are likely to be viewed as a natural extension. Some examples of favorable statutory precedent are UETA and the E-Sign Act. Questions of a contract's enforceability or whether a contract has actually been executed typically fall within the purview of common law (where applicable) and thus are subject to numerous potential interpretations, especially in instances where jurisdiction is uncertain due to the distributed/decentralized nature of smart contracts.

Digital signatures utilizing DLT or in a blockchain context do not yet have meaningful judicial precedent. However, a signature under public key encryption is likely to follow the same evaluations as a simple e-signature (such as a digitally signed PDF or merely an email with a designated name): did the signer actually execute, and did the signed have the intention to do so, the capability to do so, and the authority to do so?

## Arbitration, Dispute Resolution, and Litigation
Smart contracts, or traditional contracts leveraging smart contract technology for certain terms or conditions therein, may integrate any traditional jurisdictional or dispute settlement clauses. However, Blockchain-based arbitration may present some interesting legal intricacies when the points to be arbitrated are non-binary or non-discrete, or in the instance of mistaken award. 


## DAOs
Decentralized Autonomous Organizations ("[DAO](https://medium.com/@OpenLawOfficial/the-era-of-legally-compliant-daos-491edf88fed0)s") are decentralized, "headless" entities which rely on smart contracts to automate certain operations, governance, and behavior. This reduces overhead, permits greater organizational transparency, and tightens internal controls. DAOs effectively decentralize identifying aspects of traditional entities such as jurisdiction of organization, principal place of business, and raise novel concerns in liability apportionment-- as such, regulatory compliance of DAOs, especially in the U.S., is tricky. LexDAO is a legal engineer club building web3.0 legal assets and code, such as escrow and dispute resolution, powered by Ethereum transactional scripts via an Aragon DAO. ZeroLaw LLC is undertaking to refine a model [DAO charter](https://github.com/lex-node/SCoDA-Simple-Code-Deference-Agreement-/blob/master/DAO%20Charter%20with%20Qualified%20Code%20Deference.md) for DAOs wishing to function as unincorporated associations. DAOs often create a corresponding "legal wrapper" meatspace entity in order to interact with traditional entities in meatspace contracts and generally soak up liability.

The [LAO](https://medium.com/openlawofficial/the-lao-a-for-profit-limited-liability-autonomous-organization-9eae89c9669c), envisioning a more broadly applicable Limited Liability Autonomous Organization, seeks to lessen "meatspace" (or human, non-decentralized actor/input/output) liability through the use of Ricardian Contracts in apportioning capital. The LAO and OpenLaw are continually developing and progressing the [taxonomy](https://medium.com/@thelaoofficial/a-taxonomy-for-laos-making-sense-of-the-emerging-lao-ecosystem-1122b035fe1a) and risks of such structures, setting forth autonomous entity formation options such as the Decentralized Automated Corporation (DAC), Limited Liability Autonomous Company (LLAC), and the Limited Autonomous Cooperative (LAOP).

Smart contracts and DAOs present several advantages and possibilities for built-in regulatory compliance, as noted by the U.S. Commodities Futures Trading Commission's LabCFTC: smart contract collateral or proceeds cannot be sold to a non-Eligible Contract Participant (without clear digital forensic evidence on the blockchain), the contract may be coded so the transaction may not occur until the mandated period has passed, and it may incorporate automated reporting of required data or tax payments at pre-determined intervals.

Wyoming has recently codified the recognition of limited liability DAOs, opening the door to further entity process automation: [Forming and Operating a Wyoming DAO LLC](https://dilendorf.com/resources/forming-and-operating-a-wyoming-dao-llc.html) - Dilendorf & Tabba, 2021

[DAO Model Law](https://coala.global/reports/#1623963887316-6ce8de52-e0a0) - A proposed international uniform, model set of rules to provide legal certainty for DAOs and their members and participants by the Coalition of Automated Legal Applications (COALA), 2021

[Resources for DAOs and Creators](https://kinjal.mirror.xyz/eD3-Sgv2h50j-kwjHQCOnwqMKqSLTfnrqrtNypU-P5k) - Kinjal Shah

[LexDAO](https://github.com/lexDAO/LexCorpus/blob/master/contracts/legal/dao/membership/TUNAA.md) and [a16z](https://a16z.com/wp-content/uploads/2021/10/DAO-Legal-Framework-Jennings-Kerr10.19.21-Final.pdf) have penned materials on the case for Unincorporated Nonprofit Associations as DAO legal wrappers. 

[Foundations](https://medium.com/@erich.dylus/api3-year-0-wrapped-dao-and-legal-structure-37132af2776b) initiated by guarantee rather than share capital are a popular choice as a DAO legal wrapper, obviating the need for shareholders or members, often in tax-advantaged jurisdictions. Limitations arise in VASP-related activities, fiduciary checks, and other areas that are best discussed with local counsel.

[Cooperatives](https://thedefiant.io/solving-the-riddle-of-the-dao-with-colorados-cooperative-laws/) are also gaining traction as legal wrappers for certain types of DAOs as distributions may be made by measure of DAO contributors' patronage, though registration and collection of member personal information for tax purposes is likely unavoidable for US-based cooperatives. 

Foreign non-grantor trusts, such as the [Guernsey Purpose Trust](https://dydx.foundation/blog/en/legal-framework-non-us-trusts-in-daos) structure, are seen as a favorable way to gate DAO member liability vectors and avoid US tax reporting or filing obligations where the trust is not funded on a transfer involving a US person, no US-sourced income is generated by the trust, and there are no US beneficiaries to the trust. The trustees are generally obligated to act in accordance with the purpose of the trust and their fiduciary duties, and are subject to the supervision of an enforcer.
