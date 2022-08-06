# ltc_scrypt

A wrapper for litecoin's scrypt variant into a Python3 module. This is used
by Dogecoin Core for all QA tests that generate or validate blocks.

### Goal of this module

This module aims to provide a portable and reliable scrypt implementation to be
used in testing and other use cases where performance is not a requirement. The
code in this library is therefore not optimized for performance.

### Contributing

Contributions that enhance the goal of this module are welcome, please see the
[Contribution guide](./CONTRIBUTING.md) for more information.

### Issues

If you experience any issues with this software, please file a bug report in
the [issues section](https://github.com/dogecoin/ltc-scrypt/issues/new)

### License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

Please refer to [the license file](./LICENSE) for more information.

The files `scrypt.c` and `scrypt.h` are published under a different license as
these have been copied from the Tarsnap online backup system. Please refer to
the respective file headers for more information.
