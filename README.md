# encrypt-pdfs-in-folder
> A script to encrypt each PDF in a folder

## Usage
The script takes three arguments:

* The directory with the PDFs
* The password for those who want to open the PDF
* The owner password

You'll need to install [pdftk](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/), then:

    bash encrypt-pdfs-in-folder.bh directory/ owner_pw user_pw

__Example:__

    bash encrypt-pdfs-in-folder.bh ~/myPDFfolder/ mySuperSecurePw someUserPw
