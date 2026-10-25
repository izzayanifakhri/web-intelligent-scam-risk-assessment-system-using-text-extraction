# Requirements

## Functional Requirements

**FR_1 Submit Suspicious Text**

The system shall allow users to enter or paste a suspicious text message for analysis.

**FR_2 Submit Screenshots Images**

The system shall allow users to enter screenshot images of suspicious text message for analysis.

**FR_3 Validate User Input**

The system shall display a validation message when a user submits an empty message.

**FR_4 Extract Text from Images**

The system shall allow users to upload a supported image and extract readable text using Optical Character Recognition (OCR).

**FR_5 Handle Image Extraction Errors**

The system shall display an error message when an uploaded image contains no readable text.

**FR_6 Assess Scam Risk**

The system shall analyse submitted text using a machine learning model and rule-based indicators to assess its potential scam risk.

**FR_7 Display Assessment Results**

The system shall display the predicted risk category and relevant warning signs identified during the analysis.

**FR_8 Generate an Explanation**

The system shall use a Large Language Model (LLM) to generate an understandable explanation of the assessment results.

## Non-Functional Requirements

**NFR_1 Performance**

The system shall display text-analysis results within 5 seconds for messages containing up to 500 characters under the defined test environment.

**NFR_2 Usability**

The system shall display the message input field, submission control, and assessment results in a clearly labelled interface.

**NFR_3 Compatibility**

The system shall support the two latest stable versions of Google Chrome and Microsoft Edge at the time of testing.

**NFR_4 Reliability**

The system shall display an appropriate error message when text analysis or image extraction fails instead of terminating the user session.

**NFR_5 Privacy**

The system shall not retain submitted message content after the analysis session ends unless the user has been informed and has explicitly consented to storage.

**NFR_6 Detection Evaluation**

The system shall report precision, recall, and F1-score when evaluating the machine learning model on a labelled test dataset.
