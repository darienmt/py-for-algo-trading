# Python for Algorithmic Trading book playground

Here you can find the parts of the book [Python for Algorithmic Trading](https://www.amazon.ca/Python-Algorithmic-Trading-Cloud-Deployment/dp/149205335X) I tried. This book has a repo with most of the code but, I like to do it myself as well.

I put each chapter on its own directory to have independent from eachother, but the virtual environment will be at the root. Yes, instead of [Conda/Miniconda](https://docs.conda.io/en/latest/miniconda.html) I will use [virtualenv](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/).

## Environment setup
```bash
python3 -m venv venv
. ./venv/bin/activate
pip3 install -r requirements.txt
jupyter notebook

```

## Updating the requirement.txt
```bash
pip freeze > requierement.txt
```
