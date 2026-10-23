# Problem Statement

## 1. Who Is Affected?

The problem affects members of the public who receive suspicious digital messages, including potential victims of phishing, banking scams and fraudulent job offers. Users with limited cybersecurity awareness may find it difficult to distinguish legitimate messages from fraudulent ones.

## 2. What Is the Problem?

Scammers may use urgent language, impersonation, suspicious links and requests for sensitive information to persuade recipients to take harmful actions. Users may struggle to identify these warning signs, particularly when messages appear convincing or imitate trusted organisations.

## 3. Why Does It Matter?

The scale of scam-related crime demonstrates the importance of improving public awareness and prevention. Bernama (2025), citing the Royal Malaysia Police, reported that 35,368 scam cases were recorded in Malaysia in 2024, involving RM1.6 billion in financial losses. Although these figures cover scams broadly rather than text-message scams alone, they demonstrate the potential impact of fraudulent activities.

## 4. Problem Statement

The increasing prevalence of scams creates challenges for users who need to distinguish suspicious messages from legitimate communications. Users may lack the knowledge or confidence to recognise warning signs, while a classification result alone may not adequately explain why a message is considered suspicious. Therefore, this project proposes an intelligent scam risk assessment system that accepts suspicious text directly or extracts text from uploaded images. It will combine machine learning and rule-based indicators to assess potential scam risk, while a Large Language Model (LLM) will generate understandable explanations of the assessment. The system aims to help users recognise potential warning signs and make more informed decisions; it is intended as a decision-support tool rather than a guarantee that a message is safe.

## 5. Stakeholders

- **General users:** Submit suspicious messages and review risk assessments.
- **Potential scam victims:** Use the assessment and explanations to better understand possible warning signs.
- **System developer:** Develop, test and maintain the system and its detection components.

## 6. Project Scope

### In Scope

- Accepting suspicious text entered or pasted by users.
- Uploading supported images and extracting readable text using Optical Character Recognition (OCR).
- Analysing extracted or submitted text using machine learning and rule-based indicators.
- Displaying a predicted risk category and relevant warning signs.
- Generating explanations using an LLM.
- Evaluating the machine learning model using appropriate classification metrics.

### Out of Scope

- Automatically blocking messages or links on users' devices.
- Accessing users' SMS inboxes, banking applications or private accounts.
- Guaranteeing that every scam message will be detected.
- Reporting scams to law enforcement or contacting banks automatically.
- Analysing audio calls, videos or entire websites.
- Supporting every language; language support will be limited to the languages selected for the project.

## Reference

Bernama. (2025, March 3). *Over 35,000 scams, RM1.6 billion losses recorded last year – Bukit Aman*. https://bernama.com/en/news.php?id=2398423
