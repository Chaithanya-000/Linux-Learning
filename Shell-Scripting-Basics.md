# Shell Scripting Basics

## bash

Purpose:
Shell script execute cheyyadaniki.

Syntax:
bash <script_name.sh>

Example:
bash hello.sh

Output:
hello.sh script execute avuthundi.

---

## chmod +x

Purpose:
Script ki execute permission ivvadaniki.

Syntax:
chmod +x <script_name.sh>

Example:
chmod +x hello.sh

Output:
Script executable avuthundi.

---

## ./

Purpose:
Current directory lo unna script run cheyyadaniki.

Syntax:
./<script_name.sh>

Example:
./hello.sh

Output:
Script execute avuthundi.

---

## echo

Purpose:
Message print cheyyadaniki.

Syntax:
echo <message>

Example:
echo "Hello World"

Output:
Hello World

---

## read

Purpose:
User input teesukovadaniki.

Syntax:
read <variable_name>

Example:
read name

Output:
User input variable lo store avuthundi.

---

## Variable

Purpose:
Data ni variable lo store cheyyadaniki.

Syntax:
variable_name=value

Example:
name="Chaithanya"

Output:
Value variable lo store avuthundi.

---

## if

Purpose:
Condition check cheyyadaniki.

Syntax:
if [ condition ]
then
    commands
fi

Example:
if [ 10 -gt 5 ]
then
    echo "True"
fi

Output:
True

---

## if-else

Purpose:
Condition true or false batti commands execute cheyyadaniki.

Syntax:
if [ condition ]
then
    commands
else
    commands
fi

Example:
if [ 5 -gt 10 ]
then
    echo "True"
else
    echo "False"
fi

Output:
False

---

## for

Purpose:
Loop use chesi repeated ga commands execute cheyyadaniki.

Syntax:
for variable in values
do
    commands
done

Example:
for i in 1 2 3
do
    echo $i
done

Output:
1
2
3

---

## while

Purpose:
Condition true unna varaku loop run cheyyadaniki.

Syntax:
while [ condition ]
do
    commands
done

Example:
count=1

while [ $count -le 3 ]
do
    echo $count
    count=$((count+1))
done

Output:
1
2
3

---

## function

Purpose:
Reusable code block create cheyyadaniki.

Syntax:
function_name() {
    commands
}

Example:
greet() {
    echo "Hello"
}

greet

Output:
Hello

---

## exit

Purpose:
Script execution stop cheyyadaniki.

Syntax:
exit <status_code>

Example:
exit 0

Output:
Script successful ga terminate avuthundi.
