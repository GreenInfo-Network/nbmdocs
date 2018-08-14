National Biogeographic Map Documentation

This repo contains a standalone Sphinx docs package for documenting the National Biogeographic Map as a whole. To contribute, clone the repo, create a branch, build docs, commit, and issue a pull request with review requested from someone else in the team. Anyone on the team can merge a pull request, but please do get a second set of eyes on your contributions and be judicious in what you write. The documentation here is currently being auto-built to a couple of locations.

# Building Docs

Install Sphinx if you haven't already:

```
pip install Sphinx
```

Then just run the make:

```
cd docs/
make html
```

If you have an alternate Python or multiple versions of Python, you may specify with the `PYTHON=` flag:

```
cd docs/
make html PYTHON=python3.6
```

# Custom Styling

Additional styles beyond the default theme (`alabaster`) may be specified in `docs/_build/html/_static/custom.css`


