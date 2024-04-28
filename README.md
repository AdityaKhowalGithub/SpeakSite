# HereSay

HereSay is an innovative Chrome extension designed to enhance web accessibility by providing auditory descriptions and interactive options for navigating web content.

## Getting Started

Follow these instructions to set up HereSay on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.x
- pip (Python package installer)
- Webdriver (version 124 or later)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/heresay.git
   cd heresay
   python -m venv venv
   
***
On Windows:
```bash
.\venv\Scripts\activate
```
On macOS and Linux:
```bash
source venv/bin/activate
```
***

Install all dependencies listed in the requirements.txt file.
```bash
pip install -r requirements.txt
```

Install LM Studio and Your Model of Choice
Follow the specific installation instructions provided by LM Studio to set up the model.
Start the Model Server
Launch the model server on port 1234.

Open the script where the driver.get line is located. Replace the URL with the website of your choosing.
```python
driver.get('http://example.com')
```
