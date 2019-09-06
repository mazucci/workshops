.. _installation:

Installation
============

PostGIS is an extension for the PostgreSQL database to deal with spatial data, so in order to use it we first need an installation of the database engine. The following instructions will guide you using the PostGIS binary installers available from the official project site: https://postgis.net/install/. There are options for multiple platforms.

Windows
-------
For Windows, there is the EnterpriseDb PostgreSQL distributions: https://www.postgresql.org/download/windows/, an interactive installer that will provide the option of installing PostGIS in an installation dialog with "StackBuilder":

   .. image:: ./screenshots/install_postgis.png
     :class: inline
Mac OS X
--------
For OSX users it is possile to install PostGIS along with PostgreSQL using the Postgres app: http://postgresapp.com/. This is the easiest way to do the installation but you can also use the EnterpriseDb installer: https://www.enterprisedb.com/downloads/postgres-postgresql-downloads or the homebrew installer if you are familiar with it by running the command: ``brew install postgis``.

The following steps will guide you in the Postgres app installation:

#. Download the dmg file: https://postgresapp.com/downloads.html.

#. Drag the Postgres icon into your applications folder.

  .. image:: ./screenshots/installosx1.png
  :class: inline

#. Double click the application and allow it to be opened:

  .. image:: ./screenshots/installosx2.png
  :class: inline

#. Click initialize to start the process.

   .. image:: ./screenshots/installosx3.png
   :class: inline
   
#. If successful, you will see the databases available to connect to, this means that the database engine is up and running. By clicking the icons of the databases you will be prompted to a command line but for this workshop, the user interface pgAdmin 4 will be preferred.

   .. image:: ./screenshots/installosx4.png
   :class: inline
   
Install pgAdmin 4
-----------------
#. Go to: https://www.pgadmin.org/download/ to get pgAdmin 4 for your platform.

  The precise directions in this document are for Windows, but for OS X the installation is largely the same. Once the Suite is installed, the directions for both operating systems should be almost identical. 

#. Find OpenGeo Suite installer for your platform. You can download the latest version through `Boundless Connect <http://connect.boundlessgeo.com>`_. OpenGeo Suite is available in the `Downloads <http://connect.boundlessgeo.com/Downloads>`_ area. The Windows installer will be named something like  :file:`opengeosuite-a.b.c.exe`, the Mac OS X installer like :file:`opengeosuite-a.b.c.dmg`). Double click to begin.

#. Enjoy the warm welcome, courtesy of Boundless, then click **Next**.

   .. image:: ./screenshots/install_welcome.png
     :class: inline


#. OpenGeo Suite is licensed under the GNU GPL, which is reproduced on the licensing page. Click **I Agree**.

   .. image:: ./screenshots/install_license.png
     :class: inline


#. The directory where OpenGeo Suite will reside is the usual ``C:\Program Files\`` (or ``C:\Program Files (x86)``) location. Click **Next**.

   .. image:: ./screenshots/install_directory.png
     :class: inline


#. The installer will create a number of shortcuts in the Boundless folder in the Start Menu. Click **Next**.

   .. image:: ./screenshots/install_startmenu.png
     :class: inline


#. Make sure the **PostGIS** component and the **Client Tools** components are selected. Click **Next**.

   .. image:: ./screenshots/install_components.png
     :class: inline


#. Ready for install! Click **Install**.

   .. image:: ./screenshots/install_ready.png
     :class: inline


#. The installation process will run for a couple of minutes.

   .. image:: ./screenshots/install_installing.png
     :class: inline


#. When the installation is complete, launch the Dashboard to start the next section of the workshop! Click **Finish**.

   .. image:: ./screenshots/install_finish.png
     :class: inline
