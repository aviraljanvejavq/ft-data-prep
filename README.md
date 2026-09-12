# ft-data-prep

Clean and split JSONL datasets for fine-tuning

## Install

```bash
# stdlib only
```

## How to use

```bash
python prep.py raw.jsonl --out-dir data/ --valid-ratio 0.1
```

## Highlights

- Prints a stats summary you can eyeball
- Length filters keep the sweet spot
- Deterministic split with a seed
- Dedup by normalized instruction text

## Project structure

```text
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── prep.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m pytest -q
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas

## License

MIT licensed, see LICENSE.
