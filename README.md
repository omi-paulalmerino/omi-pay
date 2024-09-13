# Must Have Accounts

https://pypi.org/
https://test.pypi.org/

pip install --upgrade build

# Building package locally

python -m build

# Installing locally

pip install dist/py3-none-any.whl

# Uploading to Test PyPI

twine upload --repository-url https://test.pypi.org/legacy/ dist/smopay-0.1.0.tar.gz
