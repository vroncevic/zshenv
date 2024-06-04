# zsh_env (Linux ZSH Environment files)

<img align="right" src="https://raw.githubusercontent.com/vroncevic/zshenv/dev/docs/zshenv_logo.png" width="25%">

Linux ZSH environment configuration files.

Developed in the **[zsh](https://en.wikipedia.org/wiki/Z_shell)**.

The README is used to introduce the tool and provide instructions on
how to install the tool, any machine dependencies it may have, and any
other information that should be provided before the tool is installed.

[![GitHub issues open](https://img.shields.io/github/issues/vroncevic/zshenv.svg)](https://github.com/vroncevic/zshenv/issues) [![GitHub contributors](https://img.shields.io/github/contributors/vroncevic/zshenv.svg)](https://github.com/vroncevic/zshenv/graphs/contributors)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Installation](#installation)
- [Dependencies](#dependencies)
- [Docs](#docs)
- [Copyright and licence](#copyright-and-licence)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

### Installation

![Debian Linux OS](https://raw.githubusercontent.com/vroncevic/zshenv/dev/docs/ubuntux.png)

Navigate to the release **[page](https://github.com/vroncevic/zshenv/releases)** download and extract the release archive.

To install **zshenv**, type the following

```bash
# standard user
cp user_defined_functions           /home/${USER}/.user_defined_functions
cp user_defined_str_functions       /home/${USER}/.user_defined_str_functions
cp user_defined_file_functions      /home/${USER}/.user_defined_file_functions
cp user_defined_hw_functions        /home/${USER}/.user_defined_hw_functions
cp user_defined_net_functions       /home/${USER}/.user_defined_net_functions
cp user_defined_py_functions        /home/${USER}/.user_defined_py_functions
cp user_defined_perl_functions      /home/${USER}/.user_defined_perl_functions
cp user_defined_java_functions      /home/${USER}/.user_defined_java_functions
cp user_defined_avr_functions       /home/${USER}/.user_defined_avr_functions
cp user_defined_stm8_functions      /home/${USER}/.user_defined_stm8_functions
cp user_defined_web_functions       /home/${USER}/.user_defined_web_functions
cp user_defined_git_functions       /home/${USER}/.user_defined_git_functions
cp user_defined_doc_functions       /home/${USER}/.user_defined_doc_functions
cp user_defined_rust_functions      /home/${USER}/.user_defined_rust_functions
cp user_defined_yocto_functions     /home/${USER}/.user_defined_yocto_functions
cp zsh_aliases                      /home/${USER}/.zsh_aliases
cp zshrc                            /home/${USER}/.zshrc
cp gitconfig                        /home/${USER}/.gitconfig
cp gdbinit                          /home/${USER}/.gdbinit

# root user
cp user_defined_functions           /root/.user_defined_functions
cp user_defined_str_functions       /root/.user_defined_str_functions
cp user_defined_file_functions      /root/.user_defined_file_functions
cp user_defined_hw_functions        /root/.user_defined_hw_functions
cp user_defined_net_functions       /root/.user_defined_net_functions
cp user_defined_py_functions        /root/.user_defined_py_functions
cp user_defined_perl_functions      /root/.user_defined_perl_functions
cp user_defined_java_functions      /root/.user_defined_java_functions
cp user_defined_avr_functions       /root/.user_defined_avr_functions
cp user_defined_stm8_functions      /root/.user_defined_stm8_functions
cp user_defined_web_functions       /root/.user_defined_web_functions
cp user_defined_git_functions       /root/.user_defined_git_functions
cp user_defined_disk_functions      /root/.user_defined_disk_functions
cp user_defined_doc_functions       /root/.user_defined_doc_functions
cp user_defined_rust_functions      /root/.user_defined_rust_functions
cp user_defined_yocto_functions     /root/.user_defined_yocto_functions
cp zsh_aliases                      /root/.zsh_aliases
cp zshrc                            /root/.zshrc
cp gdbinit                          /root/.gdbinit
```

Updated default locale

```bash
vi /etc/default/locale
```

Modify the configuration to

```bash
LANG="en_US.UTF-8"
LANGUAGE="en_US:en"
LC_NUMERIC="en_US.UTF-8"
LC_TIME="en_US.UTF-8"
LC_MONETARY="en_US.UTF-8"
LC_PAPER="en_US.UTF-8"
LC_IDENTIFICATION="en_US.UTF-8"
LC_NAME="en_US.UTF-8"
LC_ADDRESS="en_US.UTF-8"
LC_TELEPHONE="en_US.UTF-8"
LC_MEASUREMENT="en_US.UTF-8"
```

Or you can use Docker to create an image or container.

### Dependencies

**zshenv** requires the next modules and libraries

    * None

### Docs

[![Documentation Status](https://readthedocs.org/projects/zshenv/badge/?version=latest)](https://zshenv.readthedocs.io/projects/zshenv/en/latest/?badge=latest)

More documentation and information at
* [https://zshenv.readthedocs.io/en/latest/](https://zshenv.readthedocs.io/en/latest/)
* [https://www.zsh.org/](https://www.zsh.org/)

### Copyright and licence

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Copyright (C) 2024 by [vroncevic.github.io/zshenv](https://vroncevic.github.io/zshenv)

**zshenv** is free software; you can redistribute it and/or modify
it under the same terms as Z shell itself, either Z shell version 5.9 or,
at your option, any later version of Z shell 5 you may have available.

Lets help and support FSF.

[![Free Software Foundation](https://raw.githubusercontent.com/vroncevic/zshenv/dev/docs/fsf-logo_1.png)](https://my.fsf.org/)

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://my.fsf.org/donate/)

