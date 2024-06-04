zshenv (Linux ZSH Environment files)
----------------------------------------------

Linux ZSH environment configuration files.

Developed in the `Z shell <https://en.wikipedia.org/wiki/Z_shell>`_.

The README is used to introduce the tool and provide instructions on
how to install the tool, any machine dependencies it may have, and any
other information that should be provided before the tool is installed.

|GitHub issues| |Documentation Status| |GitHub contributors|

.. |GitHub issues| image:: https://img.shields.io/github/issues/vroncevic/zshenv.svg
   :target: https://github.com/vroncevic/zshenv/issues

.. |GitHub contributors| image:: https://img.shields.io/github/contributors/vroncevic/zshenv.svg
   :target: https://github.com/vroncevic/zshenv/graphs/contributors

.. |Documentation Status| image:: https://readthedocs.org/projects/zshenv/badge/?version=latest
   :target: https://zshenv.readthedocs.io/projects/zshenv/en/latest/?badge=latest

.. toctree::
    :hidden:

    self

Installation
-------------

|Debian Linux OS|

.. |Debian Linux OS| image:: https://raw.githubusercontent.com/vroncevic/zshenv/dev/docs/debtux.png
   :target: https://www.debian.org

Navigate to the release `page`_ download and extract the release archive.

.. _page: https://github.com/vroncevic/zshenv/releases

To install **zshenv**, type the following

.. code-block:: bash

   tar xvzf zshenv-x.y.z.tar.gz
   cd zshenv-x.y.z
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
   cp user_defined_disk_functions      /home/${USER}/.user_defined_disk_functions
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

Updated default locale

.. code-block:: bash

   Updated default locale

Modify the configuration to

.. code-block:: bash

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

Or you can use Docker to create an image or container.

Dependencies
-------------

**zshenv** requires the next modules and libraries

* None

Set of modules
----------------

**zshenv** is based on Z shell.

Configuration files

.. code-block:: bash

   user_defined_functions
   user_defined_str_functions
   user_defined_file_functions
   user_defined_hw_functions
   user_defined_net_functions
   user_defined_py_functions
   user_defined_perl_functions
   user_defined_java_functions
   user_defined_avr_functions
   user_defined_stm8_functions
   user_defined_web_functions
   user_defined_git_functions
   user_defined_disk_functions
   user_defined_doc_functions
   user_defined_rust_functions
   user_defined_yocto_functions
   zsh_aliases
   zshrc
   gitconfig
   gdbinit

Copyright and licence
----------------------

|License: GPL v3| |License: Apache 2.0|

.. |License: GPL v3| image:: https://img.shields.io/badge/License-GPLv3-blue.svg
   :target: https://www.gnu.org/licenses/gpl-3.0

.. |License: Apache 2.0| image:: https://img.shields.io/badge/License-Apache%202.0-blue.svg
   :target: https://opensource.org/licenses/Apache-2.0

Copyright (C) 2024 by `vroncevic.github.io/zshenv <https://vroncevic.github.io/zshenv>`_

**zshenv** is free software; you can redistribute it and/or modify it
under the same terms as Z shell itself, either Z shell version 5.9 or,
at your option, any later version of Z shell 5 you may have available.

Lets help and support FSF.

|Free Software Foundation|

.. |Free Software Foundation| image:: https://raw.githubusercontent.com/vroncevic/zshenv/dev/docs/fsf-logo_1.png
   :target: https://my.fsf.org/

|Donate|

.. |Donate| image:: https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif
   :target: https://my.fsf.org/donate/

Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
