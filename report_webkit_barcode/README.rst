[![Build Status](https://travis-ci.org/zeroincombenze/webkit-tools.svg?branch=8.0)](https://travis-ci.org/zeroincombenze/webkit-tools)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/webkit-tools/badge.svg?branch=8.0)](https://coveralls.io/github/zeroincombenze/webkit-tools?branch=8.0)
[![codecov](https://codecov.io/gh/zeroincombenze/webkit-tools/branch/8.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/webkit-tools/branch/8.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-8.svg)](https://github.com/OCA/webkit-tools/tree/8.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-8.svg)](http://erp8.zeroincombenze.it)




















































[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

Webkit Report Barcode
=====================

This module Add barcodes in webkit reports

Installation
------------




Configuration
-------------




Usage
-----







=====

To embed a barcode image in a webkit report, use ``${helper.barcode(value)}``.
Depending on template filtering, you might need to force not to use any filter
    by doing ``${helper.barcode(value) | safe}``

The function is defined as:
  barcode(value, code='Code128', drawOpts=None, htmlAttrs=None)

Parameters
value
  Value for barcode as expected by barcode type. Code128 takes a number or
  numeric string
code
  barcode type. ReportLab 2.5 has the following codes: Codabar, Code11,
  Code128, EAN13, EAN8, Extended39, Extended93, FIM, I2of5, MSI, POSTNET, QR,
  Standard39, Standard93, USPS_4State
drawOpts
  dictionary of options for reportlab graphic. Depends on barcode type. Use
  *format* to specify image format (default png), *width* to specify image
  width in pixels (int), *height* to specify image height in pixels (int)
htmlAttrs
  dictionary of html attributes

Requirements
This module depends on reportlab and lxml, which are both part of the odoo
installation.

#. Go to ...

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/{repo_id}/{branch}

.. repo_id is available in https://github.com/OCA/maintainer-tools/blob/master/tools/repos_with_ids.txt
.. branch is "8.0" for example

Known issues / Roadmap
----------------------





* ...

Bug Tracker
-----------





Bugs are tracked on `GitHub Issues
<https://github.com/OCA/{project_repo}/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed `feedback
<https://github.com/OCA/
{project_repo}/issues/new?body=module:%20
{module_name}%0Aversion:%20
{branch}%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Credits
-------





Images

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.





### Contributors





* Vincent Vinet <vincent.vinet@savoirfairelinux.com>
* Cristian Salamea <ovnicraft@gmail.com>

### Funders

### Maintainer








.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.

[//]: # (copyright)

----

**Odoo** is a trademark of [Odoo S.A.](https://www.odoo.com/) (formerly OpenERP, formerly TinyERP)

**OCA**, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

**zeroincombenze®** is a trademark of [SHS-AV s.r.l.](http://www.shs-av.com/)
which distributes and promotes **Odoo** ready-to-use on its own cloud infrastructure.
[Zeroincombenze® distribution](http://wiki.zeroincombenze.org/en/Odoo)
is mainly designed for Italian law and markeplace.
Everytime, every Odoo DB and customized code can be deployed on local server too.

[//]: # (end copyright)

[//]: # (addons)

[//]: # (end addons)

[![chat with us](https://www.shs-av.com/wp-content/chat_with_us.gif)](https://tawk.to/85d4f6e06e68dd4e358797643fe5ee67540e408b)
