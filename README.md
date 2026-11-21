# Automated Advertising Copy and Asset Generator

## Description
Marketing automation engine that generates headline variations, body copy, and value proposition frameworks tailored to specified target customer demographics.

## Live Demo
Access the live demonstration and portfolio showcase at: [https://sohail.devsil.com/projects.html](https://sohail.devsil.com/projects.html)

## Tech Stack
- Python 3.10+
- Generative AI APIs
- Streamlit
- Pillow

## Getting Started

### Prerequisites
- Python 3.10 or higher
- Git version control

### Installation and Setup
1. Clone the repository:
```bash
git clone https://github.com/sohailahmed-bsrh/ai-ads-maker.git
cd ai-ads-maker
```

2. Configure environment and dependencies:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env
streamlit run app.py
```

## Environment Variables

Configure the following environment variables in a `.env` file at the root directory:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

## Architecture and Project Structure
The repository is structured according to modular engineering standards:

```text
ai-ads-maker/
|-- src/
|-- data/
|-- .gitignore
|-- README.md
`-- requirements.txt
```

## Interface and Verification
The system produces verifiable execution logs, data summaries, or interactive interfaces depending on the execution target. Validate operation by running the test suite or local entrypoint.

## Author
Developed by Sohail Ahmed ([Portfolio](https://sohail.devsil.com) | [GitHub](https://github.com/sohailahmed-bsrh)).
