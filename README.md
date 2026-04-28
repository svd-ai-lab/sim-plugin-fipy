# sim-plugin-fipy

Fipy driver for [sim-cli](https://github.com/svd-ai-lab/sim-cli),
distributed as an out-of-tree plugin.

FiPy driver for sim.

## Install

```bash
sim plugin install fipy
```

Other paths:

```bash
pip install git+https://github.com/svd-ai-lab/sim-plugin-fipy@v0.1.0
pip install https://github.com/svd-ai-lab/sim-plugin-fipy/releases/download/v0.1.0/sim_plugin_fipy-0.1.0-py3-none-any.whl
pip install -e .
```

After install:

```bash
sim plugin doctor fipy
sim plugin sync-skills
```

## Development

```bash
git clone https://github.com/svd-ai-lab/sim-plugin-fipy
cd sim-plugin-fipy
uv sync
uv run pytest
```

## License

Apache-2.0.
