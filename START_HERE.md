# Start here

This is a historical learning fork.

Do not start by trying to deploy a token.

## 1. Understand the source

Read:

```text
FORK_STATUS.md
README.md
LICENSE
```

## 2. Understand the code

Start with:

```text
contracts/
test/
```

The repository demonstrates minimalist EIP-20 token implementations and their tests.

## 3. Historical build commands

The upstream project documents:

```bash
npm install
npm run compile
npm run test
```

**Important:** the upstream README guaranteed Node 8. Modern Node versions may not work with these dependencies.

## Definition of done

For learning purposes, stop when you can explain:

- what the EIP-20 contract implements
- what the tests verify
- why this repository is historical
- which parts are upstream work
