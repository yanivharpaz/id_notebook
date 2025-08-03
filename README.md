## Key Features

### Image Processing
- Automatically resizes large images to reduce API costs

### Israeli ID Validation
Specifically looks for Israeli ID characteristics like:
- Hebrew text `"תעודת זהות"`
- Israeli government emblem
- Blue and white color scheme
- Personal photo placement
- Hebrew/Arabic text
- 9-digit ID number format
- Security features

---

## Multiple Usage Options
- **Interactive main function**
- **Quick validation** function for single images
- **Batch processing** for multiple images

---

## Comprehensive Analysis
Returns detailed results including:
- Validity determination
- Confidence score
- Detected/missing features
- Reasoning explanation
- Quality warnings

---

## Setup Requirements

### Install dependencies
```bash
pip install openai pillow requests
