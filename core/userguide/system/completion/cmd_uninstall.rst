..  Copyright (c) 2014-present PlatformIO <contact@platformio.org>
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
       http://www.apache.org/licenses/LICENSE-2.0
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

.. _cmd_misc_completion_uninstall:

platformio system completion uninstall
======================================

.. contents::

Usage
-----

.. code-block:: bash

    platformio system completion uninstall [OPTIONS]
    pio system completion uninstall [OPTIONS]


Description
-----------

Uninstall shell completion files or code.

Options
~~~~~~~

.. program:: platformio system completion uninstall

.. option::
    --shell

The shell type, default is ``auto`` and will be detected from a current shell session.

Supported shells are:

* `fish <https://fishshell.com/>`__
* `zsh <http://www.zsh.org/>`__
* `bash <https://www.gnu.org/software/bash>`__
* `powershell <https://msdn.microsoft.com/en-us/powershell/mt173057.aspx>`__

.. option::
    --path

Custom installation path of the code to be evaluated by the shell.
The standard installation path is used by default.

Examples
--------

.. code::

    > pio system completion uninstall

    PlatformIO CLI completion has been uninstalled for fish shell from ~/.config/fish/completions/pio.fish
    Please restart a current shell session.
