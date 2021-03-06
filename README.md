# scoring_sheet_reader

Optical Mark Recognition (OMR) program to read the numerical scores entered in an assessment sheet

## Pre-requisites

* Python 3+
* Compatible OpenCV library

## Functionality

- [x] Reviews a defined region of a scanned scoring sheet for answer bubbles
- [x] Distinguishes between empty bubbles and filled-in bubbles
- [x] Prints the final/total score
- [x] Detects missing answers
- [x] Stores the responses as a key-value pair (dict)
- [x] Loop through pages of a PDF
- [ ] Creates a FHIR-JSON object
- [ ] Programmatically find scoring region 
- [ ] Configuration files for defining default settings for various assessment sheets
- [ ] Reads written narrative text
