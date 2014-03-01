This is work-in-progress.

A basic syncronization utility for [vdir](https://github.com/untitaker/vdir).
Should be able to sync both CardDAV and CalDAV in the end.

## How to use

Copy `config.example` to `~/.vdirsyncer/config` and edit it. You can use the
`VDIRSYNCER_CONFIG` environment variable to change the path vdirsyncer will
read the config from.

Run `vdirsyncer --help`.

## How to run the tests

    pip install .
    pip install -r dev_requirements.txt
    py.test
