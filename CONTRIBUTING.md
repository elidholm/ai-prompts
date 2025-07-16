# Contributing to AI Prompt Skeletons

Thank you for your interest in contributing to this collection! This guide will help you understand how to contribute effectively.

## What I'm Looking For

I welcome contributions of:
- New prompt skeletons
- Improvements to existing prompts
- New categories or use cases
- Documentation improvements
- Bug fixes and typos

## Contribution Guidelines

### Prompt Requirements

All prompt skeletons must:
1. Use clear, specific placeholders in brackets like `[YOUR_CONTENT]`
2. Be well-tested and produce quality results

### RISEN Framework Template

```
**Role**: You are a [ROLE_DESCRIPTION] with expertise in [DOMAIN] and [SPECIFIC_SKILLS]

**Instruction**: [CLEAR_TASK_DESCRIPTION] that [SPECIFIC_OBJECTIVE]

**Steps**:
1. [STEP_1]
2. [STEP_2]
3. [STEP_3]
[Continue as needed...]

**End Goal**: [DESIRED_OUTCOME_DESCRIPTION]

**Narrowing**:
- [CONSTRAINT_1]: [OPTIONS/SPECIFICATIONS]
- [CONSTRAINT_2]: [OPTIONS/SPECIFICATIONS]
- [CONSTRAINT_N]: [OPTIONS/SPECIFICATIONS]
```

### File Structure

- Place prompts in appropriate category folders
- Use descriptive filenames with hyphens (e.g., `email-marketing.md`)
- Include a brief description at the top of each file
- Use consistent markdown formatting

## How to Contribute

### 1. Fork the Repository
Click the "Fork" button at the top right of the repository page.

### 2. Create a Branch
```bash
git checkout -b feat/your-contribution-name
```

### 3. Make Your Changes
- Add your prompt skeleton(s) to the appropriate category file
- Ensure proper formatting and, preferably, RISEN structure
- Test your prompts with AI tools to verify effectiveness

### 4. Commit Your Changes
```bash
git add .
git commit -m "Add [description of your contribution]"
```

### 5. Push to Your Fork
```bash
git push origin feature/your-contribution-name
```

### 6. Create a Pull Request
- Go to the original repository
- Click "New Pull Request"
- Select your fork and branch
- Add a clear description of your changes

## Pull Request Checklist

Before submitting, ensure:
- [ ] All placeholders are clearly marked with brackets
- [ ] Markdown formatting is consistent
- [ ] No typos or grammatical errors
- [ ] Prompts are tested and produce quality results

## Writing Style Guide

### Tone and Voice
- Professional but accessible
- Clear and concise
- Action-oriented
- Avoid jargon unless necessary

### Formatting
- Use **bold** for RISEN section headers
- Use `[BRACKETS]` for all placeholders
- Use bullet points for lists in narrowing sections
- Include code blocks for technical examples

### Placeholder Naming
- Use descriptive, ALL_CAPS names
- Separate words with underscores
- Include context when helpful
- Examples: `[TARGET_AUDIENCE]`, `[SPECIFIC_TECHNOLOGY]`, `[BUSINESS_OBJECTIVE]`

## Quality Standards

### Prompt Effectiveness
- Produces consistent, high-quality results
- Addresses common use cases in the category
- Provides clear guidance to AI agents
- Includes appropriate constraints and specifications

### Documentation Quality
- Clear, comprehensive descriptions
- Proper markdown formatting
- No spelling or grammatical errors
- Consistent with repository style

## Ideas for New Categories

I'm always looking for new categories. Consider:
- Legal and compliance
- Education and training
- Finance and accounting
- Design and creative
- Sales and business development

## Reporting Issues

If you find issues with existing prompts:
1. Check if the issue has already been reported
2. Create a new issue with:
   - Clear description of the problem
   - Steps to reproduce
   - Expected vs actual results
   - Suggested improvements

## Getting Help

If you need help:
- Check existing issues and discussions
- Create a new issue with the "question" label
- Be specific about what you need help with

## License

By contributing, you agree that your contributions will be licensed under the same Apache License 2.0 that covers the project.

## Recognition

All contributors will be acknowledged in the README. Thank you for helping make this resource better for everyone!

---

*Questions? Feel free to open an issue or start a discussion!*
