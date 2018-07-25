.. title:: SQL on Nutanix Training

.. toctree::
  :maxdepth: 2
  :caption: SQL Presentation Deck
  :name: _SQLDeck
  :hidden:

  SQLDeck/deck


.. toctree::
  :maxdepth: 2
  :caption: SQL Hands on Labs
  :name: _labs
  :hidden:

  SQLLAB01/sqllab01
  SQLLAB02/sqllab02


.. toctree::
    :maxdepth: 2
    :caption: SQL Design Lab
    :name: _DESIGNLAN01
    :hidden:

    DESIGNLAB01/designlab1


.. toctree::
  :maxdepth: 2
  :caption: Appendix
  :name: _appendix
  :hidden:

  appendix/glossary

.. _getting_started:

---------------
Getting Started
---------------

This workshop is for quick apply Microsoft SQL Server 2012 (SQL 2014 and SQL 2016 will be less practice to apply) best practice step by step base on SQL on Nutanix best practice for SE or partner training.
I found most of technical persons read the best practice guide but still can’t apply these parameter or settings.
That why I wrote this workshop material for who doesn't have any Microsoft SQL Server technical background but still want apply SQL Server best practice on Nutanix for POC or testing purpose.
It’s a quick way to apply those best practice. I still suggest you must read our Nutanix best guide to understand why we need to change some parameters and configuration to get best performance.
After you learned, You can apply this to your POC or when customer want running Microsoft SQL Server on Nutanix.
In this guide , we didn't mention about how to install Microsoft SQL Server.
If you want learn how to installed Microsoft SQL Server , you can find ”how to” in these links.

- Microsoft SQL Server installation page :
https://docs.microsoft.com/en-us/sql/database-engine/install-windows/install-sql-server?view=sql-server-2017



---------------
Lab Environment
---------------

-Hardware:

  - Nutanix NX ,HX , XC any platform that Nutanix AOS running inside

  - Nutanix CE also can be Lab environment as well

  - You can download Nutanix CE from here. https://www.nutanix.com/products/community-edition/

-Software :

 - Microsoft Windows Server download -

 https://www.microsoft.com/en-us/download/windows.aspx

 - Microsoft SQL Server download -

 https://www.microsoft.com/en-us/download/windows.aspx

 - Recommend using Microsoft SQL Server 2012 database version or above for this lab

Setup Lab
+++++++++
After you foundation your Nutanix blocks (How to Foundation Nutanix Block)
You can watch the video from https://www.nutanix.com/2014/07/15/nutanix-foundation-demo-video-from-bare-metal-to-production-in-minutes/

The foundation software is available on

https://portal.nutanix.com/#/page/foundation/list

After finish foundation, you can create a VM that content Oracle Linux OS. Install Oracle database follow this link -

https://www.youtube.com/watch?v=CwHetPzsQBY


If you have any question, you can send a email to albert.chen@nutanix.com. I will happy to teach you how to setup a environment or provide the base VM image to you.
