[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be)
[comment]: <> (useful, but WITHOUT ANY WARRANTY; without even the)
[comment]: <> (implied warranty of MERCHANTABILITY or FITNESS FOR)
[comment]: <> (A PARTICULAR PURPOSE. See the)
[comment]: <> (See the GNU Affero General Public License for)
[comment]: <> (more details.)

[comment]: <> (You should have received a copy of the GNU Affero)
[comment]: <> (General Public License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Android Lockscreen Utils (`android-lockscreen-utils`)

A collection of utilities to easily manage Android
lockscreen programmatically.

Of course the the utilities require administrative
permissions (root) to run on most Android devices.

These utilities is part of the DogeOS Android base.

The programs use the
[Crash Bash](
  https://github.com/themartiancompany/crash-bash)
library.

## Installation

The programs in this source repository
can be installed from source using GNU Make.

```bash
make \
  install
```

The utilities has been officially published
on the the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`android-lockscreen-utils`.
The source code is published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down.

To install it from there just type

```bash
ur \
  android-lockscreen-utils
```

A censorable HTTP Github mirror of the recipe published there,
containing a full list of the software dependencies needed to run the
tools is hosted on
[android-lockscreen-utils-ur](
  https://github.com/themartiancompany/android-lockscreen-utils-ur).

Be aware the mirror could go offline any time as Github and more
in general all HTTP resources are inherently unstable and censorable.

## Documentation

Help for the `lockscreen-lock` and
the `lockscreen-unlock` commands is
shown with the `-h` option.

## License

This program is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
