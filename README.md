Installing
==========

- Clone this to `devstack/themes/labster`: `git clone https://github.com/kriwil/labster-edx-theme.git labster`
- edit /edx/app/edxapp/edx-platform/lms.env.json (as `edxapp` user):

    - `"USE_CUSTOM_THEME": true`
    - `"THEME_NAME": "labster"`

- Re-run `paver devstack lms` (without `--fast` flag)

License
=======

The code in this repo is licensed under the Apache 2.0 License.
See [LICENSE.txt](LICENSE.txt) for more info.
