# Renovate Configurations

This repository holds shared Renovate configurations for all our projects. By centralizing these settings, we can ensure consistency and simplify the maintenance of our dependency update rules.

## Available Configurations

### Default Configuration

The default configuration is intended to be used by most projects.

## How to Use

To use these configurations in your project, extend the desired configuration(s) in your `renovate.json` file. For example:

```json
{
  "extends": [
    "github>GloryWong/renovate-config"
  ]
}
