      _ _ _              
     | (_) |__  _ __   __ ___  __
     | | | '_ \| '_ \ / _` \ \/ /
     | | | |_) | | | | (_| |>  < 
     |_|_|_.__/|_| |_|\__, /_/\_\
                      |___/


libngx - a general c library builded from Nginx core codes.


Build and Install
=====

    git clone git://github.com/guiquanz/libngx.git
    cd libngx
    ./configure --prefix=/usr/local
    make && make install


Test
=====

    cd examples
    make test LIBNGX_BASE_DIR=/usr/local 


Status
======

This library is *not* usable yet and still under early development.


Author
======

GuiQuan "guiquanz" Zhang (张桂权) <guiqzhang@gmail.com>


Copyright and License
=====================

This module is licensed under the BSD license.

Copyright (c) 2012 by GuiQuan "guiquanz" Zhang (张桂权) <guiqzhang@gmail.com>

Copyright (C) 2002-2012 Igor Sysoev

Copyright (C) 2011,2012 Nginx, Inc.

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


