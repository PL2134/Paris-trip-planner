# Paris Trip Planner AI ✨🗼
Welcome to **Paris Trip Planner AI** — an interactive assistant that uses **OpenAI's GPT model** to help users explore Paris with AI-generated travel guidance. Designed for seamless Q&A, this tool responds to curated tourist prompts with clarity and charm.

---

## Table of Contents
1. [Overview](#overview)
2. [Key Features](#key-features)
3. [Setup & Installation](#setup--installation)
4. [Environment Variables](#environment-variables)
5. [How It Works](#how-it-works)
6. [Contributing](#contributing)
7. [License](#license)

---

## Overview

### Why this project?
Whether you're a first-time traveler or a curious explorer, this project offers a **natural language interface to plan your Paris adventure**. It simulates an AI tour guide capable of answering common questions about landmarks, history, and local insights — making it an engaging, educational tool.

This notebook-based project is ideal for:
- Students learning OpenAI API interaction
- Travel tech demos
- Language and tourism educators
- Hackathon prototypes

---

## Key Features

1. **Conversational Tour Guide AI**  
   - Ask travel questions in natural language  
   - Receive context-rich and friendly responses

2. **Customizable Prompt Templates**  
   - Personalize the assistant's role and tone  
   - Easily extendable to other cities or topics

3. **Jupyter Notebook Format**  
   - Interactive and beginner-friendly  
   - Great for showcasing AI project workflows

4. **Secure API Integration**  
   - Uses `.env` files to manage secret keys securely

---

## Setup & Installation

### Prerequisites
- **Python 3.8+**
- A virtual environment (recommended)
- OpenAI API access

### Clone and Install
```bash
git clone https://github.com/your-repo/paris-trip-planner.git
cd paris-trip-planner

# Create and activate virtual env
python3 -m venv paris
source paris/bin/activate

# Install required packages
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file in the root directory:

```env
OPENAI=your_openai_api_key_here
```

The notebook uses `python-dotenv` to load this key and pass it to the OpenAI client securely.

---

## How It Works

### Initialization
The assistant is initialized with a system prompt that defines its personality as a helpful Parisian tour guide.

### User Input & Chat Completion
Users provide questions (e.g., *"What should I see in Montmartre?"*) and the OpenAI API responds using `gpt-3.5-turbo`.

### Session Memory (Future Scope)
The project is structured to later include session memory, personalization, or prompt chaining for longer itineraries.

---

## Contributing

We welcome improvements and creative extensions!  
- **Add more questions or city support**  
- **Suggest new use cases**  
- Fork, branch, and PR your enhancements!

---

## License

This project is shared under the [MIT License](LICENSE).  
Use it, remix it, and build on it freely.

---

**Bon voyage and happy coding!** 🌍
