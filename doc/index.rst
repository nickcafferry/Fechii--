`Fechii-Gas Chromatography Mass Spectrometry <https://github.com/nickcafferry/Fechii-Application-Chemical-Engineer/tree/master>`_
===============

|Documentation Status| |Licence| |Chinaperfumer| |Firmenich| |Givaudan| |DSM| |Zeno| |Gitter|

.. |Licence| image:: https://img.shields.io/badge/license-MIT-blue.svg?style=flat
   :target: https://github.com/nickcafferry/Fechii-Application-Chemical-Engineer/blob/master/LICENSE
   
.. |Documentation Status| image:: https://readthedocs.org/projects/fechii-application-chemical-engineer/badge/?version=latest
   :target: https://fechii-application-chemical-engineer.readthedocs.io/en/latest/?badge=latest

.. |Chinaperfumer| image:: https://img.shields.io/badge/link-Chinaperfumer-brightgreen.svg?style=flat
   :target: http://www.zoteq.com/
   
.. |Firmenich| image:: https://img.shields.io/badge/link-firmenich-blue.svg?style=flat
   :target: https://www.firmenich.com/
   
.. |Givaudan| image:: https://img.shields.io/badge/link-givaudan-yellow.svg?style=flat
   :target: http://www.givaudan.cn/givaudan-china

.. |Gitter| image:: https://badges.gitter.im/GC-MS-for-Perfumer/community.svg
   :target: https://gitter.im/GC-MS-for-Perfumer/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge

.. |DSM| image:: https://img.shields.io/badge/link-DSM-brightgreen.svg?style=flat
   :target: https://www.dsm.com/corporate/home.html

.. |Zeno| image:: https://img.shields.io/badge/link-Zeno-yellow.svg?style=flat
   :target: http://www.zeon.co.jp/index_e.html

Copyright |copy| Wei MEI, |MLMS (TM)| |---| all rights reserved. |bamboo|
"""""""""""""""""""""""""

.. |copy| unicode:: 0xA9 .. copyright sign
.. |MLMS (TM)| unicode:: MLMS U+2122
   .. with trademark sign
.. |---| unicode:: U+02014 .. em dash
   :trim:

.. |bamboo| unicode:: 0x1F024 .. bamboo

Fechii Materials Demo
-------------------------

.. raw:: html
   :file: helv-C-14-CT.html

Agilent 7890/5975C-GC/MSD
-------------------------

气相色谱仪类型: 7890A

质谱仪类型: 5973C 通常情况下,不需要设计参数.

开机以及关机

a. 仪器参数的设定;
b. 分析方法的编辑;
c. 谱库的检索;
d. 报告的打印.

故障排查: 首先, 有两个泵, 一个在地上, 一个在仪器里面, 在仪器里面要看一下比较烫.
比较严重的故障:1. 真空泵反油, 主机器扳烧毁.

.. attention:: 
   
   1. 老化柱子: 分段老化。程序升温老化(最好的老化方法)。如HP-5柱，不到20min将其升温完，并反复进行数次。再升至280度，反复数次。接到质谱仪上看基线情况。270度，必须观测到基线提高。再老化到300度半小时。无论何种方式，载气必须充足。
   
   2. 进样口用灰色隔垫，减少隔垫流失。
   
   3. GC/MS接口处必须用vesper垫圈(5062-3508). 注意安装方向(大的一端朝向质谱)。
   
   4. 新柱子安装时无方向性，但一旦使用过，再不要改变方向。
   
   5. Pay attention to the helium tank when the pointer gets to the last one. Alarm the manager so that the helium gas can arrive on time and replace it.
   
   保存柱子时注意将两端密封好，避免水和空气破环柱子内涂层。

You can download :download:`A Quick Guide to Agilent 7890A Gas Chromatograhphy <https://fechii-application-chemical-engineer.readthedocs.io/en/latest/_static/Agilent-7890A-GC-A-Quick-Guide.pdf>` here.

VirtualBox
=============

VirtualBox Pages can be viewed `here <https://www.virtualbox.org/>`_.

VirtualBox can be downloaded `here <https://www.virtualbox.org/wiki/Downloads>`_.

`Windows XP iso <http://windows.sczmwj.com/xp.html>`_

`How to install Windows XP on VirtualBox pages? <https://jingyan.baidu.com/article/574c52196787b06c8c9dc158.html>`_.

`Ubuntu <https://ubuntu.com/download/desktop>`_.


