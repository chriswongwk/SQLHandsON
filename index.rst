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


**Just One Thing. The HOL is simple and short. Read carefully** 

What's New
++++++++++

- Workshop updated for the following software versions:
  - AOS 5.9.1

Access Instructions
+++++++++++++++++++

The Nutanix Hosted POC environment can be accessed a number of different ways:

Citrix XenDesktop
.................

https://citrixready.nutanix.com - *Accessible via the Citrix Receiver client or HTML5*

Or, 

VMware Horizon View
...................

https://hostedpoc.nutanix.com  - *Accessible via the View client or HTML5*


**Nutanix Employees** - Use your NUTANIXDC credentials

**Non-Employees** - **Username:** POCxxx-User01 (up to POCxxx-User20), **Password:** partnerSE/4u

We have 4 cluster today, each cluster will be shared with 10 participants. You will be informed your cluster number and user number before you start your HOL.

POC-031, Brian	Fu, RonaldChoy, Benny	Ho

POC-086, Gary	Lau, Yuki	Leung, Brian	Ku

POC-087, Ryan	ng, David	Chow, Jonathan Chan

POC-089, Brian	Tse, Ryan	Chan, Peter	Cheng, Linus	Yip

If your VDI is slow try to use this VPN.

Non-Employee Pulse Secure VPN
https://lab-vpn.nutanix.com - Username: POCxxx-User01 (up to POCxxx-User20), Password: partnerSE/4u

Under Client Application Sessions, click Start to the right of Pulse Secure to download the client.

Install and open Pulse Secure.

Add a connection:

Type - Policy Secure (UAC) or Connection Server
Name - HPOC VPN
Server URL - lab-vpn.nutanix.com

---------------
Lab Environment
---------------

-Hardware:
NX1365G54/G5

-Software :

 - Microsoft Windows Server download -

\\hpoc-afs\se\chriswong\iso\windows

 - Microsoft SQL Server download -
 
\\hpoc-afs\se\chriswong\iso\windows


Setup Lab
+++++++++

Upload the WIndows ISO
create a Windows VM
Install Hammer DB
Install SQL server



