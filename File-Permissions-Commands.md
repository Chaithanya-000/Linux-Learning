# File Permissions Commands

## chmod

Purpose:
File or directory permissions change cheyyadaniki.

Syntax:
chmod <permissions> <file_name>

Example:
chmod 777 notes.txt

Output:
notes.txt ki read, write, execute permissions provide avuthayi.

---

## chown

Purpose:
File owner ni change cheyyadaniki.

Syntax:
chown <owner> <file_name>

Example:
chown user1 notes.txt

Output:
notes.txt owner user1 ga maruthadu.

---

## chgrp

Purpose:
File group ni change cheyyadaniki.

Syntax:
chgrp <group_name> <file_name>

Example:
chgrp developers notes.txt

Output:
notes.txt group developers ga maruthundi.

---

## umask

Purpose:
New files and folders create ayyeppudu default permissions set cheyyadaniki.

Syntax:
umask

Example:
umask

Output:
Current default permission mask display avuthundi.
