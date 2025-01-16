# Renovate config

This repository contains my personal [renovate](https://docs.renovatebot.com/) configuration used as base for my projects.

## Presets

- `default.json` - Default configuration for all projects
- `typo3-extension.json` - Configuration for TYPO3 extension projects

## Usage

```json
{
    "$schema": "https://docs.renovatebot.com/renovate-schema.json",
    "extends": [
        "github>jackd248/renovate-config"
    ]
}
```
