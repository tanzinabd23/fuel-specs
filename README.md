# Fuel: A Secure Decentralized Generalized Massively Scalable Transaction Ledger

This repository specifies the Fuel protocol, including the Fuel Virtual Machine (FuelVM, FVM), a next-generation verifiable virtual machine for [the Fuel v2 blockchain](https://github.com/FuelLabs).

- [Specification](#specification)
  - [Protocol](#protocol)
  - [FuelVM](#fuelvm)
  - [Chain-Specific Configuration](#chain-specific-configuration)
    - [Ethereum](#ethereum)
- [Contributing](#contributing)

## Specification

### Protocol

1. [tx_format.md](./specs/protocol/tx_format.md): Fuel transaction format.
1. [identifiers.md](./specs/protocol/identifiers.md): How to compute unique IDs for transactions and UTXOs.
1. [tx_validity.md](./specs/protocol/tx_validity.md): Defines transaction validity rules.
1. [cryptographic_primitives](./specs/protocol/cryptographic_primitives.md): Cryptographic primitives used in Fuel.
1. [abi.md](./specs/protocol/abi.md): ABI specifications.

### FuelVM

1. [main.md](./specs/vm/main.md): Describes the FuelVM at a high level, from its architecture to how it is initialized.
1. [opcodes.md](./specs/vm/opcodes.md): Defines all opcodes available in the FuelVM.

### Chain-Specific Configuration

#### Ethereum

1. [compressed_tx_format.md](./specs/chains/ethereum/compressed_tx_format.md): Ethereum-compressed transaction format.

## Contributing

Markdown files must conform to [GitHub Flavored Markdown](https://github.github.com/gfm/). Markdown must be formatted with:

- [markdownlint](https://github.com/DavidAnson/markdownlint)
- [Markdown Table Prettifier](https://github.com/darkriszty/MarkdownTablePrettify-VSCodeExt)
