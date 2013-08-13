jboss-quickstarts-sandbox: Quickstarts sandbox
==============================================

The quickstarts in this project are examples that originate from multiple external Git repositories and are then combined in this project as Git submodules. 

They do not fit the standard pattern of the other quickstarts where you use Maven to build and deploy the quickstart and then access the URL via a browser. These quickstarts may require you to install additional software or follow more complex setup and testing procedures.


Check Out the Quickstart Source
-----------------------------

Git submodules allow you clone another repository as a subdirectory in your project, but keep its source and commits separate. The following Git commands are used to fetch data from submodules into the project.

1. To clone this Git repository, use the following command:

        git clone --recursive https://github.com/jboss-jdf/jboss-quickstarts-sandbox.git
   _Note: This command creates the directories for the submodules, but does not download the data._
2. After you clone the repository, use the following command to initialize the and fetch data from the submodule project:

        git submodule update --init
3. To refresh the submodule with any updates to the external project, run the following command:

        git submodule update



