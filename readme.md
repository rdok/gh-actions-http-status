# HTTP Status

[![build-status](https://github.com/rdok/gh-actions-http-status/workflows/build-status/badge.svg)](https://github.com/rdok/gh-actions-http-status/actions?query=workflow%3Abuild-status)

This GitHub Action checks the HTTP status code for a given URL.

## Usage

```yml
    - name: Check http status code of production site
      uses: rdok/gh-actions-http-status@v1
      with:
        sites: '["http://github.com", "https://education.github.com"]'
        expected: '[301, 200]'
```

## Credits

[lakuapik/gh-actions-http-status](https://github.com/lakuapik/gh-actions-http-status) was used to quickly bootstrap this action.
