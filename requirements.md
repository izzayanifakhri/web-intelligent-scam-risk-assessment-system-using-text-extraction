# Requirements

## Functional requirements 
1. The system shall allow users to enter or paste a suspicious text message for analysis.
2. The system shall analyze the submitted message using a machine learning model and rule-based indicators.
3. The system shall classify the message as potentially fraudulent or legitimate based on the analysis.
4. The system shall identify relevant warning signs such as urgent language, suspicious links or request for sensitive information to assess the potential scam risk of the submitted message.
5. The system shall display the classification result, risk assessment, identified warning signs, and generated explanation to the user.
6. The system shall use a Large Language Model (LLM) to generate understandable explanations of why a message is considered potentially fraudulent or legitimate.
7. The system shall notify users when the submitted message is empty or cannot be analysed successfully.

## Non-functional requirements 
1. The system shall rocess a submitted text message and display the analysis results within a reasonable response time.
2. The system shall provide a simple and user-friendly interface that allows users to submit messages and understand the results easily.
3. The system shall handle valid message inputs consistently and display appropriate error messages when analysis fails.
4. The system shall protect submitted messages and prevent unauthorised access to user data.
5. The system shall be evaluated using appropriate classification metrics such as precision, recall and F1-score to assess its scam detection performance.
6. The system shall be designed with modular components to facilitate updates to the machine learning model, rule-based indicators and LLM integration.
7. The system shall be accessible through commonly used web browsers such as Google Chrome and Microsoft Edge.
