# Bedrock-agent-websearch
web search tool functionality using Brave Search API 


# Notes: 

0) **Prerequisites**
- An AWS account. 
- An AWS Identity and Access Management (IAM) User with access to Amazon Bedrock.
- Amazon Bedrock Model Access to Claude 3.5 model

1) **Requirements:**
- First, install Python 3.12.
```bash
# For macOS (using Homebrew):
brew update
brew install python@3.12
```
- Install Python 3.12 and create a virtual environment
````bash
# For Unix-based systems (Linux, macOS)
python3.12 -m venv .venv
````
- Activate the virtual environment,
````bash
# For Unix-based systems (Linux, macOS)
source .venv/bin/activate
````
- Verify the Python version in your virtual environment,
````bash
python --version
#This should output "Python 3.12.x"
````
- Install dependencies,
```bash
pip3 install requests boto3 html2text streamlit
```

- You must have the AWS CLI configured. Use ``aws --version``. 





