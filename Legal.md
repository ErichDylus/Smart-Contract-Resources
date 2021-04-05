# Cryptolaw Resources and Repos

[LexDAO's Lex Corpus](https://github.com/lexDAO/LexCorpus) - contract library for legal engineering

[lex_node's Cryptolaw Emporium](https://github.com/lex-node/lex_node_cryptoLaw_emporium)

[Startup Starter Pack](https://github.com/ErichDylus/Startup-Starter-Pack) - model legal documents for typical startup setup and fundraising needs

[Choose a License](https://choosealicense.com/) for open source works

# Smart Contracts v. Traditional Contracts
Smart/Ricardian contracts and traditional, written contracts may be used in tandem to provide an optimized level of security and efficiency in enforceability, while leaving flexibility for sensitive "meatspace" terms and mutual amendments in the parties' preferences. 

 •  if a participant is able to execute a smart contract through its construction, this could be deemed an offer; if the smart contract is sent to a counterparty directly, that smart contract likely constitutes an offer solely to that counterparty; 

 •  by signing their private signature to the smart contract, the counterparty has effectively given acceptance to the agreement; and 

 •  the element of consideration may be satisfied provided each party in the smart contract exchanges some form of value.

The imperative departure from traditional contracts is that smart contracts are agreements in digital form that are self-executing and self-enforcing to the extent encoded; importantly, Traditional legal enforcement of rights and obligations of the underpinning agreements may be still available except to the extent expressly waived (subject to applicable law). Including a provision allowing for liquidated damages or mutual amendment in the case of unintended software vulnerabilities or failures either in your principal agreement or in your audit contract may be advisable to the extent possible. 


## "Code is Law" v. Code Deference 

Parties may want to eschew the Ricardian, unqualified ‘code is law’ approach in their contracting, and instead document the agreed level of deference to code's execution, perhaps adapting a form similar to the following: [Simple Code Deference Agreement](https://github.com/ErichDylus/SCoDA-Simple-Code-Deference-Agreement-)

In this instance, parties are agreeing that, except in certain narrow express circumstances, they will defer to (or, refrain from legal dispute over) the results of the underlying smart contract's operation.

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

•  New York’s Department of Financial Services established a stringent licensing rule (the “BitLicense”) for virtual currency-based businesses. 

• Tax laws and regulations (International treaties, Federal, State, and local) must always be addressed in transfers of value.

• Money transmission laws and regulations (International treaties, Federal, and State) apply to digital currency transfers.

• GDPR: extraterritoriality (the operation of laws outside the boundary of a state or country) may affect an international company that collects data on EU citizens - it is under the same legal obligation it would be if  headquartered in the EU, even without presence there. Generally, Cravath, Swaine & Moore LLP recommends "four guiding principles for entities hosting GDPR‑compliant blockchains: Use a private, permissioned blockchain; avoid, if possible, the storing of personal data on the blockchain; establish a detailed governance framework; and employ innovative solutions to data protection problems." While ongoing security and privacy implementations may invalidate some of these points, they should not be ignored.

The UK Jurisdiction Task Force has released a [statement](https://35z8e83m1ih83drye280o9d1-wpengine.netdna-ssl.com/wp-content/uploads/2019/11/6.6056_JO_Cryptocurrencies_Statement_FINAL_WEB_111119-1.pdf) on the legal treatment of cryptoassets and smart contracts, more clearly defining the UK position on enforceability and classifications. 

The statement confirms that under English law:

cryptoassets are capable of being owned; and
smart contracts can be, or be part of, binding legal contracts.
Linklaters notes that the legal statement provides that the asset is "not any of the public or private keys, or the distributed ledger data itself. None of those constitute property but rather they are mere information. Instead, the asset is something that arises from their combination with the relevant system rules (including the embedded cryptography): the exclusive ability to update or spend transaction data." Further, the statement acknowledges that security over a cryptoasset may be accomplished by way of charge or mortgage, but not pledge or lien.


Consensys provides a myriad of webinars covering specific sector information as well, including niche commercial and legal considerations.

Security Token Laws and Regulations
For any token issuance or transactions through smart contracts that may involved a security changing hands, it is crucial to seek legal advice regarding applicable securities laws and regulations (including but not limited to International, Federal and State jurisdictions) beforehand. Examples of American regulations include:

 - Reg D (Private Placement Exemption): "accredited investors" only, as defined by the SEC

 - Reg A (Limited Amount Exemption)  non-accredited investors for maximum $50 million 

 - Reg S (International Exemption)


To launch a Security Token Offering ("STO") in the EU, companies generally have to submit a prospectus and comply with local security laws, except when qualified by certain exceptions, such as:

 - Qualified investors’ exemption (private placement): solicit "qualified investors" only for the STO, as defined by EU regulations.

 - Large investments exemption: companies may sell their securities freely if every investor buys at least a statutory minimum amount each.

 - Limited network exemption: Companies may issue security tokens to up to a certain number of individual people or entities per EU member state without submitting a prospectus.

 - Limited amount exemption: companies may sell securities valued up to a certain threshold amount over a one year period without submitting a prospectus.  Individual EU Member States may exempt domestic offers where the total amount offered in the EU is between a certain range of amounts. 

- Growth Prospectus:  starting July 21, 2019, SMEs (companies with a market cap of up to €43 million, turnover of up to €5 million or fewer than 250 employees) and mid-sized companies admitted to an SME Growth Market may use a simplified document when offering securities to the public, provided that their securities are not traded on a regulated market.


When an EU Prospectus is submitted, the PR requires that summaries set out the 15 most material risk factors specific to the issuer, and the guarantor (if applicable). Possible risk factors for STOs and smart contract-related entities may include errors in code, protocol forks, crypto market volatility, technological obsolescence, and security. It is important to note that civil liability could arise in respect of a summary that is misleading, inaccurate or missing material information when read along with the rest of the prospectus.


The Monetary Authority of Singapore issues a Guide to Digital Token Offerings that requires a submitted prospectus, absent one of the outlined exemptions, including a private placement up to a certain threshold number of individuals within a one year period.

Morrison Cohen has relaunched their [Cryptocurrency Litigation Tracker](https://www.morrisoncohen.com/news-page?itemid=471), which tracks SEC, CFTC, and criminal litigation; other public regulatory proceedings and summary orders; class action and private litigation; and major pronouncements by U.S. regulators about cryptocurrency. 

# Digital Signatures and Click-Wrap Transactions
Courts have already looked upon digital signatures and click-wrap agreements with overwhelming favor, and smart contracts in their simplest form are likely to be viewed as a natural extension. Some examples of favorable statutory precedent are UETA and the E-Sign Act. Questions of a contract's enforceability or whether a contract has actually been executed typically fall within the purview of common law (where applicable) and thus are subject to numerous potential interpretations, especially in instances where jurisdiction is uncertain due to the distributed/decentralized nature of smart contracts.

The USA's 21st Century IDEA Act presents a new legal framework to improve digital interactions with the federal government. It establishes deadlines for federal government agencies to provide mobile-accessible and updated versions of their websites, digital forms and services, and electronic signatures.  Given the forward-thinking contributors at the widely-used digital signature enabler DocuSign, it is possible the outcomes of this new legislation will be leveraged into smart contract implementations.

Digital signatures utilizing DLT or in a blockchain context do not yet have meaningful judicial precedent. However, a signature under public key encryption is likely to follow the same evaluations as a simple e-signature (such as a digitally signed PDF or merely an email with a designated name): did the signer actually execute, and did the signed have the intention to do so, the capability to do so, and the authority to do so?

## Arbitration, Dispute Resolution, and Litigation
Smart contracts, or traditional contracts leveraging smart contract technology for certain terms or conditions therein, may integrate any traditional jurisdictional or dispute settlement clauses. However, Blockchain-based arbitration, as currently being tested and developed by OpenLaw, may present some interesting legal intricacies when the points to be arbitrated are non-binary or non-discrete, or in the instance of mistaken award. This is a process whose development we are closely monitoring.

JAMS, a member of the Accord Project, is the first institutional ADR provider to create supportive protocols for disputes arising from blockchain smart contracts. Draft JAMS rules and clauses are being vetted by industry experts and potential users, and are available for review and comment upon request to JAMS.  


## DAOs and Regulatory Compliance
Decentralized Autonomous Organizations ("[DAO](https://medium.com/@OpenLawOfficial/the-era-of-legally-compliant-daos-491edf88fed0)s") are decentralized, "headless" entities which rely on smart contracts to automate certain operations, governance, and behavior. This reduces overhead, permits greater organizational transparency, and tightens internal controls. DAOs effectively decentralize identifying aspects of traditional entities such as jurisdiction of organization, principal place of business, and raise novel concerns in liability apportionment-- as such, regulatory compliance of DAOs, especially in the U.S., is tricky. LexDAO is a legal engineer club building web3.0 legal assets and code, such as escrow and dispute resolution, powered by Ethereum transactional scripts via an Aragon DAO. ZeroLaw LLC is undertaking to refine a model [DAO charter](https://github.com/lex-node/SCoDA-Simple-Code-Deference-Agreement-/blob/master/DAO%20Charter%20with%20Qualified%20Code%20Deference.md) for DAOs wishing to function as unincorporated associations. 

The [LAO](https://medium.com/openlawofficial/the-lao-a-for-profit-limited-liability-autonomous-organization-9eae89c9669c), envisioning a more broadly applicable Limited Liability Autonomous Organization, seeks to lessen "meatspace" (or human, non-decentralized actor/input/output) liability through the use of Ricardian Contracts in apportioning capital. The LAO and OpenLaw are continually developing and progressing the [taxonomy](https://medium.com/@thelaoofficial/a-taxonomy-for-laos-making-sense-of-the-emerging-lao-ecosystem-1122b035fe1a) and risks of such structures, setting forth autonomous entity formation options such as the Decentralized Automated Corporation (DAC), Limited Liability Autonomous Company (LLAC), and the Limited Autonomous Cooperative (LAOP).

Smart contracts and DAOs present several advantages and possibilities for built-in regulatory compliance, as noted by the U.S. Commodities Futures Trading Commission's LabCFTC: smart contract collateral or proceeds cannot be sold to a non-Eligible Contract Participant (without clear digital forensic evidence on the blockchain), the contract may be coded so the transaction may not occur until the mandated period has passed, and it may incorporate automated reporting of required data or tax payments at pre-determined intervals.