.. code:: python 
   
   >>> m/z 15, 29, 43, 57, 71, 85, 99 -------->  (Aliphatic hydrocarbons: 脂肪烃或链状烃) 代表物： `正庚烷 Heptane <https://pubchem.ncbi.nlm.nih.gov/compound/8900>`
   
   >>> m/z 19, 31, 50, 69 -------->  (Perfluoro compounds: 全氟化合物) 代表物：`四氟化碳 Carbon tetrafluoride  <https://pubchem.ncbi.nlm.nih.gov/compound/6393>`
   
   >>> m/z 30, 44, 58 ----------> (Amines: 胺类) 代表物：`尸胺 Cadaverine <https://pubchem.ncbi.nlm.nih.gov/compound/273>`
   
   >>> m/z 31,45, 59 -----------> (Alcohols or ethers) 代表物：`alpha 松油醇 alpha-TERPINEOL <https://pubchem.ncbi.nlm.nih.gov/compound/17100>`;
   
   代表物：`甲基叔戊基醚 Tert-Amyl methyl ether <https://pubchem.ncbi.nlm.nih.gov/compound/61247>`
   
   >>> m/z 39, 50, 51, 52, 63, 65, 76, 77, 91 --------------> (Aromatic hydrocarbons) 代表物：`六甲基苯 Hexamethylbenzene <https://pubchem.ncbi.nlm.nih.gov/compound/6908>`
   
   >>> m/z 41, 54, 68 ----------------> Aliphatic nitriles
   
   >>> m/z 41, 55, 69 ----------------> Unsaturated hydrocarbons 
   
   >>> m/z 41, 69 ---------------> Methacrylates
   
   >>> m/z 43, 58 ---------------> Methyl ketones
   
   >>> m/z 43, 87 ---------------> Glycol diacetates
   
   >>> m/z 44, 42 ---------------> (CH3)2N-
   
   >>> m/z 53, 80 ---------------> Pyrrole derivatives
   
   >>> m/z 55, 99 ---------------> Glycol diacrylates
   
   >>> m/z 59, 72 ---------------> Amides
   
   >>> m/z 60, 73 ---------------> Underivatized acids
   
   >>> m/z 61, 89 ----------------> Sulfur compounds
   
   >>> m/z 67, 81, 95 ------------> 1-Acetylenes
   
   >>> m/z 69, 41, 86 ------------> "Segemented" fluoromethacrylates
   
   >>> m/z 69, 77, 65 ------------> "Segemented" fluoroiodies
   
   >>> m/z 74, 87 ------------> Methyl esters
   
   >>> m/z 76, 42, 61 --------> (CH3)2NS-
   
   >>> m/z 82, 67 -------> Cyclohexyl compounds
   
   >>> m/z 83, 82, 54 -------> A cyclohexyl ring
   
   >>> m/z 87, 43 -------> Glycol diacetates
   
   >>> m/z 89, 61 --------> Sulfur-containing compounds
   
   >>> m/z 86, 100, 114 ------> Diamines
   
   >>> m/z 99, 55 -----> Glycol acrylates
   
   >>> m/z 104, 91 -------> Alkylbenzenes
   
   >>> m/z 104, 117 -------> Alkylbenzenes


m/z-Chemical Compounds
======================

.. raw:: html
   :file: masstochargeratio.html
   

香味原料
==========

二甲基庚醇-------麝香增效剂--------------松油醇

1. 环十五内酯 果香

2. 环十五烯内酯

3. 麝香烯酮

4. 异麝香酮

5. 异麝香烯酮

6. 开司米酮 龙涎+琥珀 浓烈

7. 麝香 T

8. 黄葵內脂

9. 麝香果酮

10. 环十六烯酮

1. 2020-12-9闻香 

`2020.12.9 <https://fechii-application-chemical-engineer.readthedocs.io/en/latest/_static/2020-12-9.html>`_

2. 2020-12-10

`2020.12.10 <https://fechii-application-chemical-engineer.readthedocs.io/en/latest/_static/2020-12-10.html>`_

2. 2020-12-17

`2020.12.17 <https://fechii-application-chemical-engineer.readthedocs.io/en/latest/_static/2020-12-17.html>`_

仪器购买
=======

.. toctree::
    :maxdepth: 2
    :caption: 仪器购买
    
    Apparatus
    

RT Analysis
===========

.. toctree:: 
   :maxdepth: 5
   :caption: RT Analysis
   
   RT_Analysis
   

SDE Apparatus
==============

.. toctree::
   :maxdepth: 5
   :caption: SDE
   
   SDE
   

GC-MS 进样
===============

.. toctree::
   :maxdepth: 5
   :caption: Sampling
   
   Sampling
   

GC-MS Mass Spectrometry Analysis
===============================

.. toctree::
   :maxdepth: 5
   :caption: MS Analysis
   
   GC-MS-Analysis

Fechii Source Materials
=========================

`Givaudan <https://fechii-application-chemical-engineer.readthedocs.io/en/latest/_static/Givaudan/givaudan.html>`_  



.. toctree:: 
   :maxdepth: 5
   :caption: Source Materials
   
   sourcematerials

.. toctree:: 
   :maxdepth: 5
   :caption: 比较全面的信息表
   
   allinformation

.. toctree::
   :maxdepth: 5
   :caption: fragance_english
   
   fragance_english
   
.. toctree:: 
   :maxdepth: 5
   :caption: 常见的香精原料
   
   commonfragancematerials

.. toctree:: 
   :maxdepth: 5
   :caption: 中文名非中文开头
   
   namestartsunusually

.. toctree:: 
   :maxdepth: 5
   :caption: 中文名以A开头
   
   namestartswitha

.. toctree:: 
   :maxdepth: 5
   :caption: 中文名以B开头
   
   namestartswithb

.. toctree:: 
   :maxdepth: 5
   :caption: 中文名以C开头
   
   namestartswithc

.. toctree:: 
   :maxdepth: 5
   :caption: 中文名以D开头
   
   namestartswithd

Chemical Structures of Source Materials
=======================================

.. toctree:: 
   :maxdepth: 5
   :caption: Chemical Structures of Source Materials
   
   structures
