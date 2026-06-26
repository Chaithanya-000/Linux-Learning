# Archive and Compression Commands

## tar

Purpose:
Multiple files and folders ni oka archive file ga create cheyyadaniki.

Syntax:
tar -cvf <archive_name.tar> <files_or_folders>

Example:
tar -cvf backup.tar Documents

Output:
Documents folder backup.tar file lo archive avuthundi.

---

## tar -xvf

Purpose:
Tar archive ni extract cheyyadaniki.

Syntax:
tar -xvf <archive_name.tar>

Example:
tar -xvf backup.tar

Output:
backup.tar content extract avuthundi.

---

## tar -czvf

Purpose:
Tar archive ni gzip compression tho create cheyyadaniki.

Syntax:
tar -czvf <archive_name.tar.gz> <files_or_folders>

Example:
tar -czvf backup.tar.gz Documents

Output:
Compressed archive create avuthundi.

---

## tar -xzvf

Purpose:
Compressed tar.gz archive ni extract cheyyadaniki.

Syntax:
tar -xzvf <archive_name.tar.gz>

Example:
tar -xzvf backup.tar.gz

Output:
Archive content extract avuthundi.

---

## gzip

Purpose:
File ni compress cheyyadaniki.

Syntax:
gzip <file_name>

Example:
gzip notes.txt

Output:
notes.txt.gz file create avuthundi.

---

## gunzip

Purpose:
Gzip compressed file ni extract cheyyadaniki.

Syntax:
gunzip <file_name.gz>

Example:
gunzip notes.txt.gz

Output:
Original notes.txt file restore avuthundi.

---

## zip

Purpose:
Files and folders ni ZIP archive ga compress cheyyadaniki.

Syntax:
zip -r <archive_name.zip> <folder_name>

Example:
zip -r project.zip Project

Output:
project.zip file create avuthundi.

---

## unzip

Purpose:
ZIP archive ni extract cheyyadaniki.

Syntax:
unzip <archive_name.zip>

Example:
unzip project.zip

Output:
ZIP file content extract avuthundi.

---

## zipinfo

Purpose:
ZIP file details chudadaniki.

Syntax:
zipinfo <archive_name.zip>

Example:
zipinfo project.zip

Output:
ZIP file lo unna files information display avuthundi.
