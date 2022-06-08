# renovate config

## usage

- renovate.json

```json
{
  "extends": ["github>hayashikengo/renovate"]
}
```

- package.json

```json
{
  "name": "renovate-config-fastcore",
  "version": "0.0.1",
  ...
  "renovate-config": {
    "default": {
      "extends": ["github>hayashikengo/renovate"]
    }
  }
}
```
