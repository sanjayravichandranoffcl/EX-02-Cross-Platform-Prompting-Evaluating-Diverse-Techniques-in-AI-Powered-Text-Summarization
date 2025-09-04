# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:


 

#  ChatGPT (GPT-4.5) 
## 1. Zero-Shot Prompting 
Prompt: "Summarize the following article." 
Summary: 
Blockchain is a decentralized digital ledger that records transactions across a 
network of computers. Each transaction is stored in a block, which is linked 
to the previous one, forming a chain. This structure ensures data integrity 
and security, as altering any block would require consensus from the entire 
network. Blockchain technology eliminates the need for intermediaries, 
enabling peer-to-peer transactions. It's widely used in cryptocurrencies like 
Bitcoin but also has applications in supply chain management, healthcare, 
and voting systems. The transparency and immutability of blockchain make it 
a promising tool for various industries seeking secure and efficient data 
management. 
## 2. Few-Shot Prompting 
Prompt: "Here are examples of summaries for technical articles. [Provide 
2–3 examples.] Now, summarize the following article." 
Summary: 
Blockchain functions as a decentralized ledger, recording transactions in 
linked blocks across a network. Each block contains a timestamp and a 
reference to the previous block, ensuring chronological integrity. This design 
prevents unauthorized alterations, as changes require consensus from the 
network. Blockchain's decentralized nature removes the need for central 
authorities, facilitating transparent and secure transactions. Beyond 
cryptocurrencies, it's applied in areas like supply chain tracking, healthcare 
records, and digital identity verification, offering enhanced security and 
efficiency. 
## 3. Chain-of-Thought Prompting 
Prompt: "Let's think step-by-step. First, explain how blockchain works, then 
summarize its key applications." 
Summary: 
Blockchain operates by storing data in blocks that are cryptographically 
linked, forming a chain. Each block contains transaction data, a timestamp, 
and a reference to the previous block, ensuring data integrity. This 
decentralized system requires consensus from network participants to 
validate new blocks, making it secure and tamper-resistant. Key applications 
of blockchain include facilitating cryptocurrencies like Bitcoin, enhancing 
supply chain transparency, securing healthcare records, and enabling smart 
contracts. Its ability to provide transparent, immutable records makes it 
valuable across various sectors. 
## 4. Role-Based Prompting 
Prompt: "You are a professional content curator for students. Summarize the 
article in simple terms." 
Summary: 
Imagine a digital notebook shared among many people, where each page 
(block) records transactions. Once a page is filled, it's linked to the previous 
one, forming a chain. This system, called blockchain, ensures that records 
can't be changed without everyone's agreement, making it secure. It's like a 
public ledger that anyone can verify but no one can alter alone. Blockchain is 
the backbone of cryptocurrencies like Bitcoin and is also used in tracking 
goods, securing medical records, and more. Its transparency and security 
make it useful in many fields. 

# � Gemini (Google) 
## 1. Zero-Shot Prompting 
Prompt: "Summarize the following article." 
Summary: 
Blockchain is a secure, decentralized ledger technology that records 
transactions across multiple computers. Each transaction is stored in a block, 
linked to the previous one, forming a chain. This structure ensures data 
integrity, as altering a block requires consensus from the network. 
Blockchain eliminates the need for intermediaries, enabling direct 
peer-to-peer transactions. It's widely known for powering cryptocurrencies 
like Bitcoin but also finds applications in supply chain management, 
healthcare, and voting systems due to its transparency and security features. 
## 2. Few-Shot Prompting 
Prompt: "Here are examples of summaries for technical articles. [Provide 
2–3 examples.] Now, summarize the following article." 
Summary: 
Blockchain functions as a decentralized ledger, recording transactions in a 
series of linked blocks across a network. Each block contains a timestamp 
and a reference to the previous block, ensuring chronological integrity and 
security. This system removes the need for central authorities, allowing 
transparent and tamper-resistant record-keeping. Beyond cryptocurrencies, 
blockchain is utilized in various sectors, including supply chain tracking, 
healthcare data management, and digital identity verification, offering 
enhanced efficiency and trust. 
## 3. Chain-of-Thought Prompting 
Prompt: "Let's think step-by-step. First, explain how blockchain works, then 
summarize its key applications." 
Summary: 
Blockchain operates by storing data in blocks that are cryptographically 
linked, forming an immutable chain. Each block contains transaction data, a 
timestamp, and a reference to the previous block. This decentralized system 
requires consensus from network participants to validate new blocks, 
ensuring security and transparency. Key applications of blockchain include 
powering cryptocurrencies like Bitcoin, enhancing supply chain transparency, 
securing healthcare records, and enabling smart contracts, making it a 
versatile technology across industries. 
## 4. Role-Based Prompting 
Prompt: "You are a professional content curator for students. Summarize the 
article in simple terms." 
Summary: 
Think of blockchain as a digital ledger shared among many people. Each 
entry, or block, records a transaction and is linked to the previous one, 
forming a chain. This setup ensures that once information is added, it can't 
be changed without everyone's agreement, making it secure and 
trustworthy. Blockchain is best known for supporting cryptocurrencies like 
Bitcoin but is also used in tracking products, managing medical records, and 
more, thanks to its transparency and reliability. 

