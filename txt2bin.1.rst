..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025, 2026  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as
   published by the Free Software Foundation, either version 3 of the
   License, or (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public
   License along with this program.
   If not, see <https://www.gnu.org/licenses/>.


==============
txt2bin
==============

--------------------------------------------------------
Text To Binary
--------------------------------------------------------
:Version: txt2bin |version|
:Manual section: 1

Synopsis
========

txt2bin *[options]* *out_file* *[in_txt_files]*

Description
===========

Converts text to binary.

Options
========


-t argument_type        Possible values are 'file' and
                        'list'.
                        When it is 'file' the arguments
                        are the encoded file paths,
                        when it is 'list' the argument is
                        a file containing the paths of the
                        encoded files.
-f encoding_format      Encoding format ('base64').

-h                      Display help.
-c                      Enable color output
-v                      Enable verbose output


Bugs
====

https://github.com/themartiancompany/encoding-tools/-/issues

Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* bin2txt
* base64

.. include:: variables.rst
