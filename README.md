# Unitex/GramLab 3.1beta Rev. 4225 [![Build Status][build-badge]][build-log]

[![Join the chat at https://gitter.im/UnitexGramLab/UnitexGramLab](https://badges.gitter.im/UnitexGramLab/UnitexGramLab.svg)](https://gitter.im/UnitexGramLab/UnitexGramLab?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
December 08, 2015

Unitex/GramLab is an open source, cross-platform, multilingual, lexicon-
and grammar-based corpus processing suite. Project home page can be found
from: <http://unitexgramlab.org>.

## Installation

This section covers compilation and installation of Unitex/GramLab on
Windows and Unix-like systems. For the latest downloads please visit
our [releases page](http://releases.unitexgramlab.org).

### Windows

Unitex/GramLab for Windows is distributed as a binary executable
installer. It can be downloaded from:

http://releases.unitexgramlab.org/latest-beta

The downloaded file will be named something similar to:

```
Unitex-GramLab-3.1beta_win32-setup.exe
Unitex-GramLab-3.1beta_win64-setup.exe
```

To begin the installation process, double-click on that file and follow
the instructions provided. Please note it is best to uninstall any
existing versions before continue.

Once the installation has been finished, you have nothing to do but
running the graphical interface by double-clicking on the file "Unitex"
(Unitex Classic IDE) or "GramLab" (Unitex Project-oriented IDE) located
under the "App" directory. If you prefer a manual install, check the
[source distribution package]() section.

The Windows setup installer accepts several optional command line
parameters. Some common options are:

+ `/AllUsers`                 : Sets default to a per-machine install
+ `/CurrentUser`              : Sets default to a per-user install
+ `/D C:\path\without quotes\`: Sets the default installation directory
+ `/NCRC`                     : Not perform a Cyclic Redundancy Check
+ `/S`                        : Runs the installer silently

### GNU/Linux

Unitex/GramLab for GNU/Linux is distributed as a binary executable
installer. It can be downloaded from:

http://releases.unitexgramlab.org/latest-beta

The downloaded file will be named something similar to:

```
Unitex-GramLab-3.1beta-linux-i686.run
Unitex-GramLab-3.1beta-linux-x86_64.run
```

Before begin the installation process, you will need to give it
executable permissions:

```
chmod a+x Unitex-GramLab-3.1beta-linux-i686.run
```

The .run file is a self-extracting archive. You can execute it at any
time with:

```
./Unitex-GramLab-3.1beta-linux-i686.run
```

The GNU/Linux setup installer accepts several optional command line
parameters. Some common options are:

+ `--confirm`     : Ask before running the embedded installation script
+ `--quiet`       : Do not print anything except error messages
+ `--noexec`      : Do not run the embedded installation script
+ `--target dir`  : Sets the default installation directory


### Source Distribution Package

Proceeding through the install process is straightforward. First,
acquire the source distribution package from:

http://releases.unitexgramlab.org/latest-beta

The downloaded file will be named something similar to:

```
Unitex-GramLab-3.1beta-source-distribution.zip
```

After this, extract the contents of the compressed file to a preferred
location. Then, go into the directory named `App/install` and type:

```
sh setup
```

This script check if you have Java installed, compile the C++ Core
sources, setup the Unitex and GramLab workspace directories and create
some desktop shortcuts. After finish installing, double click in
`App/Unitex` to open the Unitex IDE, or in `App/GramLab` to open the
GramLab IDE.

If you want to compile only the C++ Core sources. Extract the files
from the source distribution package, go into the directory named
`Src/C++/build` and type:

```
make install
```

## Documentation

User's Manual (in PDF format) is available in English and French (more
translations are welcome). You can view and print them with Evince,
downloadable [here](https://wiki.gnome.org/Apps/Evince/Downloads). The
latest on-line version of the User's Manual is accessible
[here](http://docs.unitexgramlab.org).

## Support

Support questions can be posted in the [community support
forum](http://forum.unitexgramlab.org). Please feel free to submit any
suggestions or requests for new features too. Some general advice about
asking technical support questions can be found
[here](http://www.catb.org/esr/faqs/smart-questions.html).

## Reporting Bugs

See the [Bug Reporting
Guide](http://unitexgramlab.org/index.php?page=6) for information on
how to report bugs.

## Governance Model

Unitex/GramLab project decision-making is based on a community
meritocratic process, anyone with an interest in can join the
community, contribute to the project design and participate in
decisions. The [Unitex/GramLab Governance
Model](http://governance.unitexgramlab.org) describes
how that participation takes place and how to set about earning merit
within the project community.

## Spelling

Unitex/GramLab is spelled with capitals "U" "G" and "L", and with
everything else lower case. Excepting the forward slash, do not put
a space or any character between words. Only when the forward slash
is not allowed, you could replace it with a hyphen "-", i.e.
"Unitex-GramLab".

It's common to refer to the Unitex/GramLab Core as "Unitex", and to the
Unitex Project-oriented IDE as "GramLab". If you are mentioning the
distribution suite (Core, IDE, Linguistic Resources and others bundled
tools) always use "Unitex/GramLab".

## License

* All Unitex/GramLab programs, libraries and source codes are
distributed under the terms of the [GNU Lesser General Public License
version 2.1][LGPLv2] (LGPLv2), which itself incorporates the terms and
conditions of the GNU General Public License.

* Linguistic Resources are distributed under the terms of the [Lesser
General Public License For Linguistic Resources][LGPLLR] (LGPLLR).

* Documentation is licensed under the terms of the [GNU Free
Documentation License version 1.3][GFDL] (GFDL), as published by the
Free Software Foundation.

* Unitex/GramLab includes copyrighted third-party libraries licensed
under the terms of the [Apache Software License version
2.0][Apache-2.0] (Apache-2.0), the [BSD 2-Clause License][BSD-2-Clause]
(BSD License), and the [MIT License][MIT] (MIT). All third-party
packages are copyright by their respective authors.

---
Copyright (c) Universite Paris-Est Marne-la-Vallee, 2001-2015

[Apache-2.0]:   http://opensource.org/licenses/Apache-2.0
[BSD-2-Clause]: http://opensource.org/licenses/BSD-2-Clause
[GFDL]:         http://www.gnu.org/licenses/fdl-1.3.txt
[MIT]:          http://opensource.org/licenses/MIT
[LGPLLR]:       http://spdx.org/licenses/LGPLLR.html
[LGPLv2]:       http://opensource.org/licenses/lgpl-2.1
[build-badge]:  http://unitex.univ-mlv.fr/v6/badge/commit/2015-12-08-14-20-05.svg
[build-log]:    http://unitex.univ-mlv.fr/v6/#bundle=commit&q=2015-12-08-14-20-05
