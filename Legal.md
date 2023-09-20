# Cryptolaw Resources and Repos

[the cod3x](https://www.thecod3x.com/) - cryptolaw treatise and reference aggregator

[LexDAO's Lex Corpus](https://github.com/lexDAO/LexCorpus/tree/master/contracts/legal) - contract library for legal engineering

[lex_node's Cryptolaw Emporium](https://github.com/lex-node/lex_node_cryptoLaw_emporium)

[Cryptolaw News Aggregator](https://news.octal.one/) by Octal

[Open Source Law Repo](https://github.com/ErichDylus/Open-Source-Law) - open source templates, forms, and other materials for DAOs, devs, and incentive programmers

[Blockchain 2023](https://practiceguides.chambers.com/practice-guides/blockchain-2023/) - DLx Law-edited guide to blockchain and cryptocurrency law and regulation in 22 jurisdictions

[Buzko DAO Legal Canon](https://www.buzko.legal/dao-legal-canon) - living list of publications and other content relating to legal aspects of DAOs

# Legal Contract Formation
Smart/Ricardian contracts and traditional, written contracts may be used together to provide an optimized level of security and efficiency in enforceability, while leaving flexibility for sensitive "meatspace" terms and mutual amendments in the parties' preferences. 

 •  if a participant is able to execute a smart contract through its construction, this could be deemed an offer; if the smart contract is executable only by a specific address, that smart contract could constitute an offer solely to that counterparty; 

 •  by signing a message with their private signature or directly calling a function in a smart contract, the counterparty may have provided acceptance; and 

 •  the element of consideration may be satisfied provided each party in the smart contract exchanges some form of value.

Depending on numerous factors, there may be elements of direct [legal contract formation in smart contracts](https://lexdao.substack.com/p/legal-contract-formation-in-smart) by the code's construction, intended interactions, etc. 


## "Code is Law" v. Code Deference 

Parties may want to eschew the Ricardian, unqualified ‘code is law’ approach in their contracting, and instead document the agreed level of deference to code's execution, perhaps adapting a form similar to the following: [Simple Code Deference Agreement](https://github.com/ErichDylus/SCoDA-Simple-Code-Deference-Agreement-). In this instance, parties are agreeing that, except in certain narrow express circumstances, they will defer to (or, refrain from legal dispute over) the results of the underlying smart contract's operation. Code deference has limitations, as examined in [this article](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3889630) by Drew Hinkes, who notes it may best be viewed as a mechanism to "rebalance incentives by increasing the opportunity costs for a decentralized venture participant to sue over a smart contract outcome and providing efficient alternatives to litigation."

# Relevant Laws and Regulations
It is imperative to consult local counsel for the jurisdiction or jurisdictions in which you and your products and services are based, conducting business, soliciting funds or usage, the governing law of any underlying agreements, and any other pertinent law - especially so if any type of token offering is contemplated, or for products or services which might be more heavily scrutinized by regulators (for example, a privacy tool, following the unprecedented [sanctioning](https://home.treasury.gov/news/press-releases/jy0916) of Tornado Cash smart contracts). Here's a non-exhaustive list of example laws, regulations, and other legal constructs to consider:

• The GDPR sets out data privacy and data protection rules under EU law, as outlined in the [GDPR Compliance Checklist](https://gdpr.eu/checklist/)

• The Uniform Commercial Code ("UCC"), Uniform Electronic Transactions Act ("UETA"), and Electronic Signatures in Global and National Commerce Act ( the "E-Sign Act") generally govern American digital commerce agreements, absent a treaty or federal preemption. 
   UCC Exclusions under E-Sign Act and UETA: all sections except 1-107 (Waiver of Renunciation of Claim or Right After Breach), 1-206, (Statute of Frauds for Kinds of Personal Property Not Otherwise Covered), Article 2 (Sales) and Article 2A (Leases)
   UCC Article 9 security agreements are excluded, but Article 9 already allows for "electronic records" and electronic "authentication." Article 3 negotiable instruments are excluded, but safe harbor rule allows for electronic "transferable records" that are unique and identifiable, with a single authoritative copy identifying controller.
   UCC has certain "possession" and "control" provisions that have so far been untested in the context of private keys and "ownable" smart contracts

The proposed draft UCC Article 12 sets out parameters for a new defined term, "controllable electronic record(s)" ("CER"), which intends to provide the legal rules governing the transfer—both outright and for security—of interests in some, but not all, electronic records (controllable electronic records - designed to encompass many types of digital assets). The Article 12 rules specify the rights in a CER that a purchaser would acquire, and would make CER negotiable, in the sense that a good faith purchaser for value would take a CER free of third-party claims of a property interest in the CER.

• Commodity Exchange Act and U.S. SEC and CFTC regulations may apply to digital currency transfers and purchases via smart contracts.

• The Bank Secrecy Act, the Patriot Act, and other Anti-Money Laundering and Money Transmission laws and regulations are imperative US laws to follow in remittance of cryptocurrencies and/or fiat currencies through public blockchain technologies and in determining KYC requirements. 

• Tax laws and regulations (International treaties, Federal, State, and local) must always be addressed in transfers of value. NFTs may present some novel tax quandaries, as noted [in this article by Jason Schwartz](https://www.friedfrank.com/siteFiles/Publications/Non-Fungible%20Tokens%20_%20Decentralized%20Law%20-%20BanklessDAO.pdf)

• Money transmission laws and regulations (International treaties, Federal, and State) apply to digital currency transfers.

• GDPR: extraterritoriality (the operation of laws outside the boundary of a state or country) may affect an international company that collects data on EU citizens - it is under the same legal obligation it would be if  headquartered in the EU, even without presence there. Generally, Cravath, Swaine & Moore LLP recommends "four guiding principles for entities hosting GDPR‑compliant blockchains: Use a private, permissioned blockchain; avoid, if possible, the storing of personal data on the blockchain; establish a detailed governance framework; and employ innovative solutions to data protection problems." While ongoing security and privacy implementations may invalidate some of these points, they should not be ignored.

Security Token Laws and Regulations
For any token issuance or transactions through smart contracts that may involved a security changing hands, it is crucial to seek legal advice regarding applicable securities laws and regulations (including but not limited to International, Federal and State jurisdictions) beforehand. 

Morrison Cohen's [Cryptocurrency Litigation Tracker](https://www.morrisoncohen.com/news-page?itemid=471) tracks SEC, CFTC, and criminal litigation; other public regulatory proceedings and summary orders; class action and private litigation; and major pronouncements by U.S. regulators about cryptocurrency. 

# Digital Signatures and Click-Wrap Transactions
Questions of a contract's enforceability or whether a contract has actually been executed typically fall within the purview of common law (where applicable) and thus are subject to numerous potential interpretations, especially in instances where jurisdiction is uncertain due to the distributed/decentralized nature of smart contracts.

A private key signature's enforceability considerations are in many respects analogous to a simple e-signature (such as a digitally signed PDF or merely an email with a designated name): did the signer actually execute, and did the signed have the intention to do so, the capability to do so, and the authority to do so?

## DAOs and Legal Entity Wrappers
Decentralized Autonomous Organizations ("[DAO](https://medium.com/@OpenLawOfficial/the-era-of-legally-compliant-daos-491edf88fed0)s") are decentralized, "headless" entities which rely on smart contracts to automate certain operations, governance, and behavior. This can reduce overhead, permit greater organizational transparency, and ease and automate capital apportionment. Some DAOs enable on-chain accession to off-chain guidelines or rules, such as constitutions or [charters](https://github.com/lex-node/SCoDA-Simple-Code-Deference-Agreement-/blob/master/DAO%20Charter%20with%20Qualified%20Code%20Deference.md) for DAOs wishing to function as unincorporated associations. DAOs often have a related "legal wrapper" meatspace entity in order to interact with traditional entities in meatspace contracts and generally approach certain types of liability.

Smart contracts and DAOs present several advantages and possibilities for built-in regulatory compliance, such as automated reporting of required data or tax payments at pre-determined intervals or encoded transfer restrictions.

US states' attempts to codify DAO-like entities (often slightly altered LLC implementations) have so far been rife with [issues](https://lexnode.substack.com/p/wyomings-legal-dao-saster).

[DAO Model Law](https://coala.global/reports/#1623963887316-6ce8de52-e0a0) - A proposed international uniform, model set of rules to provide legal certainty for DAOs and their members and participants by the Coalition of Automated Legal Applications (COALA), 2021

[Resources for DAOs and Creators](https://kinjal.mirror.xyz/eD3-Sgv2h50j-kwjHQCOnwqMKqSLTfnrqrtNypU-P5k) - Kinjal Shah

[LexDAO](https://github.com/lexDAO/LexCorpus/blob/master/contracts/legal/dao/membership/TUNAA.md) and [a16z](https://a16z.com/wp-content/uploads/2021/10/DAO-Legal-Framework-Jennings-Kerr10.19.21-Final.pdf) have penned materials on using Unincorporated Nonprofit Associations and hybrid structures as DAO legal wrappers, with a16z following up with a detailed [Part II](https://a16zcrypto.com/wp-content/uploads/2022/06/dao-legal-framework-part-2.pdf) on entity selection frameworks. [Paradigm](https://daos.paradigm.xyz/) has also created an entity wrapper comparison matrix comparing features and liability vectors. Both a16z's and Paradigm's analyses are from primarily American perspectives.

[Foundations](https://medium.com/@erich.dylus/api3-year-0-wrapped-dao-and-legal-structure-37132af2776b) initiated by guarantee rather than share capital are a popular choice as a DAO-adjacent legal entity, obviating the need for shareholders or members, often in tax-advantaged jurisdictions. Limitations arise in VASP-related activities, fiduciary checks, and other areas that are best discussed with local counsel.

[Cooperatives](https://thedefiant.io/solving-the-riddle-of-the-dao-with-colorados-cooperative-laws/) are also gaining traction as legal wrappers for certain types of DAOs as distributions may be made by measure of DAO contributors' patronage, though registration and collection of member personal information for tax purposes is likely unavoidable for US-based cooperatives. 

Foreign non-grantor trusts, such as the [Guernsey Purpose Trust](https://dydx.foundation/blog/en/legal-framework-non-us-trusts-in-daos) structure, are seen as a favorable way to gate DAO member liability vectors and avoid US tax reporting or filing obligations where the trust is not funded on a transfer involving a US person, no US-sourced income is generated by the trust, and there are no US beneficiaries to the trust. The trustees are generally obligated to act in accordance with the purpose of the trust and their fiduciary duties, and are subject to the supervision of an enforcer.
