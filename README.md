# IT23722736_ITPM_assignment1

## Project Description
This project automates testing of the Chat Sinhala transliteration function at [PixelSuite Chat Translator](https://www.pixelssuite.com/chat-translator).  
Contains **50 negative test cases** where the system fails to convert Singlish to Sinhala correctly.

## Test Cases
| Total | Singlish Types | Expected Result |
|-------|----------------|-----------------|
| 50 | 24 | All FAIL |

## Prerequisites
- Python 3.12
- Google Chrome
- pip

## Installation

### 1. Install Packages
```bash
pip install playwright openpyxl
```
## Running the Tests

From the Command Prompt (inside `C:\IT23722736`), run the following command:

```bash
PS C:\IT23722736> python .\IT23722736\IT23722736.py --excel ".\IT23722736\IT23722736.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open  
