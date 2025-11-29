# Contributing to Awesome Nano Banana Prompts

Thank you for your interest in contributing to Awesome Nano Banana Prompts! This document provides guidelines for contributing prompts.

## How to Contribute

### Adding a New Prompt

1. **Fork the repository** and create a new branch for your contribution.

2. **Add your prompt** to `prompts.csv` with the following format:
   ```csv
   act,prompt,contributor,twitter
   "Act as [Role]","Your prompt text here","@yourgithub","@yourtwitter"
   ```

3. **Follow the prompt format:**
   - Start with "Act as [Role]" or similar engaging introduction
   - Be clear and specific about what the AI should do
   - Include examples when helpful
   - Keep prompts concise but complete

4. **Include attribution:**
   - Add your GitHub username in the `contributor` column
   - Add your Twitter/X handle in the `twitter` column (optional but encouraged)

5. **Submit a Pull Request** with a clear description of your prompt.

### Prompt Guidelines

- ✅ Prompts should be useful and practical
- ✅ Prompts should work well with Nano Banana and other LLMs
- ✅ Prompts should be original or properly attributed
- ✅ Prompts should be clear and well-formatted
- ❌ Avoid prompts that are offensive, harmful, or violate terms of service
- ❌ Avoid duplicate prompts

### CSV Format

The `prompts.csv` file uses the following columns:

- **act**: The title/role of the prompt (e.g., "Act as a Python Developer")
- **prompt**: The full prompt text
- **contributor**: GitHub username of the contributor (with @ prefix)
- **twitter**: Twitter/X handle of the contributor (with @ prefix, optional)

Example:
```csv
act,prompt,contributor,twitter
"Act as a Python Developer","I want you to act as a Python developer...","@username","@twitterhandle"
```

## Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Follow the project's guidelines

Thank you for contributing! 🎉

