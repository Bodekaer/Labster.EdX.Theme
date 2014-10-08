Installing
==========

- Clone this to `devstack/themes/labster`: `git clone https://github.com/kriwil/stanford-edx-theme.git labster`
- Add these to your `lms/envs/private.py`:

```
PLATFORM_NAME = 'LabsterX'
THEME_NAME = 'labster'
FAVICON_PATH = "themes/{}/images/favicon.ico".format(THEME_NAME)
```

- Re-run `paver devstack lms` (without `--fast` flag)

License
=======

The code in this repo is licensed under the Apache 2.0 License.
See [LICENSE.txt](LICENSE.txt) for more info.
