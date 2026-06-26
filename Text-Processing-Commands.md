# Text Processing Commands

## cat

Purpose:
File content ni display cheyyadaniki.

Syntax:
cat <file_name>

Example:
cat notes.txt

Output:
notes.txt lo unna content display avuthundi.

---

## more

Purpose:
Large file content ni page by page ga chudadaniki.

Syntax:
more <file_name>

Example:
more notes.txt

Output:
File content page wise display avuthundi.

---

## less

Purpose:
File content ni forward and backward scroll chesthu chudadaniki.

Syntax:
less <file_name>

Example:
less notes.txt

Output:
File content interactive mode lo display avuthundi.

---

## head

Purpose:
File lo first 10 lines display cheyyadaniki.

Syntax:
head <file_name>

Example:
head notes.txt

Output:
File first 10 lines display avuthayi.

---

## head -n

Purpose:
Specified number of lines ni beginning nundi display cheyyadaniki.

Syntax:
head -n <number> <file_name>

Example:
head -n 5 notes.txt

Output:
First 5 lines display avuthayi.

---

## tail

Purpose:
File lo last 10 lines display cheyyadaniki.

Syntax:
tail <file_name>

Example:
tail notes.txt

Output:
File last 10 lines display avuthayi.

---

## tail -n

Purpose:
Specified number of lines ni ending nundi display cheyyadaniki.

Syntax:
tail -n <number> <file_name>

Example:
tail -n 5 notes.txt

Output:
Last 5 lines display avuthayi.

---

## grep

Purpose:
File lo specific word or pattern search cheyyadaniki.

Syntax:
grep "<word>" <file_name>

Example:
grep "Linux" notes.txt

Output:
Linux unna lines display avuthayi.

---

## grep -i

Purpose:
Case insensitive search cheyyadaniki.

Syntax:
grep -i "<word>" <file_name>

Example:
grep -i "linux" notes.txt

Output:
Linux, linux, LINUX anni match avuthayi.

---

## wc

Purpose:
File lo lines, words, characters count cheyyadaniki.

Syntax:
wc <file_name>

Example:
wc notes.txt

Output:
Lines, words, characters count display avuthayi.

---

## wc -l

Purpose:
File lo total lines count cheyyadaniki.

Syntax:
wc -l <file_name>

Example:
wc -l notes.txt

Output:
Total line count display avuthundi.

---

## sort

Purpose:
Data ni alphabetical order lo sort cheyyadaniki.

Syntax:
sort <file_name>

Example:
sort names.txt

Output:
Content alphabetical order lo display avuthundi.

---

## uniq

Purpose:
Consecutive duplicate lines ni remove cheyyadaniki.

Syntax:
uniq <file_name>

Example:
uniq names.txt

Output:
Duplicate consecutive lines remove avuthayi.

---

## cut

Purpose:
Line lo specific field or column extract cheyyadaniki.

Syntax:
cut -d "<delimiter>" -f <field_number> <file_name>

Example:
cut -d ":" -f 1 users.txt

Output:
First field maatrame display avuthundi.
