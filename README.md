PHPCodeAddress
==============

Cryptocoin address creator for: Bitcoin, Namecoin, Litecoin, and PPCoin.  Single file, static php object.

Version 0.1.0

Usage:
==============

require_once 'CoinAddress.php';
// CoinAddress::set_debug(true);      // optional - show debugging messages
// CoinAddress::set_reuse_keys(true); // optional - use same key for all addresses
$coin = CoinAddress::bitcoin();
print 'Bitcoin:  Public Address: ' . $coin['public'] . '  Private Address: ' . $coin['private'];


Notes:
==============
- modded from https://gist.github.com/scintill/3549107
- includes elliptic curve cryptography (ECC) libraries from https://github.com/mdanter/phpecc

License:
==============
Copyright (C) 2013 CoinAddress Developers

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES
OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

