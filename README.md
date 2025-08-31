# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. 

### Task:
Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.
Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:Accuracy, Coherence, Simplicity, Speed, User experience.

## Algorithm

1.Select the article (The Basics of Blockchain Technology, ~500 words).

2.For each platform, run all four prompting techniques (Zero-Shot, Few-Shot, CoT, Role-Based).

3.Collect outputs (initial summaries + revised versions with feedback).

4.Evaluate summaries against criteria:Accuracy, Coherence, Simplicity, Speed, User Experience.

5.Compare results across platforms and techniques.

6.Identify best-performing combination (e.g., Role-Based on ChatGPT, or Few-Shot on Claude).

### Summary of The Basics of Blockchain Technology -ChatGPT:
Blockchain is a digital system that securely records and stores transactions across a network of computers. Unlike traditional databases controlled by a single authority, blockchain is decentralized, meaning everyone in the network shares the same copy of data. Transactions are grouped into “blocks,” which are linked together in a “chain,” making them transparent and very difficult to alter. This design ensures security, trust, and efficiency without needing middlemen. One of the most popular uses of blockchain is cryptocurrencies like Bitcoin and Ethereum, which allow safe peer-to-peer money transfers without banks. Another practical use is in supply chain management—companies such as Walmart use blockchain to trace food products from farm to store, improving safety and reducing fraud. Beyond finance and logistics, blockchain is also being explored in areas like digital voting, healthcare records, and smart contracts.

### Summary of The Basics of Blockchain Technology -Gemini:
Blockchain is a decentralized digital ledger that securely records transactions across a network of computers, rather than a single central authority. This ledger is made of "blocks" of data, which are linked together in a chronological "chain" using complex cryptography. Once a block is added, it is nearly impossible to alter, creating a transparent and immutable record.
This technology builds trust without the need for intermediaries. For example, in supply chain management, it can track goods from their source to the consumer, ensuring authenticity and preventing fraud. In healthcare, blockchain can provide a secure and tamper-proof way to manage and share patient medical records among providers, improving data integrity and privacy. It is the underlying technology for cryptocurrencies like Bitcoin, but its applications extend far beyond finance.

### Summary of The Basics of Blockchain Technology -Claude:
Blockchain is a shared, immutable digital ledger that enables transparent information sharing within a business network. Think of it as a digital notebook that multiple people can read but no one can erase or alter once something is written. In blockchain technology, each transaction is grouped into blocks, which are then linked together, forming a secure and transparent chain. Each block contains transaction details and is connected to the previous block through cryptographic hashes—unique digital fingerprints that make tampering nearly impossible. The blocks are grouped in an irreversible chain, with each new block reinforcing the security of the previous one. The key advantage is decentralization: instead of relying on a central authority like a bank, the network operates through consensus among participants. This structure guarantees data integrity and provides a tamper-proof record. Real-world applications include: Cryptocurrencies: Bitcoin uses blockchain as its foundation for peer-to-peer digital payments without banks Supply Chain Management: Companies track products from origin to consumer, ensuring authenticity and preventing fraud Blockchain's transparency, security, and elimination of intermediaries make it valuable across finance, healthcare, and logistics industries.

### Summary of The Basics of Blockchain Technology -Copilot:
Blockchain is a digital ledger system that records transactions across a network of computers, making data secure, transparent, and nearly impossible to alter. Instead of relying on a central authority, blockchain uses a decentralized structure where each block contains a record of transactions and links to the previous one—forming a secure chain. One popular application is cryptocurrency, like Bitcoin, which uses blockchain to verify and record peer-to-peer transactions without banks. Another real-world use is in supply chain management: companies like Walmart use blockchain to track food products from farm to shelf, improving safety and transparency. Beyond finance and logistics, blockchain is also being explored for voting systems, digital identity, and healthcare records, offering tamper-proof solutions. As industries seek more trust and efficiency, blockchain is becoming a key technology for the future.

## Comparison Table

<img width="1370" height="339" alt="image" src="https://github.com/user-attachments/assets/b93be9f7-8d52-4283-90b2-0e619013b6a3" />

## Key Insights

Accuracy: All four did well → no major mistakes.

Coherence: Claude > ChatGPT = Gemini > Copilot (Claude explains in depth, ChatGPT balances well).

Simplicity: Copilot > ChatGPT > Gemini > Claude (Claude is more technical).

Speed: All are fast; Claude and Copilot feel snappier in real use.

User Experience: ChatGPT and Copilot are strongest for everyday users; Claude is great for learners who want extra clarity.

## Final Verdict

Best Overall (Balance) → ChatGPT Zero-shot
(Accuracy + readability + practical examples = very strong).

Best for Technical Depth → Claude Zero-shot
(Great if the audience wants detailed technical explanation).

Best for Quick & Simple → Copilot Zero-shot
(Compact, easy-to-digest summaries for non-experts).

Best for Professional Tone → Gemini Zero-shot

## Conclusion:
Across platforms, Zero-shot prompting gave the best results, since each AI handled the blockchain basics confidently without extra examples. Among them, ChatGPT Zero-shot is the best overall for accuracy, coherence, simplicity, and user-friendliness, while Claude, Gemini, and Copilot each shine in specialized ways.

## Result
The experiment showed that zero-shot prompting gave the best results across all platforms. Among them, ChatGPT Zero-shot provided the most balanced summary in terms of accuracy, clarity, and user experience.


