(Not restricted to)Cumulus - Documentation Generator README File
===========================================

"Bash is the gateway drug to automation" ~JR Rivers.

Why was this created:

====================

"Quickly" generate a formatted "baseline" output of all operation commands, My Customer asked for a troubleshooting guide and this would help them get started.

Other reasons:

=============

    Because creating and maintaining accurate and updated documentation is a full-time job. That's why most people simply lack the documentation they need for troubleshooting, regulatory compliance, and change management. This dirty rudimentary script can make the start of this difficult task easier, by automatically creating a baseline document leveraging live network data.

__________________________________________________________________

0\. Description

    A Script written in PHP to generate Documentation from a Production or Lab Network, it takes ~440 troubleshooting commands as input and generates HTML and Markdown pages as output, the output is divided into tables, each one with a different technology area (EVPN, BGP, SNMP...etc), each table has three columns, one for the command, another for the output and the third for the help section.

    __________________________________________________________________

1\. Prerequisites

    A) PHP is used to generate the output, so #!/usr/bin/php needs to be there.

    B) Edit the script 'make.parse.do' to include the host IP, example : $cumulusip = "35.193.138.248"

    C) Edit the script 'make.parse.do' to include the host username, example : $cumulususrname = "cumulus"

    D) Password will be prompted for the user to enter on the console

    E) The password will be prompted three times, so the user needs to manually do that.

    F) The list of commands should be in a file with the file name "initial.commands"

    G) Each section of commands has a heading to mark the section beginning, one pound (#) identifies a heading. (Example of a file is provided)

     __________________________________________________________________

2\. How to run

   A) Extract the files on your personal laptop.

   B) Chmod of the script to be an executable with the command : $ chmod +x make.do.parse

   C) Make sure all variables are provided, including IP address of the destination host.

   D) Execute the script : $ ./make.do.parse

   E) Waiting time is variable, it depends on the length of the list of commands and if something went wrong

   F) Monitor the script performance by logging in to the network host where the host IP was provided earlier and run this command from the home directory of the user : "while true; do echo -ne $(cat current.command)"        \\r" && sleep 1; done"

   G) Install Doxygen

   H) Modify the Doxygen setting file 'Doxyfile' as needed and use it.

   I) Run Doxygen from the same directory as Doxyfile and all the Markdown Files

     __________________________________________________________________

4\. Result

   A) After the script is done, it will require one last prompt for the ssh password on the prompt where the script was run.

   B) The script will generate many markdown files, and then Doxygen can be used later to consume them.

     __________________________________________________________________

5\. Copying

   Contact : ahmed@cumulusnetworks.com

   Copyright © 2018 Cumulus Networks. Free use of this software is

   granted under the terms of the GNU General Public License version 2

   (GPLv2).

     __________________________________________________________________

6\. Disclaimer

   This script was written in two days with only speed in mind and it can be improved in many ways...rewriting it is a better idea.

     __________________________________________________________________

7\. How it looks when running

    Cumulus-AT1176:script.201807191219 ahmed$ ./make.do.parse 

    Password: CumulusLinux!

    To watch progress, in new terminal:

    ssh cumulus@35.193.138.248

    while true; do echo -ne $(cat current.command)"        \\r" && sleep 1; done

    Slow lines:

       sudo cl-support

       sudo cl-support -s

       sudo vtysh (REALLY SLOW)

    Read nitial.commands.

    Generated rocessed.commands.

    cumulus@35.193.138.248's password: (Enter password once, copy from above)

    cumulus@35.193.138.248's password: (Do it again)

    cumulus@35.193.138.248's password: (One last time)

    Generated out.html.

    Generated out.md.

    Cumulus-AT1176:script.201807191219 ahmed$

    Here is how the monitoring window will look like while running and when its done:

    cumulus@oob-mgmt-server:~$ while true; do echo -ne $(cat current.command)"        \\r" && sleep 1; done

    438 nohup cat /etc/cumulus/acl/policy.d/01control_plane_bgp.rules -h        -id|self-originated] -h          

    64 sudo nohup ps -ef        es -h            trol_plane_bgp.rules -h        

    438 nohup cat /etc/cumulus/acl/policy.d/01control_plane_bgp.rules -h        02.0.0.2 --help

