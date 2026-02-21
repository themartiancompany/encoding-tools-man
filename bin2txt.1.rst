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
bin2txt
==============

--------------------------------------------------------
Binary To Text
--------------------------------------------------------
:Version: bin2txt |version|
:Manual section: 1

Synopsis
========

bin2txt *[options]* *in_file* *out_txt_prefix*

Description
===========

Converts binary to ascii text.

Options
========

-f encoding_format      Encoding format ('base64').
-B buffer_size          Size in bytes the input file will
                        be split before being read
   		        in memory and passed to
   		        the encoder.
-L string_length        String chunk length.
-s                      Only print chunks amount.

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

* base64
* txt2bin

.. include:: variables.rst
