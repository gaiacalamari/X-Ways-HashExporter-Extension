# X-Ways-HashExporter-Extension
This X-Ways Forensics extension automates the export of hashes from an image
While the extension could be run from the X-Ways gui, it can also be run from the command-line.

<code>D:\XWAYS>"c:\Program Files\X-Ways Forensics\xwb64.exe" "NewCase:D:\XWAYS\test" "AddImage:d:\XWAYS\testdisk.img" "AddImage:d:\XWAYS\test2.img" "XT:D:\XWAYS\XT_HashExporter.dll" RVS:~ auto</code>

I thought to automate the process of loading forensic acquisitions, traversing and the Refine Volume Snapshot with a DLG file created by me, useful before exporting documents and mail. 
To edit the DLG file, go to the xways GUI.

<code>"C:\xwf21.5\xwforensics64.exe" "NewCase:W:\xways" "AddImage:L:\Digital Corpora\PC\CF\nps-2008-jean.E01" "AddImage:L:\BSidesAmman21\CF\BSidesAmman21.E01" RVS:~ "C:\xwf21.5\XTension\RVS -pre-export documents and mail.dlg" </code>

![2025-10-22 12-24-22_parte1](https://github.com/user-attachments/assets/65f1427c-59be-49f7-80ea-9b0787e1d923)
![2025-10-22 12-24-22_parte2](https://github.com/user-attachments/assets/a61240a4-7115-4dc4-9b8a-362ca3c874af)

## License
Polito Inc. is providing the HashExporter extension ("this Software") for free for the benefit of the Digital Forensics community. This Software is provided "as is", without any warranty of any kind, express or implied. You may copy, distribute, and use this Software without charge for commercial or non-commercial purposes, provided that you give full credit to its source and you do not sell, rent, or lease it. While we are unable to provide support for this Software, feel free to contact us at  <b>info(at)politoinc.com</b>  with any bug reports or feature requests. Also feel free to contact us if you have suggestions for other X-Ways extensions. 
<p>Hashes of the files : 

<p>  MD5      9C54E8F431983CEA3D8BF298898A6BEA                 XT_HashExporter.dll
<p> After running plugin, output of results are in a file : casename_Hashes.txt
<p>
<!-- See blog post here for more details and instructions for how to use this extension in X-Ways: -->
<img src="./x-ways-hashing.gif">


