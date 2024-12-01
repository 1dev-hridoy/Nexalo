# Contributing to Nexalo

First off, thank you for considering contributing to Nexalo! It's people like you that make Nexalo such a great tool.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Getting Started](#getting-started)
   - [Issues](#issues)
   - [Pull Requests](#pull-requests)
3. [Coding Standards](#coding-standards)
4. [Setting Up the Development Environment](#setting-up-the-development-environment)
5. [Testing](#testing)
6. [Documentation](#documentation)
7. [Community](#community)

## Code of Conduct

This project and everyone participating in it is governed by the [Nexalo Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [dev.hridoy2002@gmail.com].

## Getting Started

### Issues

- Feel free to submit issues and enhancement requests.
- Before creating an issue, please check that a similar issue doesn't already exist.
- When you create a new issue, please provide as much detail as possible, including steps to reproduce if it's a bug.

### Pull Requests

1. Fork the repository and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Issue that pull request!

## Coding Standards

- Use ES6+ features
- Maintain consistent error handling
- Add comments for complex logic
- Follow the existing command structure
- Use meaningful variable and function names
- Keep functions small and focused
- Use async/await for asynchronous operations

## Setting Up the Development Environment

1. Clone the repository:
   ```
   git clone https://github.com/1dev-hridoy/Nexalo.git
   cd nexalo
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up your `.env` file with the necessary environment variables:
   ```
   BOT_TOKEN=YOUR_BOT_TOKEN
   OWNER_ID=OWNER_ID_HERE
   ADMIN_IDS=comma_separated_admin_ids
   MONGODB_URI=YOUR_MONGODB_URI
   ```

4. Start the bot in development mode:
   ```
   npm run dev
   ```

## Testing

- Write unit tests for new features or bug fixes.
- Run the existing test suite before submitting a pull request:
  ```
  npm test
  ```
- Aim for high test coverage for critical parts of the codebase.

## Documentation

- Update the README.md if you change functionality.
- Comment your code where necessary.
- If you add new commands, include them in the command documentation.

## Creating New Commands

1. Create a new file in the `commands` directory with the command name (e.g., `mycommand.js`).
2. Use the following template:

   ```javascript
   module.exports = {
     name: 'mycommand',
     adminOnly: false,
     ownerOnly: false,
     category: 'Category',
     description: 'Command description',
     guide: 'How to use the command',
     execute: async (bot, msg, args) => {
       // Command logic here
     }
   };
   ```

3. Implement the command logic in the `execute` function.
4. Test your command thoroughly.
5. Update the command documentation if necessary.

## Community

- You can join our [Telegram group](https://t.me/nexalo_community) for discussions about the development of Nexalo.
- For major changes, please open an issue first to discuss what you would like to change.

Remember, contributions to Nexalo should be a fun, enjoyable, and educational experience. If you're having trouble with your contribution, please reach out for help!

Thank you for contributing to Nexalo!
