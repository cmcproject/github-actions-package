Create Python package and deploy it to Python Package Index

Deploy package:
- pip install setuptools wheel twine
- create setup.py, LICENSE, README.md
- python setup.py sdist bdist_wheel
 -twine upload dist/*
