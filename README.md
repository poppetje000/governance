se [nox](https://nox.thea.codes):

```bash
# Build the documentation
nox -s docs

# Or serve with live reload
nox -s docs-live
```

Alternatively, install MyST directly and build manually:

```bash
pip install -r requirements.txt
cd docs
myst build --html
```

The resulting website will be in `docs/_build/html`, which you can explore by opening
any of the `.html` files that are created.