8\. Doxygen needs to be install and all that is needed is just to run it in the same directory as all the MD files and the Doxyfile so it would generate the output directory.

    Cumulus-AT1176:doc_gen_cumulus_1.0 ahmed$ doxygen

    Notice: Output directory `output_of_doxygen' does not exist. I have created it for you.

    Searching for include files...

    Searching for example files...

    Searching for images...

    Searching for dot files...

    Searching for msc files...

    Searching for dia files...

    Searching for files to exclude

    Searching INPUT for files to process...

    Reading and parsing tag files

    Parsing files

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/BGP.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/Bridges.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/CLAG.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/ECMP.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/EVPN.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/Filters_and_Access_Lists.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/GRE.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/IGP_MLD_Snooping.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/LACP.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/Layer_1.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/Layer_2.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/Layer_3.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/Logging.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/PBR.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/PIM.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/Pluggables.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/Redistribute.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/Software_and_Licenses.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/Spanning_Tree.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/System_Resources.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/VLANs.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/VRF.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/VRR.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/VXLAN.md...

    Reading /Users/ahmed/Projects/operationalize/paypal_command_ref/doc_gen_cumulus_1.0/NTP.md...

    Building group list...

    Building directory list...

    Building namespace list...

    Building file list...

    Building class list...

    Associating documentation with classes...

    Computing nesting relations for classes...

    Building example list...

    Searching for enumerations...

    Searching for documented typedefs...

    Searching for members imported via using declarations...

    Searching for included using directives...

    Searching for documented variables...

    Building interface member list...

    Building member list...

    Searching for friends...

    Searching for documented defines...

    Computing class inheritance relations...

    Computing class usage relations...

    Flushing cached template relations that have become invalid...

    Computing class relations...

    Add enum values to enums...

    Searching for member function documentation...

    Creating members for template instances...

    Building page list...

    Search for main page...

    Computing page relations...

    Determining the scope of groups...

    Sorting lists...

    Freeing entry tree

    Determining which enums are documented

    Computing member relations...

    Building full member lists recursively...

    Adding members to member groups.

    Computing member references...

    Inheriting documentation...

    Generating disk names...

    Adding source references...

    Adding xrefitems...

    Sorting member lists...

    Computing dependencies between directories...

    Generating citations page...

    Counting data structures...

    Resolving user defined references...

    Finding anchors and sections in the documentation...

    Transferring function references...

    Combining using relations...

    Adding members to index pages...

    Generating style sheet...

    Generating search indices...

    Generating example documentation...

    Generating file sources...

    Generating file documentation...

    Generating page documentation...

    Generating docs for page md_BGP...

    Generating docs for page md_Bridges...

    Generating docs for page md_CLAG...

    Generating docs for page md_ECMP...

    Generating docs for page md_EVPN...

    Generating docs for page md_Filters_and_Access_Lists...

    Generating docs for page md_GRE...

    Generating docs for page md_IGP_MLD_Snooping...

    Generating docs for page md_LACP...

    Generating docs for page md_Layer_1...

    Generating docs for page md_Layer_2...

    Generating docs for page md_Layer_3...

    Generating docs for page md_Logging...

    Generating docs for page md_PBR...

    Generating docs for page md_PIM...

    Generating docs for page md_Pluggables...

    Generating docs for page md_Redistribute...

    Generating docs for page md_Software_and_Licenses...

    Generating docs for page md_Spanning_Tree...

    Generating docs for page md_System_Resources...

    Generating docs for page md_VLANs...

    Generating docs for page md_VRF...

    Generating docs for page md_VRR...

    Generating docs for page md_VXLAN...

    Generating docs for page md_NTP...

    Generating group documentation...

    Generating class documentation...

    Generating namespace index...

    Generating graph info page...

    Generating directory documentation...

    Generating index page...

    Generating page index...

    Generating module index...

    Generating namespace index...

    Generating namespace member index...

    Generating annotated compound index...

    Generating alphabetical compound index...

    Generating hierarchical class index...

    Generating member index...

    Generating file index...

    Generating file member index...

    Generating example index...

    finalizing index lists...

    writing tag file...

    lookup cache used 0/65536 hits=0 misses=0

    finished...

    Cumulus-AT1176:doc_gen_cumulus_1.0 ahmed$

   
