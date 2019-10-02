# PyBites Platform Docs

This is the docs repo of [CodeChalleng.es](https://codechalleng.es/)

## Contribute

* Fork this repo: [https://github.com/pybites/platform-docs](https://github.com/pybites/platform-docs)

* Clone the fork, for example: `git clone git@github.com:bbelderbos/platform-docs.git platform-docs-bob`

* Create a virtual env and install the dependencies:

		cd platform-docs-bob
		python3.7 -m venv venv && source venv/bin/activate
		pip install -r requirements.txt

* Write documentation in `docs`, see [sphinx docs](http://www.sphinx-doc.org/en/master/) for reference and the `rst` files in `docs/` for examples.

* Check documentation locally (from root folder): `sphinx-build -b html docs docs/build`, check if it is what you want: `open docs/build/` / open `index.html`. 

* If so, commit your changes (`docs/build` output dir should be ignored, see `.gitignore`).

* Push your changes to your fork and open a PR against our repo to get it merged in.
