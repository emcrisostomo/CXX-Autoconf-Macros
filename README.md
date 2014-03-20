README
======

This project contains a collection of C++ Autoconf macros offering the
following functionality:

  * Checks on the new features introduced by the C++11 standard in the
    `<functional>` header.

Available Macros
----------------

The following macros check for new features introduced by the C++11 standard
and defined in the `<functional>` header:

  * `AX_CXX_HAVE_BAD_FUNCTION_CALL()`: this macro checks for
    `std::bad_function_call`.
  * `AX_CXX_HAVE_BIND()`:  this macro checks for `std::bind`.
  * `AX_CXX_HAVE_BIT_AND()`: this macro checks for `std::bit_and`.
  * `AX_CXX_HAVE_BIT_OR()`: this macro checks for `std::bit_or`.
  * `AX_CXX_HAVE_BIT_XOR()`: this macro checks for `std::bit_xor`.
  * `AX_CXX_HAVE_CREF()`: this macro checks for `std::cref`.
  * `AX_CXX_HAVE_FUNCTION()`: this macro checks for `std::function`.
  * `AX_CXX_HAVE_HASH()`: this macro checks for `std::hash`.
  * `AX_CXX_HAVE_IS_BIND_EXPRESSION()`: this macro checks for 
    `std::is_bind_expression`.
  * `AX_CXX_HAVE_IS_PLACEHOLDER()`: this macro checks for `std::is_placeholder`.
  * `AX_CXX_HAVE_MEM_FN()`: this macro checks for `std::mem_fn`.
  * `AX_CXX_HAVE_PLACEHOLDERS()`: this macro checks for `std::placeholders`.
  * `AX_CXX_HAVE_REF()`: this macro checks for `std::ref`.
  * `AX_CXX_HAVE_REFERENCE_WRAPPER()`: this macro checks for
    `std::reference_wrapper`.

Installation
------------

This repository is a development repository which is *not* meant to be used by
GNU Autotools users.  Instead, users should get the latest release versions of
these macros from the [GNU Autoconf Archive][gar].

[gar]: http://www.gnu.org/software/autoconf-archive/

Bug Reports
-----------

Bug reports can be sent directly to the authors.

-----

Copyright (C) 2014 Enrico M. Crisostomo

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 3, or (at your option)
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
