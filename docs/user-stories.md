# User Stories

## User Story 1: Submit Suspicious Text

As a user, I want to submit a suspicious text message so that I can assess whether it may be a scam.

**Related Requirements:** FR1, FR2

### Acceptance Criteria

- Given that I enter a non-empty message, when I submit it, then the system analyses the message.
- Given that I submit an empty message, when I submit it, then the system displays a validation message.

## User Story 2: Extract Text from an Image

As a user, I want to upload an image containing a suspicious message so that the system can extract the text for analysis.

**Related Requirements:** FR3, FR4

### Acceptance Criteria

- Given that I upload a supported image containing readable text, when the image is processed, then the system extracts the text.
- Given that I upload an image containing no readable text, when the image is processed, then the system displays an appropriate error message.

## User Story 3: Assess and Understand Scam Risk

As a user, I want the system to assess the risk of a suspicious message and explain its warning signs so that I can make a more informed decision.

**Related Requirements:** FR5, FR6, FR7

### Acceptance Criteria

- Given that a message is submitted successfully, when the analysis is completed, then the system displays a predicted risk category and relevant warning signs.
- Given that the assessment results are available, when the explanation is generated, then the system displays an understandable explanation of the assessment.