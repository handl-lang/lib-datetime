# lib-datetime

`datetime` — Handl stdlib port (pure handl).

## Layout

```text
src/                     the library (pure handl)
pkg.hnl                  package manifest
scripts/hnl-gate.sh      the gate
workflows/gate.yaml                    bupha entry (handl-gates)
```

## Gate

```bash
HNL=../host-cli/target/debug/hnl scripts/hnl-gate.sh
```

## License

MIT.
