# CERTIFY Documentation [![Documentation Status](https://readthedocs.org/projects/certify/badge/?version=latest)](https://certify.readthedocs.io/en/latest/?badge=latest)
CERTIFY uses [Read the Docs](https://readthedocs.org/) for software documentation. It facilitates automatic building, versioning, and hosting of the documentation. The [Sphinx](https://www.sphinx-doc.org/en/master/) tool is used to build the documentation using the [theme](https://github.com/readthedocs/sphinx_rtd_theme).
The documentation is generated for each commit in the master branch. Therefore, it is advised to build locally for update, preview and design. The [section](#update-documentation) describe the procedure. You could find the latest version of [documentation](https://certify.readthedocs.io/en/latest/index.html) online.

## Update Documentation
### Setup
1. Download and install latest version of Python from [here](https://www.python.org/downloads/)
2. Clone the repo

   `git clone https://github.com/ccertify-project/certify-docs.git`
3. Install dependencies

   ```
   cd certify-docs/docs
   pip3 install -r requirements.txt
   ```
### Build
Make your changes and run following commands to generate html documentation.

```
cd Framework/docs
make html
```
### Preview
Open `build/html/index.html` file in a browser.
### Upload
When all the changes are according to your needs then push changes or make pull request. 


