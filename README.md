# emplace
Command-line tool to mirror installed software on multiple machines.

[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Ftversteeg%2Femplace%2Fbadge&style=flat)](https://actions-badge.atrox.dev/tversteeg/emplace/goto)
[![](https://img.shields.io/crates/d/emplace.svg)](#downloads)
[![](https://img.shields.io/crates/v/emplace.svg)](https://crates.io/crates/emplace)
[![](https://img.shields.io/github/commits-since/tversteeg/emplace/latest.svg)]()

## Installation

### Getting Started

1. Install the *emplace* binary:

   #### Rust
   
   ```sh
   cargo install emplace
   ```

2. Add the init script to your shell's config file:

   #### Bash
   
   Add the following tot he end of `~/.bashrc`:
   
   ```sh
   # ~/.bashrc
   
   eval "$(emplace init bash)"
   ```
