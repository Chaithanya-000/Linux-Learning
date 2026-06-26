# Process Management Commands

## ps

Purpose:
Currently running processes ni chupisthundi.

Syntax:
ps

Example:
ps

Output:
Current terminal ki sambandhinchina processes display avuthayi.

---

## ps -ef

Purpose:
System lo running processes anni detailed ga chupisthundi.

Syntax:
ps -ef

Example:
ps -ef

Output:
All running processes details display avuthayi.

---

## top

Purpose:
Live system processes and resource usage monitor cheyyadaniki.

Syntax:
top

Example:
top

Output:
CPU, Memory, Running Processes live ga display avuthayi.

---

## kill

Purpose:
Specific process ni stop cheyyadaniki.

Syntax:
kill <PID>

Example:
kill 1234

Output:
PID 1234 process terminate avuthundi.

---

## kill -9

Purpose:
Force ga process terminate cheyyadaniki.

Syntax:
kill -9 <PID>

Example:
kill -9 1234

Output:
Process immediate ga stop avuthundi.

---

## pkill

Purpose:
Process name batti process terminate cheyyadaniki.

Syntax:
pkill <process_name>

Example:
pkill firefox

Output:
firefox process stop avuthundi.

---

## jobs

Purpose:
Current shell lo running background jobs chupisthundi.

Syntax:
jobs

Example:
jobs

Output:
Background jobs list display avuthundi.

---

## bg

Purpose:
Stopped job ni background lo run cheyyadaniki.

Syntax:
bg

Example:
bg

Output:
Job background lo continue avuthundi.

---

## fg

Purpose:
Background job ni foreground ki teesukuravadaniki.

Syntax:
fg

Example:
fg

Output:
Job foreground lo run avuthundi.

---

## nohup

Purpose:
Terminal close ayina process continue ga run avvadanki.

Syntax:
nohup <command> &

Example:
nohup python app.py &

Output:
Process terminal close ayina continue ga run avuthundi.
