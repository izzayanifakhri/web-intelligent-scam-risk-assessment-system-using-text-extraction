# User Stories

# User Stories

## User Story 1: Submit Suspicious Text

As a user, I want to submit a suspicious text message
so that I can assess whether it may be a scam.

### Acceptance Criteria
- Given that I enter a text message, when I submit it,
  then the system analyses the message.
- Given that the input is empty, when I submit it,
  then the system displays a validation message.

## User Story 2: Extract Text from an Image

As a user, I want to upload an image containing a
suspicious message so that the system can extract
the text for analysis.

### Acceptance Criteria
- Given that I upload a supported image, when the
  image is processed, then the system extracts the text.
- Given that the image contains no readable text,
  then the system displays an appropriate error message.

## User Story 3: Assess Scam Risk

As a user, I want the system to assess the scam risk
of a message so that I can make a more informed decision.

### Acceptance Criteria
- Given that a message is submitted, the system
  classifies its scam risk using the implemented
  detection methods.
- Given that analysis is completed, the system
  displays the predicted risk category.

## User Story 4: Explain the Assessment

As a user, I want to understand why a message is
considered suspicious so that I can recognise
potential scam indicators.

### Acceptance Criteria
- Given that a message has been analysed, the 
  system displays relevant suspicious indicators.
- Given that a risk assessment is available, the 
  system generates a clear explanation of the assessment.