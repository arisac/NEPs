# Newton Evolution Proposals (NEPs)

[![Join the chat at https://gitter.im/newtonproject/NEPs](https://badges.gitter.im/newtonproject/NEPs.svg)](https://gitter.im/newtonproject/NEPs?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Newton Evolution Proposals (NEPs) describe Proposals for the Newton Project including _Economic Model_, _Personnel_, _Technical_, _Community Governance_ and _Business_.

We welcome anyone with suggestions related to Newton Project to compile a NEP.

This repository tracks the ongoing status of NEPs.

- [NEPs Official Website](https://nepdemo.newton.bio/) are build from NEPs and Docs from this repository.

- [All NEPs](https://nepdemo.newton.bio/neps/) of all NEPs merged in to this repository.

- [NEP Process](https://nepdemo.newton.bio/guides/nep-process/) that governs the NEPs repository.

## Contributing to NEPs

Newton Evolution Proposals (NEPs) repository exists as a place to share concrete proposals with potential users of the proposal and the Newton community at large.

Visit [NEP Guidelines](https://nepdemo.newton.bio/guides/) to learn how to contribute to NEPs.

Docs for Guides are located in `./guides` directory in this repository.

## Local Development

### Prerequisites

1. Open Terminal.

2. Check whether you have NodeJS and Yarn installed:

```bash
node --version && yarn --version
```

If you don't have NodeJS or Yarn installed, install them from [NodeJS Download](https://nodejs.org/en/download/) and [Yarn Installation](https://yarnpkg.com/getting-started/install).

3. Clone repository and update git submodules

```bash
git clone --recursive git@github.com:newtonproject/NEPs.git
```

Then go into your cloned git directory

```bash
cd NEPs
```

If not cloned with `--recursive`, update submodule to fetch the theme:

```bash
git submodule update --init --recursive
```

4. Install Dependencies:

```bash
yarn
```

### Start Website in Dev Mode

```bash
yarn dev
```

### Build Website Files

```bash
yarn build
```
