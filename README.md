# Purpose
Set of api tools around OpenAI codex models to explore new ways to write code. Experience with copilot shows that a few modifications to the model can make it more useful. For example programatic control of the previous context, multiple returns with short token lengths, and adjustable temperature.


# Setup
add your openai api key to `query.js` or create a .env file with 
```
export OPENAI_API_KEY=yourkeyhere
```

# Installation
```bash
npm install
```

# Test
```bash
npm test
```

# Contributing
pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

# Roadmap
- integrate into web based code editor
- work with functions instead of files