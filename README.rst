==========
remchecker
==========

What's this?
------------
手元で動くりむったーもどきな何か．
Twitterのfollowersのリムーブを確認します．


Requirements
------------
| python 2.5 or later
| tweepy
| pyyaml

How to Install?
---------------

.. easy_install
.. ++++++++++++
.. ::

..   $ easy_install remchecker


setuptools
++++++++++
::

  $ python setup.py install (run as admin/root)


run
++++++++++
::

  $ remcheckr

| 設定ファイルは~/.remcheckerに保存します．
| リムーブを発見した場合は自分にDMを送ります．
| 適当にcronで回して下さい．
|
|
| Author: seikichi
| License: MIT
| Mail: seikichi [at] kmc.gr.jp
