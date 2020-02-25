

Using the HPC
=============

**Note:**  Any questions specific to the proper use of the Henry2 cluster should be sent directly to oit_hpc@help.ncsu.edu. 

Basic HPC workflow
******************

Please see HPC's `Getting Started <https://projects.ncsu.edu/hpc/Documents/GetStarted.php>`_ for instructions on all steps.

1. HPC access is available to those with an NCSU Unity ID - see `Request Access <https://projects.ncsu.edu/hpc/Accounts/GetAccess.php>`_ for information
2. Connect to the HPC via ``login.hpc.ncsu.edu`` using any SSH client 
3. Create a job submission script file that contains the commands you want to execute
4. Submit the job script to the appropriate queue and wait until the job is complete
5. Transfer the output data back to your office workstation for further analysis, or write another job submission script to carry out more analysis on the HPC

How to get started
******************

Just as with any new tool, there is a learning curve to using the HPC.  Before using the HPC, you must learn basic Linux and also the basics of using an HPC cluster.  There are many online resources available via the NCSU HPC webpage, and consulting help is available both during scheduled office hours and by request.  

Please see the following resources before you begin:

* `Quick Start Tutorial <https://projects.ncsu.edu/hpc/Guide/>`_
* `HPC training and events <https://projects.ncsu.edu/hpc/Documents/UserTraining.php>`_
* `HPC contact information and consulting <https://projects.ncsu.edu/hpc/Documents/TempAskQuestion.php>`_ 


Installing bioinformatics software on the HPC 
*********************************************

HPC staff cannot install and maintain every application that may be used by the entire University, so `users must install and maintain software for the use of their Project group <https://projects.ncsu.edu/hpc/Software/Software.php>`_.

Here are some of the existing resources supporting the installation of bioinformatics software.

*       `The software group 'bioinfo' <https://docs.google.com/document/d/1G_1zKmWws3g3PTCS9gfOv94Gd96rr6QDo2pHYMTtdkY/edit>`_ contains several Conda environments (QIIME2, DADA2) and some other applications including SPAdes, Canu, and Trimmomatic.
*       `The software group 'spack' <https://docs.google.com/document/d/1ihajkaYzATiWVCJmsg37KJ4f3PFqtLFjsnEdghWqzRs>`_ contains `a wide variety of bioinformatics packages <https://projects.ncsu.edu/hpc/Software/examples/spack/current.html>`_, although they are usually not the latest versions. 
*       Many bioinformatics packages are most appropriately installed with a Conda environment.  `Here are instructions for creating Conda environments. <https://projects.ncsu.edu/hpc/Software/Apps.php?app=Conda>`_

Running bioinformatics software on the HPC 
******************************************

HPC Staff are not domain experts in bioinformatics, and they cannot advise on the fitness of a particular software for a particular scientific workflow.  They can give advice on how to develop and optimize submission scripts, but the advice will be limited if the user knows very little about how the software works.

If an application is staff supported, the `HPC Software Page <https://projects.ncsu.edu/hpc/Software/Software.php>`_ will contain instructions for the software.  deBUG group is collecting instructions from group members on other software packages, and they will be [here in read the docs somewhere, add link]

Please contribute to this group by sharing your knowledge and expertise with the software you *have* used, either by participating in the `Google group discussions <https://groups.google.com/a/ncsu.edu/forum/#!forum/group-bioinformatics-users>`_ or by adding links to your notes and scripts to the following `Google spreadsheet <https://docs.google.com/spreadsheets/d/1L6tQfqHJ1sBqRgmHsjx1u7Ox02WOIY65fpNg2wNHsRQ/edit?usp=sharing>`_ 

