# EasyDockVina

/////////////////////////////////////////////////////////////////////////<br/>
<br/>

        - #EasyDockVina is a free tool to perform multiple receptor-ligand
          docking with AutoDockVina.	
        - Programmed By AhmedElTijani AKA S3cr3tSDN	
<br/>
/////////////////////////////////////////////////////////////////////////<br/>


[+] Tool Usage:

        EasyDockVina dock [parameters]

[+] Parameters:

        --receptor file.pdbqt                   Receptor should be prepared and in pdbqt format.
        --ligands ./ligands/                    Ligands folder, all ligands should be in pdbqt format.
        --config config.txt                     Config file should only contain search box center and size.
        --output docking_result.txt             All docking results will be written on the file specified.

[+] Example:

        EasyDockVina dock --receptor e2cr.pdbqt --ligands ./ligands/ --config config.txt --output results.txt
        
        
Config.txt file should contain only:<br/>
center_x = XXXXXX<br/>
center_y = YYYYYY<br/>
center_z = ZZZZZZ<br/>
size_x = XXXXXX<br/>
size_y = YYYYYY<br/>
size_z = ZZZZZZ <br/>


this tool will only work on windows machines, linux version is on the way.<br/>
Please report any bug to s3cr3tsdn@gmail.com<br/>
if you need help to configure EasyDockVina to run on a webserver, contact me at s3cr3tsdn@gmail.com<br/>
