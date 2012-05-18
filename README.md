# python-quirc

Python ctypes interface for QR code decoding library [libquirc](https://github.com/dlbeer/quirc)

# Tests

[![Build Status](https://secure.travis-ci.org/svartalf/python-quirc.png)](http://travis-ci.org/svartalf/python-quirc)

Run tests with a `tox` command.

# Trobleshooting

If library raises an exception `OSError: libquirc.so.1: cannot open shared object file: No such file or directory`,
set environment variable LD_PRELOAD_PATH to `/usr/local/lib/` like this: `$ LD_PRELOAD_PATH=/usr/local/lib/ ./myscript.py`
