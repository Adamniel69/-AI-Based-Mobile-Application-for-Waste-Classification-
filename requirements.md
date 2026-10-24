# System Requirements

## 1. Functional Requirements

| ID | Requirement |
|---|---|
| FR1 | The system shall allow users to capture or upload an image of a waste item. |
| FR2 | The system shall classify a submitted image into one of the supported waste categories using a CNN model. |
| FR3 | The system shall display the predicted waste category to the user. |
| FR4 | The system shall obtain the user's current location after permission is granted. |
| FR5 | The system shall display nearby recycling facilities based on the user's location and available facility data. |

## 2. Non-Functional Requirements

| ID | Type | Requirement |
|---|---|---|
| NFR1 | Performance | The system shall return a classification result within 3 seconds for at least 95% of supported test images under defined test conditions. |
| NFR2 | Usability | A first-time user shall be able to complete a waste classification task within 2 minutes during usability testing. |
| NFR3 | Security and Privacy | The system shall request user permission before accessing the device's current location. |

## 3. Scope of Requirements

### Included
- Waste image capture and upload
- CNN-based waste classification
- Display of classification results
- Location-based recycling facility search
- Display of available recycling facility information

### Excluded
- Physical waste collection
- Recycling facility operations management
- Online payments
- Real-time waste collection vehicle tracking

## 4. Notes

These requirements describe the proposed system. They have not yet been verified through implementation or testing.
