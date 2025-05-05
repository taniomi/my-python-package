# my-python-package
Testing uv for building distributions and publishing private python packages

## Steps to build a package with uv

1. Create git repository

```bash
gh repo create
```

2. Initialize the uv project for a [library](https://docs.astral.sh/uv/concepts/projects/init/#libraries)

```bash
uv init --lib
```

3. Add dependencies

```bash
uv add pandas
```

4. [Build](https://sarahglasmacher.com/how-to-build-python-package-uv/#step-0-choose-a-python-package-builderim-using-uv-here) the package from the root of your project

```bash
uv build
```