#  Claude  
## 1. Zero-Shot Prompting 
Prompt: "Summarize the following article." 
Summary: 
Blockchain is a decentralized digital ledger that records transactions across a 
network of computers. Each transaction is stored in a block, which is linked 
to the previous one, forming a chain. This structure ensures data integrity 
and security, as altering any block would require consensus from the entire 
network. Blockchain technology eliminates the need for intermediaries, 
enabling peer-to-peer transactions. It's widely used in cryptocurrencies like 
Bitcoin but also has applications in supply chain management, healthcare, 
and voting systems. 
## 2. Few-Shot Prompting 
Prompt: "Here are examples of summaries for technical articles. [Provide 
2–3 examples.] Now, summarize the following article." 
Summary: 
Blockchain functions as a decentralized ledger, recording transactions in 
linked blocks across a network. Each block contains a timestamp and a 
reference to the previous block, ensuring chronological integrity. This design 
prevents unauthorized alterations, as changes require consensus from the 
network. Blockchain's decentralized nature removes the need for central 
authorities, facilitating transparent and secure transactions. Beyond 
cryptocurrencies, it's applied in areas like supply chain tracking, healthcare 
records, and digital identity verification. 
## 3. Chain-of-Thought Prompting 
Prompt: "Let's think step-by-step. First, explain how blockchain works, then 
summarize its key applications." 
Summary: 
Blockchain operates by storing data in blocks that are cryptographically 
linked, forming a chain. Each block contains transaction data, a timestamp, 
and a reference to the previous block, ensuring data integrity. This 
decentralized system requires consensus from network participants to 
validate new blocks, making it secure and tamper-resistant. Key applications 
of blockchain include facilitating cryptocurrencies like Bitcoin, enhancing 
supply chain transparency, securing healthcare records, and enabling smart 
contracts. 
## 4. Role-Based Prompting 
Prompt: "You are a professional content curator for students. Summarize the 
article in simple terms." 
Summary: 
Imagine a digital notebook shared among many people, where each page 
(block) records transactions. Once a page is filled, it's linked to the previous 
one, forming a chain. This system, called blockchain, ensures that records 
can't be changed without everyone's agreement, making it secure. It's like a 
public ledger that anyone can verify but no one can alter alone. Blockchain is 
the backbone of cryptocurrencies like Bitcoin and is also used in tracking 
goods, securing medical records, and more. 

# Copilot  
## 1. Zero-Shot Prompting 
Prompt: "Summarize the following article." 
Summary: 
Blockchain is a decentralized digital ledger that records transactions across a 
network of computers. Each transaction is stored in a block, which is linked 
to the previous one, forming a chain. This structure ensures data integrity 
and security, as altering any block would require consensus from the entire 
network. Blockchain technology eliminates the need for intermediaries, 
enabling peer-to-peer transactions. It's widely used in cryptocurrencies like 
Bitcoin but also has applications in supply chain management, healthcare, 
and voting systems. 
## 2. Few-Shot Prompting 
Prompt: "Here are examples of summaries for technical articles. [Provide 
2–3 examples.] Now, summarize the following article." 
Summary: 
Blockchain functions as a decentralized ledger, recording transactions in 
linked blocks across a network. Each block contains a timestamp and a 
reference to the previous block, ensuring chronological integrity. This design 
prevents unauthorized alterations, as changes require consensus from the 
network. Blockchain's decentralized nature removes the need for central 
authorities, facilitating transparent and secure transactions. Beyond 
cryptocurrencies, it's applied in areas like supply chain tracking, healthcare 
records, and digital identity verification. 
## 3. Chain-of-Thought Prompting 
Prompt: "Let's think step-by-step. First, explain how blockchain works, then 
summarize its key applications." 
Summary: 
Blockchain operates by storing data in blocks that are cryptographically 
linked, forming a chain. Each block contains transaction data, a timestamp, 
and a reference to the previous block, ensuring data integrity. This 
decentralized system requires consensus from network participants to 
validate new blocks, making it secure and tamper-resistant. Key applications 
of blockchain include facilitating cryptocurrencies like Bitcoin, enhancing 
supply chain transparency, securing healthcare records, and enabling smart 
contracts. 
## 4. Role-Based Prompting 
Prompt: "You are a professional content curator for students. Summarize the 
article in simple terms" 
summary: 
Think of blockchain as a special kind of digital notebook that’s shared among 
many people. Whenever something happens—like a transaction—it gets 
written on a new page (called a block). Each page connects to the one before 
it, making a long, unchangeable chain. This means no one can secretly 
change what’s written without everyone else knowing. Because it's shared 
and secure, blockchain is used for things like Bitcoin, tracking packages, 
managing medical records, and even voting. It helps keep information safe, 
transparent, and easy to check. 
Your goal is to determine which combination of prompting technique + 
platform provides the best summary in terms of: 

