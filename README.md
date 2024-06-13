## Install Python Packages
Several Python 3 packages are utilized:
  - tarfile
  - xml.etree.ElementTree as ET
  - pandas
  - glob
  - sys
  - datetime
  - csv

All packages except pandas should be Python standard library. Use <b>pip install [package_name]</b> to install or <b>pip install [package_name] --upgrade</b> to upgrade a package.

<br/>

## HathiPrint_Process_Records_Single-part_Monographs

This Python 3 script is used for processing compressed single-part monographs Alma records. After the publication profiles job is done, download all .tar.gz files from FTP server and save them to a local folder (folder_path_1). Create a new folder (folder_path_2) for MARC-XML files. Then create a new folder (folder_path_3) for the results generated by the script.

To run the script, download the Single-part_Monographs.py file (to file_path_4). We recommend you to save the python file and folders in the same folder, so we could use relative path in the command line.
In the command line, 
### In the command line, run: python file_path_4/Single-part_Monographs.py folder_path_1 folder_path_2 folder_path_3
<br/>

## HathiPrint_Process_Records_Multipart_Monographs
This Python 3 script is used for processing compressed multipart monographs Alma records. After the publication profiles job is done, download all .tar.gz files from FTP server and save them to a local folder (folder_path_1). Create a new folder (folder_path_2) for MARC-XML files. Then create a new folder (folder_path_3) for the results generated by the script.

To run the script, download the Multipart_Monographs.py file (to file_path_4). We recommend you to save the python file and folders in the same folder, so we could use relative path in the command line.

In the command line, 
### In the command line, run: python file_path_4/Multipart_Monographs.py folder_path_1 folder_path_2 folder_path_3
                           
<br/>

## HathiPrint_Process_Records_Serials
This Python 3 script is used for processing serials Alma records. After the publication profiles job is done, download all .tar.gz files from FTP server and save them to a local folder (folder_path_1). Create a new folder (folder_path_2) for MARC-XML files. Then create a new folder (folder_path_3) for the results generated by the script.

To run the script, download the Serials.py file (to file_path_4). We recommend you to save the python file and folders in the same folder, so we could use relative path in the command line.

In the command line, 
### In the command line, run: python file_path_4/Serials.py folder_path_1 folder_path_2 folder_path_3
