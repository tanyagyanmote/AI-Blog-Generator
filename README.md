# AI Blog Generator

A simple Python script that generates blog posts using an AI model.  
You give it a topic, and it will create a blog post for you.

## Setup

1. **Clone the repo**
   ```bash
   git clone git@github.com:tanyagyanmote/AI-Blog-Generator.git
   cd AI-Blog-Generator
   ```

2. **Create a virtual environment**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install openai python-dotenv
   ```

4. **Set API Key**
   - Copy `.env.example` to `.env`
   - Add your key inside `.env`:
     ```
     OPENAI_API_KEY=sk-your-key-here
     ```

5. **Run**
   ```bash
   python blog_generator.py
   ```