# ChatGPT (GPT-4.5) 
Accuracy: High 
Captures key concepts like decentralization, immutability, and applications 
beyond cryptocurrency. 
Coherence: Very High 
Well-structured and logically flows from explanation to examples; suitable 
for student comprehension. 
Simplicity: Excellent 
Uses relatable metaphors (e.g., digital notebook), making technical terms 
digestible for undergrads. 
Speed: Fast 
Returns a high-quality summary within seconds. 
User Experience: Excellent 
Interface is user-friendly, and output feels tailored and polished for the 
educational context. 

# Gemini (Google) 
Accuracy: High 
Covers fundamental aspects like block linking and security features; slight 
underemphasis on real-world use cases. 
Coherence: High 
Flows well but occasionally feels more generic than student-tailored. 
Simplicity: Good 
Clear language, though explanations may lack the creativity or analogies 
found in ChatGPT. 
Speed: Very Fast 
Delivers output nearly instantly. 
User Experience: Good 
Efficient but lacks customization depth; output may feel “template-like” at 
times. 

# Claude (Anthropic) 
Accuracy: High 
Includes all essential components: block structure, decentralization, 
real-world applications. 
Coherence: Very High 
Summary reads smoothly and logically connects ideas for a student 
audience. 
Simplicity: Excellent 
Uses analogies and clear language very effectively, second only to ChatGPT. 
Speed: Moderate to Fast 
Slightly slower than Gemini or ChatGPT but still prompt. 
User Experience: Very Good 
Friendly tone and human-like responses, though interface feels less refined 
than ChatGPT's. 

# Copilot (Microsoft) 
Accuracy: Moderate to High 
Hits basic points but can miss nuances or provide repetitive phrasing. 
Coherence: Moderate 
The structure is serviceable, but transitions can feel mechanical. 
Simplicity: Good 
Language is simple, but lacks depth or creative explanation. 
Speed: Fast 
Fast generation time, similar to ChatGPT. 
User Experience: Fair 
Integrated into developer tools, not ideal for educational use cases; lacks 
interactivity. 


# ALGORITHM (Methodology) 
Preparation: 
Select or write a 500-word article titled “The Basics of Blockchain 
Technology.” 
Standardize the text input across all platforms. 
Define Prompting Techniques 
Zero-Shot Prompting: “Summarize the following article.” 
Few-Shot Prompting: Provide 2–3 example summaries and then ask for a 
summary. 
Chain-of-Thought Prompting: Instruct the AI to think step-by-step before 
summarizing. 
Role-Based Prompting: Ask the AI to act as a "professional content curator 
for students" while summarizing. 
# Platforms Evaluated 
ChatGPT (GPT-4.5) 
Gemini (Google) 
Claude (Anthropic) 
Copilot (Microsoft) 
Execution 
Run all four prompting techniques on all four platforms 
Result for the execution: 
![Screenshot 2025-05-08 080701](https://github.com/user-attachments/assets/14c28828-2724-41f7-8e1f-30473073c79b)

![Screenshot 2025-05-08 080840](https://github.com/user-attachments/assets/9e4ad073-c239-401f-b70c-cf766378602b)


# RESULT: 
Thus 
Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Tex
 t-Summarization is executed successfully





