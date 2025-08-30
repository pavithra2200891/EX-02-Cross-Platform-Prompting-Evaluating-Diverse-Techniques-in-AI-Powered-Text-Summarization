# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:

### Step 1:

Summarize the following 500-word article on “The Basics of Blockchain Technology” in 120–150 words for undergraduate students. Keep it clear and beginner-friendly.

Blockchain is a digital system that records transactions securely and transparently without needing a central authority like a bank. It is made of blocks of data linked in a chain, where each block contains information and is protected by cryptography. Once data is added, it cannot be altered, making blockchain highly secure and trustworthy. This decentralized network ensures all participants have the same copy of information, reducing fraud and errors. While it was first developed for Bitcoin, blockchain is now used in many fields. Its benefits include security, transparency, and efficiency, though challenges like high energy use and scalability remain. Overall, blockchain is a foundation for new digital innovations and helps people exchange information or value in a reliable way.


### Step 2 (Feedback):

Please revise the summary to make it even simpler and include at least two real-world examples of blockchain applications.

Blockchain is like a digital notebook shared by many people, where everyone can see the same information, but no one can secretly change it. It stores data in blocks connected in a chain, making it secure and transparent. This system removes the need for middlemen, like banks, and helps people trust each other online. For example, Bitcoin uses blockchain to transfer money safely without banks. Another example is supply chain tracking, where companies use blockchain to check if products like medicines or food are genuine. While blockchain is powerful, it still faces issues like high energy use and slow transactions. Still, it is an important technology shaping the future of finance, trade, and record-keeping.

### The Basics of Blockchain Technology

## ChatGPT:

Blockchain is a digital system that records and checks information in a secure and transparent way. Unlike traditional databases managed by one company, blockchain is decentralized, meaning data is stored across many computers. Information is grouped into “blocks,” and each block is connected to the previous one, forming a permanent “chain.” Once data is added, it cannot be easily changed, which makes the system reliable. Blockchain uses cryptography (secret codes) and consensus (agreement among computers) to confirm transactions.
<img width="309" height="163" alt="image" src="https://github.com/user-attachments/assets/15519156-967e-4253-a46f-1e53e96f2ddf" />


Transactions are validated using consensus mechanisms such as Proof of Work or Proof of Stake, ensuring accuracy without needing a central authority. Beyond finance, blockchain powers smart contracts, which are self-executing agreements that trigger automatically once conditions are met—for example, releasing payment once goods are delivered.

## Gemini:

Blockchain is like a digital notebook shared across thousands of people. Every time a new entry is made, it gets locked in with the old ones, forming a chain that’s very hard to break. Because no single person owns it, everyone can trust it.

<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/fb87aae9-9e82-44e9-9e55-251d31cee55c" />

Uses include:

Cryptocurrencies (e.g., Bitcoin, Ethereum): Digital money that doesn’t need banks.
Supply Chains: Verify whether products are original, organic, or ethically sourced.
NFTs (Non-Fungible Tokens): Blockchain also powers digital collectibles and art. image
Its uses are wide-ranging: cryptocurrencies such as Bitcoin and Ethereum allow people to send money directly without banks, supply chain tracking verifies whether products are authentic and ethically sourced, and NFTs (non-fungible tokens) enable digital ownership of art and collectibles. Blockchain also supports innovations like micropayments and borderless transfers, making it useful for everyday online transactions.

## Meta:

Blockchain is a distributed ledger where data is stored in linked blocks. Each block contains a hash of the previous one, making the chain tamper-resistant. Transactions are verified by a network of participants (nodes), which eliminates the need for trust in a single party.

<img width="318" height="159" alt="image" src="https://github.com/user-attachments/assets/8fe4be8f-81df-4c72-b747-221952f7963b" />

Examples:

Bitcoin & Ethereum: Digital currencies with global adoption.
Walmart’s Food Tracking: Helps find contaminated goods in seconds instead of days.
Banking: Cross-border payments processed in minutes rather than days. image Its applications extend beyond digital currencies. Walmart, for example, uses blockchain to trace food from farms to shelves, reducing the time needed to identify contaminated products from days to seconds. Banks use it for cross-border payments, cutting processing time from days to minutes. On top of that, advanced solutions like Layer-2 networks (e.g., Lightning Network) are emerging to make blockchain faster and more scalable.
## Claude:

Blockchain can be imagined as a chain of sealed boxes. Each box (block) stores transaction details, and once added, it cannot be altered, creating permanent trust in the data.
<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/df524496-17f4-42d8-807c-7e8d209a7a22" />

Benefits:

*Transparency: Public blockchains let anyone verify records. *Security: Strong encryption prevents hacking. *Decentralization: No single authority can manipulate the system.

Real-world use cases:

*Healthcare: Patients control access to their medical records. *Food Safety: Companies quickly trace contamination sources. *Education: Universities can issue tamper-proof digital certificates. image Real-world examples include healthcare systems that allow patients to control who accesses their records, universities issuing tamper-*proof digital certificates, and governments maintaining corruption-free land ownership records. Companies like Walmart also use it to trace food sources, helping identify contamination issues quickly.

## Cohere Command:

Blockchain is a decentralized digital ledger that links data blocks together in a secure chain. Every transaction is confirmed by the network, removing the need for middlemen such as banks or notaries. Its immutability makes it highly reliable for recording sensitive information.
<img width="311" height="162" alt="image" src="https://github.com/user-attachments/assets/ed52d593-4614-4f60-bdd6-a5dd62fbd203" />

Common applications include Bitcoin, which pioneered blockchain-based digital money, and supply chain management, where goods are tracked to ensure authenticity and prevent counterfeits. Some countries are even testing blockchain-based voting systems to enable transparent elections. At the same time, challenges remain: high energy consumption, scalability issues, and regulatory uncertainty. New approaches like Proof of Stake are addressing these concerns, making blockchain more sustainable for the future. image Cohere often brings a critical view—blockchain faces challenges like high energy consumption, scalability limits, and regulatory uncertainty. However, new eco-friendly methods (like Proof of Stake) are addressing these issues.

## Algorithm

Input a 500-word article on blockchain.

Apply different prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) to request summarization across AI platforms.

Collect the generated summaries.

Compare the clarity, accuracy, and beginner-friendliness of each summary.

Revise based on feedback to simplify further and add real-world examples.

Document results (Step 1 and Step 2 outputs).

## Result

● Step 1 produced a structured beginner-level summary of blockchain

● Step 2 improved accessibility by simplifying language and adding real-world examples (Bitcoin, supply chain).

● The experiment shows how prompt refinement (feedback/role-based prompting) enhances clarity and usefulness for undergraduates.

<img width="1024" height="454" alt="image" src="https://github.com/user-attachments/assets/7c2201de-bc40-4896-8dae-e484f2f08e8b" />



