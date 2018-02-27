
.. _h1441783432115d27343710632e743d25:

Installation Guide

*******************

.. _h63431b712245581753c63164c674c:

RPM Package Installation
========================

To install Ne.Mo. Network Monitoring Tool you must have a machine with CentOS 6.5 (64bit) or higher, physical or virtual.The amount of RAM, CPU and DISK depends on how many devices you want to monitor. A basic server installation is enough. You can found the CentOS 6.6 ISO at the following url:

\ |LINK1|\ 

Then you have to configure the repository as the follow:


.. code:: 

    cd /etc/yum.repos.d
    wget http://www.nemosupport.com/nemo.repo

The repository is authenticated so you have to request an account from the contact form at http://www.nemosupport.com/ or writing an email to \ |LINK2|\ .

After you receive the username and password to access our repository it is necessary modifying the nemo.repo file like that:


.. code:: 

    [nemo]
    name=Nemo Repository - ScaiConnect s.r.l.
    baseurl=http://theusername:thepassword@www.nemosupport.com/repo/6/$basearch/
    enabled=1
    gpgcheck=0

.. _h5d4055157f105b6d3d711325e757b35:

Hardware And System Requiremets
===============================

The minimum requirements to install Ne.Mo. are:

* CentOS 6.5 x86_64bit Operating System

* CPU Intel Pentium IV 2.4Ghz

* Ram: minimum 2GB.

* Hard Disk: minimum 3 Gbyte for the software and additional space for data retention


In the previous situation, the system can manage up to 20.000 collected entities (measures) polling them every 5 minutes.


.. bottom of content


.. |LINK1| raw:: html

    <a href="http://www.nemosupport.com/download/CentOS-6.6-x86_64-minimal.iso" target="_blank">http://www.nemosupport.com/download/CentOS-6.6-x86_64-minimal.iso</a>

.. |LINK2| raw:: html

    <a href="mailto:support@nemosupport.com">support@nemosupport.com</a>

