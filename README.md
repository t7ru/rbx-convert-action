# rbx-convert-action

Convert Roblox place/model files between XML and binary formats using [`rbx-util`](https://github.com/rojo-rbx/rbx-dom/tree/master/rbx_util).

`.rbxlx` <-> `.rbxl` · `.rbxmx` <-> `.rbxm`

## Usage

```yaml
- uses: t7ru/rbx-convert-action@v0.2.0
  with:
    input: path/to/place.rbxlx
    output: path/to/place.rbxl
```

## Inputs

| Input | Required | Default | Description |
|---|---|---|---|
| `input` | ✅ | - | Input file path, relative to workspace root |
| `output` | ✅ | - | Output file path, relative to workspace root |
| `verbosity` | ❌ | `""` | Verbosity flags (`-v` or `-vv`) |
| `rbx-dom-rev` | ❌ | `2bac02a` | rbx-dom commit SHA used to select the prebuilt rbx-util binary |

## License

[MIT](LICENSE)

Upstream `rbx-util` copyright 2018-2025 The Rojo Developers
