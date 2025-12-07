# Contributing to Follow the White Rabbit

Thank you for your interest in contributing! We welcome contributions from the community.

## How to Contribute

### Reporting Bugs

1. Check if the bug has already been reported in Issues
2. If not, create a new issue with:
   - Clear title and description
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots if applicable
   - Environment details (browser, OS, etc.)

### Suggesting Features

1. Check existing feature requests in Issues
2. Create a new issue with the "enhancement" label
3. Describe the feature and its benefits
4. Provide examples or mockups if possible

### Code Contributions

1. **Fork the repository**
```bash
   # Click "Fork" on GitHub, then:
   git clone https://github.com/YOUR-USERNAME/follow-the-white-rabbit.git
   cd follow-the-white-rabbit
```

2. **Create a branch**
```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/bug-description
```

3. **Make your changes**
   - Follow existing code style
   - Add comments for complex logic
   - Update documentation if needed

4. **Test your changes**
```bash
   npm run dev
   # Test thoroughly in browser
```

5. **Commit your changes**
```bash
   git add .
   git commit -m "feat: add new feature description"
   # Use conventional commits: feat, fix, docs, style, refactor, test, chore
```

6. **Push to your fork**
```bash
   git push origin feature/your-feature-name
```

7. **Create a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your fork and branch
   - Fill out the PR template
   - Wait for review

## Code Style Guidelines

- Use meaningful variable names
- Keep functions small and focused
- Comment complex logic
- Use consistent formatting (2 space indentation)
- Follow the Matrix aesthetic for UI changes

## Commit Message Format
```
<type>: <short description>

<longer description if needed>

<footer with issue references>
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

Examples:
- `feat: add monthly summary email template`
- `fix: resolve email parsing issue for special characters`
- `docs: update README with deployment instructions`

## Development Setup

See the main [README.md](./README.md) for setup instructions.

## Questions?

Feel free to open an issue with the "question" label or email us at morpheus@followthewhiterabbit.com

Thank you for contributing! 🐇
