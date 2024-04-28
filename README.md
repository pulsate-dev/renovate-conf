# pulsate-dev/renovate-conf

Renovate configuration for Pulsate projects

## Usage

> [!NOTE]
>
> This repository support only Node.js v20.0.0 and higher.
> If you are using older version of Node.js, please update it.
>
> ```sh
> mise install
> ```

1. Setup [renovate](https://github.com/apps/renovate) in repository
2. Add `renovate.json` file to repository `.github` directory

```json
{
    "extends": ["github>pulsate-dev/renovate-config"]
}
```

## Overwriting configuration

You can override the configuration by appending it directly to the `renovate.json` file in the repository root directory.

See renovate docs for more information on what you can do with Renovate.

[Configuration Options - Renovate Docs](https://docs.renovatebot.com/configuration-options/)
