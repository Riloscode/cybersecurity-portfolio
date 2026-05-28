# Microsoft Learn: Fundamentals of AI Security

## Overview

I completed the Microsoft Learn module **Fundamentals of AI Security**, which introduced key security concepts related to artificial intelligence systems, especially generative AI and large language models.

This module helped me understand how AI security differs from traditional cybersecurity due to the nondeterministic nature of generative AI, the expanded attack surface created by natural language interfaces, and the need for responsible AI practices.

## Key Concepts Learned

### AI Security vs. Traditional Cybersecurity

AI security expands beyond traditional cybersecurity because AI systems can respond unpredictably depending on prompts, context, training data, and user interaction.

Unlike traditional applications that follow more predictable logic, generative AI systems introduce new risks involving:

- Natural language manipulation
- Prompt-based attacks
- Model behavior abuse
- Data leakage through AI responses
- Overreliance on AI-generated output

## AI Architecture Security Layers

The module explained AI security across three major layers:

### 1. Usage Layer

This layer focuses on how users interact with AI tools.

Security concerns include:

- Unsafe prompts
- Sensitive data entered into AI tools
- User overreliance on AI responses
- Unauthorized AI tool usage, also known as shadow AI

### 2. Application Layer

This layer focuses on applications that use AI models or integrate AI capabilities.

Security concerns include:

- Prompt injection
- Insecure output handling
- Weak access controls
- Poor input validation
- Lack of logging and monitoring

### 3. Platform Layer

This layer focuses on the infrastructure, model hosting environment, identity controls, and cloud services supporting AI systems.

Security concerns include:

- Identity and access misconfiguration
- Model manipulation
- Data poisoning
- Weak monitoring
- Unauthorized access to AI resources

## AI-Specific Attack Categories

### 1. Jailbreaking

Jailbreaking refers to techniques used to bypass AI safety controls or guardrails.

Examples include:

- Direct instruction attacks
- Crescendo attacks
- Encoding tricks
- Attempts to make the model ignore safety rules

### 2. Prompt Injection

Prompt injection occurs when malicious instructions are inserted into a prompt, document, website, or other AI input to manipulate model behavior.

This can cause an AI system to:

- Ignore original instructions
- Reveal sensitive information
- Perform unauthorized actions
- Produce unsafe or misleading output

Prompt injection can be direct or indirect.

### 3. Model Manipulation

Model manipulation involves attempts to compromise the AI model or its behavior.

Examples include:

- Model poisoning
- Data poisoning
- Tampering with training data
- Influencing how the model responds

### 4. Data Exfiltration

Data exfiltration in AI systems involves unauthorized extraction of sensitive data.

This can include:

- Training data
- Prompt history
- Interaction data
- Model information
- Sensitive business or employee data

### 5. Overreliance

Overreliance is a human risk where users trust AI-generated responses without proper verification.

This can lead to:

- Poor decision-making
- Security mistakes
- Compliance issues
- Incorrect or unsafe business actions

## Frameworks Covered

The module introduced several important AI security frameworks and resources:

### OWASP Top 10 for LLM Applications

The OWASP Top 10 for Large Language Model Applications identifies major risks affecting LLM-based systems, including prompt injection, sensitive information disclosure, insecure output handling, and supply chain risks.

### MITRE ATLAS

MITRE ATLAS provides a knowledge base of adversary tactics and techniques targeting AI systems.

### NIST AI Risk Management Framework

The NIST AI RMF helps organizations govern, map, measure, and manage AI-related risks.

## Defensive Strategies Learned

AI security requires layered defenses. No single control fully protects an AI system.

Important mitigation strategies include:

- Least privilege access
- Strong identity and access management
- Input validation
- Output monitoring
- Data loss prevention
- Logging and auditing
- Human oversight
- Responsible AI governance
- AI usage policies
- Continuous monitoring
- Employee awareness training

## How This Applies to AI Security Analyst Work

This module is directly relevant to AI security analyst responsibilities such as:

- Reviewing AI tools before business use
- Identifying shadow AI risks
- Protecting sensitive data from AI misuse
- Monitoring AI usage
- Understanding prompt injection and jailbreak risks
- Supporting responsible AI adoption
- Helping build AI security policies
- Applying frameworks like OWASP, MITRE ATLAS, and NIST AI RMF

## Interview Takeaway

A key takeaway from this module is that AI security is not only about protecting models. It is about protecting the full AI ecosystem, including users, applications, data, identity, infrastructure, and business processes.

For organizations handling sensitive data such as HR records, payroll information, benefits data, Social Security numbers, or employee records, AI security must focus on:

- Data classification
- Access guardrails
- Monitoring
- Vendor review
- Prompt injection defense
- Sensitive data leakage prevention
- Responsible AI governance

## Skills Strengthened

- AI security fundamentals
- LLM risk awareness
- Prompt injection awareness
- AI attack surface understanding
- Responsible AI concepts
- Data protection awareness
- AI governance awareness
- Security framework awareness

## Completion

**Platform:** Microsoft Learn  
**Module:** Fundamentals of AI Security  
**Status:** Completed  
**XP Earned:** 100 XP  
