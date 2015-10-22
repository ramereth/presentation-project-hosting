Project Hosting 3.0
===================

.. revealjs:: Project Hosting 3.0
  :title-heading: h2
  :subtitle: Lance Albertson
  :subtitle-heading: h3

.. revealjs:: Session Summary

  * Brief history of FOSS hosting
  * Advances made
  * What the future holds
  * Discuss future of FOSS hosting

.. revealjs:: Types of FOSS Hosting

  .. rst-class:: fragment

    File Hosting

    Hosted Platform Hosting

    Co-Location Hosting

    Continuous Integration Hosting

.. revealjs:: Evolution of FOSS hosting

  .. revealjs:: File hosting

    Typically FTP and/or HTTP web servers hosted by:

    * Universities (IU, MIT, OSU)
    * ISP's
    * Other orgs (Kernel.org, ISC)

  .. revealjs:: Hosted Platform hosting

    * SourceForge (1999)
    * GNU Savannah (2001)
    * LaunchPad (2004)
    * Google Code (2006)
    * Github (2008)
    * GitLab (2001)

  .. revealjs:: Co-Location Hosting

    * ISC (1994)
    * OSU Open Source Lab (2003)
    * *Anyone else?*

  .. revealjs:: Continuous Integration Hosting

    * CircleCI (2011)
    * Travis CI (2012)
    * Drone.io (2014)

.. revealjs:: Major Advances

  .. rst-class:: fragment

    Github

    Public cloud computing

    Cheaper CDN storage

    CI testing platforms

.. revealjs:: Co-Location vs. Public Cloud

  .. csv-table::
    :header: Co-Location, Public Cloud

    More expensive, Cheaper initial costs
    Less flexible, More flexible
    Better Performance, Performance varies
    More control, Less control
    Hardware ownership, Pay for the service

.. revealjs:: OSL Advances

  .. revealjs:: Cloud-based Hosting

     * Flexible elastic computing
     * Cheaper hosting options
     * No need for buying hardware

  .. revealjs:: New tools and technologies

    .. rst-class:: fragment

      Virtual computing

      * OpenStack
      * Ganeti

      Storage Technologies

      * GlusterFS
      * Ceph

  .. revealjs:: Configuration Management

    .. rst-class:: fragment

      Chef

      Integration testing on infrastructure

      Scale up infrastructure easier

      Standardize deployments of services

      Delegate infrastructure code with projects

.. revealjs:: What do FOSS Projects Need?

  .. revealjs:: Testing Resources

    .. rst-class:: fragment

      Flexible testing compute resources

      Customizable test integration tools

      Unique testing challenges

    .. rv_note::

      Things that don't fit well with free services like TravisCI.

      TravisCI can be slow, having dedicated high performance bare metal
      hardware is important

      Some projects need to test their hardware at a larger scale to fix or find
      bugs

  .. revealjs:: Managed Service Hosting

    .. rst-class:: fragment

      Hosting complex platforms:

      Gerrit, Gitlab, Jenkins, etc

      Mailman, Jira, etc

      They need the service, but don't want to manage it

  .. revealjs:: Neutral CDN Mirroring

    .. rst-class:: fragment

      Projects get popular and need to scale fast

      Current FTP mirroring infrastructure not flexible enough

      API-driven, geographically diverse

      Hosted by a trusted entity

  .. revealjs:: Access to specialized hardware

    .. rst-class:: fragment

      New and upcoming hardware (ARM64, POWER8, etc)

      Porting and fixing bugs

.. revealjs:: How do we get there?

.. revealjs:: OSL Vision 2.0

  .. revealjs:: Technical Upgrade

    .. rst-class:: fragment

      Build and expand Cloud infrastructure (Ganeti & OpenStack)

      Automated Build Services

      Test Services and Support

      Project Dashboards

      OSL CDN (ftp mirroring 2.0)

      Security Audits

  .. revealjs:: OSL University Network

    .. rst-class:: fragment

      Collaborate with global universities

      Host half rack of gear

      OpenStack / Ganeti

      Mentor students at those universities

  .. revealjs:: Re-engineer backend services

    .. rst-class:: fragment

      Convert everything to Chef + CentOS

      Catch up with technology trends

      Fully testable infrastructure

      Make it more robust to failure

.. revealjs:: OSL - SuperCell

  .. revealjs:: Currently

    .. rst-class:: fragment

      Created in 2010 in conjunction with Facebook

      Utilized Ganeti to offer VM compute resources to projects

      Dozen or so projects are currently using it

  .. revealjs:: Plans

    .. rst-class:: fragment

      Rebuild with OpenStack and expand resources

      Ease on-boarding for projects

      Offer pre-built managed CI solutions

      Access to upcoming testing suites from Academia

.. revealjs:: Summary

  .. rst-class:: fragment

    Testing resources are important to projects

    Need a place to host unique hardware

    Managed service hosting

    We need your help!

.. revealjs:: Discussion future of FOSS hosting

  .. rst-class:: fragment

    What do YOU need?

    What is missing?

    What's important to you?

    What should the OSL be doing? 

.. revealjs:: Questions?

  Lance Albertson

  lance@osuosl.org

  `@ramereth`_

  http://osuosl.org

  http://lancealbertson.com

  *Attribution-ShareAlike CC BY-SA ©2015*

  .. raw:: HTML

    <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
    <img alt="Creative Commons License" style="border-width:0"
    src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>

.. _@ramereth: http://twitter.com/ramereth
