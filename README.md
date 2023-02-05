
# install-pinned/reorder_python_imports
<!-- !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! -->
<!-- ⚠️auto-generated from init.py, do not edit manually ⚠️-->
<!-- !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! -->

![](https://shields.io/badge/python-%3E=3.7-blue)
![](https://shields.io/badge/runner%20os-Windows%20%7C%20Linux%20%7C%20macOS-blue)

Securely install the latest [reorder_python_imports](https://pypi.org/project/reorder_python_imports/) release from PyPI.

This action installs a pinned version of **reorder_python_imports** and all its dependencies,         making sure that file hashes match. Pinning your dependencies:

 1. Stops software supply chain attacks.
 2. Makes sure your CI does not break unexpectedly.

## Usage

In your GitHub Actions workflow, use this action like so:

```yaml
      - name: Install reorder_python_imports from PyPI
        uses: install-pinned/reorder_python_imports@2a40c379f1c9e5a3f87b441e488971c2d26b09b6  # 3.9.0
```

You can [set up Dependabot](https://docs.github.com/en/code-security/dependabot/working-with-dependabot/keeping-your-actions-up-to-date-with-dependabot#example-dependabotyml-file-for-github-actions)
so that your pins are updated regularly.

## Alternatives

This action is a relatively simple wrapper around [poetry](https://python-poetry.org/)         and is most useful if there is no existing `requirements.txt`/`poetry.lock`/... infrastructure in place.         If you already pin all your dependencies in a single place, you don't need it!

## More Details

See the [@install-pinned README](https://github.com/install-pinned) for details.
