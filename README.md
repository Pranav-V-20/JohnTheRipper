# JohnTheRipper

Installation
---
John the ripper tool is alread avaliable in kali linux

Crack
---
First change thr zip file into txt file :

    zip2john Sample.zip > sample.txt

Then use cat function to decrypt it:ol

    cat sample.txt

To start attack:

    john sample.txt

It takes time to crack the password according to the bit size
The above mentoned Filenames are depends on sample file attached to the repositor

Other
---
You can create your own zip file in kali linux:
First install plugin:

    sudo apt install zip

To zip the file first enter into the folder where the file is stored by using cd comand
Then zip the file:

    zip -e outputfilename.zip sourcefilename

Disclaimer
---
Use only for educational purpose
