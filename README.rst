.. -*- coding: utf-8; -*-

What is this
============

There are live templates for IntelliJ IDEA for Buster.JS based on buster-snippets.el_
Probably, it works on WebStorm / PhpStorm.

Not high functionality templates like buster-snippets.el_

Install
=======

If you enabled `IntelliJ Configuration Server Plugin`, it does not work very well.

1. Terminating your IntelliJ IDEA.
2. Put the BusterJS.xml to the below directory, depends on your system.
3. Start IntellJ IDEA.

Mac
---
  $HOME/Library/Preferences/IntelliJIdea12/templates

Linux
-----
  $HOME/.IntelliJIdea12/config/templates

Windows
-------
  %HOME%\\.IntelliJIdea12\\config\\templates

  if you not set HOME environment, it means `C:\\Users\\<USERNAME>`

Key assign
==========

The key are almost same as buster-snippets.el. But the key duplicated(e.g. `asin`, `tc`), so I changed to other key.

+--------+--------------------------------------+
| key    | name                                 |
+========+======================================+
|as      |assert                                |
+--------+--------------------------------------+
|asaco   |assert.alwaysCalledOn                 |
+--------+--------------------------------------+
|asacw   |assert.alwaysCalledWith               |
+--------+--------------------------------------+
|asacwe  |assert.alwaysCalledWithExactly        |
+--------+--------------------------------------+
|asat    |assert.alwaysThrew                    |
+--------+--------------------------------------+
|asc     |assert.called                         |
+--------+--------------------------------------+
|asc1    |assert.calledOnce                     |
+--------+--------------------------------------+
|asc1w   |assert.calledOnceWith                 |
+--------+--------------------------------------+
|asc2    |assert.calledTwice                    |
+--------+--------------------------------------+
|asc3    |assert.calledThrice                   |
+--------+--------------------------------------+
|ascc    |assert.CallCount                      |
+--------+--------------------------------------+
|ascn    |assert.className                      |
+--------+--------------------------------------+
|ascon   |assert.calledOn[**asco**]             |
+--------+--------------------------------------+
|ascor   |assert.callOrder[**asco**]            |
+--------+--------------------------------------+
|ascw    |assert.calledWith                     |
+--------+--------------------------------------+
|ascwe   |assert.calledWithExactly              |
+--------+--------------------------------------+
|asd     |assert.defined                        |
+--------+--------------------------------------+
|ase     |assert.equals                         |
+--------+--------------------------------------+
|asia    |assert.isArray                        |
+--------+--------------------------------------+
|asial   |assert.isArrayLike                    |
+--------+--------------------------------------+
|asib    |assert.isBoolean                      |
+--------+--------------------------------------+
|asid    |assert.inDelta                        |
+--------+--------------------------------------+
|asif    |assert.isFunction                     |
+--------+--------------------------------------+
|asinan  |assert.isNaN[**asin**]                |
+--------+--------------------------------------+
|asinull |assert.isNull[**asin**]               |
+--------+--------------------------------------+
|asinum  |assert.isNumber[**asin**]             |
+--------+--------------------------------------+
|asio    |assert.isObject                       |
+--------+--------------------------------------+
|asis    |assert.isString                       |
+--------+--------------------------------------+
|asm     |assert.match                          |
+--------+--------------------------------------+
|ass     |assert.same                           |
+--------+--------------------------------------+
|ast     |assert.threw                          |
+--------+--------------------------------------+
|astn    |assert.tagName                        |
+--------+--------------------------------------+
|asto    |assert.typeOf                         |
+--------+--------------------------------------+
|asx     |assert.exception                      |
+--------+--------------------------------------+
|cx      |buster.nestedContext                  |
+--------+--------------------------------------+
|re      |refute                                |
+--------+--------------------------------------+
|reaco   |refute.alwaysCalledOn                 |
+--------+--------------------------------------+
|reacw   |refute.alwaysCalledWith               |
+--------+--------------------------------------+
|reacwe  |refute.alwaysCalledWithExactly        |
+--------+--------------------------------------+
|reat    |refute.alwaysThrew                    |
+--------+--------------------------------------+
|rec     |refute.called                         |
+--------+--------------------------------------+
|rec1    |refute.calledOnce                     |
+--------+--------------------------------------+
|rec1w   |refute.calledOnceWith                 |
+--------+--------------------------------------+
|rec2    |refute.calledTwice                    |
+--------+--------------------------------------+
|rec3    |refute.calledThrice                   |
+--------+--------------------------------------+
|recc    |refute.CallCount                      |
+--------+--------------------------------------+
|recn    |refute.className                      |
+--------+--------------------------------------+
|recon   |refute.calledOn[**reco**]             |
+--------+--------------------------------------+
|recor   |refute.callOrder[**reco**]            |
+--------+--------------------------------------+
|recw    |refute.calledWith                     |
+--------+--------------------------------------+
|recwe   |refute.calledWithExactly              |
+--------+--------------------------------------+
|red     |refute.defined                        |
+--------+--------------------------------------+
|ree     |refute.equals                         |
+--------+--------------------------------------+
|reia    |refute.isArray                        |
+--------+--------------------------------------+
|reial   |refute.isArrayLike                    |
+--------+--------------------------------------+
|reib    |refute.isBoolean                      |
+--------+--------------------------------------+
|reid    |refute.inDelta                        |
+--------+--------------------------------------+
|reif    |refute.isFunction                     |
+--------+--------------------------------------+
|reinan  |refute.isNaN[**rein**]                |
+--------+--------------------------------------+
|reinull |refute.isNull[**rein**]               |
+--------+--------------------------------------+
|reinum  |refute.isNumber[**rein**]             |
+--------+--------------------------------------+
|reio    |refute.isObject                       |
+--------+--------------------------------------+
|reis    |refute.isString                       |
+--------+--------------------------------------+
|rem     |refute.match                          |
+--------+--------------------------------------+
|res     |refute.same                           |
+--------+--------------------------------------+
|ret     |refute.threw                          |
+--------+--------------------------------------+
|retn    |refute.tagName                        |
+--------+--------------------------------------+
|reto    |refute.typeOf                         |
+--------+--------------------------------------+
|rex     |refute.exception                      |
+--------+--------------------------------------+
|su      |buster.setUp                          |
+--------+--------------------------------------+
|tcb     |testCase.browser[**tc**]              |
+--------+--------------------------------------+
|tcm     |testCase.mixed[**tc**]                |
+--------+--------------------------------------+
|tcn     |testCase.node[**tc**]                 |
+--------+--------------------------------------+
|td      |buster.tearDown                       |
+--------+--------------------------------------+
|tt      |buster.test                           |
+--------+--------------------------------------+

License
=======

Copyright (C) 2013 Ryuichi Maeno

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.

.. _buster-snippets.el: https://github.com/magnars/buster-snippets.el
