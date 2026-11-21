# py-experiments

Some basic examples to test [numpy](https://numpy.org/doc/stable/user/quickstart.html), [matplotlib](https://matplotlib.org/), [pytorch](https://pytorch.org/) and [IGN Geoplateforme](https://geoservices.ign.fr/) services.

## Examples

| Theme | Description |
|---|---|
| [fitting](fitting/README.md) | Estimate line and circle parameters from noisy points (least squares, gradient descent, autograd) |
| [neural-networks](neural-networks/README.md) | Basic neural networks with pytorch |
| [geometry](geometry/README.md) | Computational geometry algorithms (tangents, intersections) |
| [geoplateforme](geoplateforme/README.md) | Use IGN Geoplateforme services (WMS, ...) |
| [misc](misc/README.md) | Miscellaneous experiments (colormap, ...) |

## Usage

With [uv](https://github.com/astral-sh/uv#readme) :

```bash
# download dependencies
uv sync
# start jupyter notebook (should open browser)
uv run --with jupyter jupyter lab
```

## Adding an example

* Put it in the folder of its theme (or create a new theme folder with a `README.md`) and list it in the theme `README.md`.
* Use kebab-case file names. Use a numeric prefix (`01-`, `02-`, ...) only for progressive series.
* Store input data in `<theme>/data/` and write generated files to `<theme>/output/` (ignored by git).

## License

[MIT](LICENSE)
