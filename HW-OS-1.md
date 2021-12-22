# 1. 
chdir("/tmp")
# 2. 
/usr/share/misc/magic
# 3. 
> "/proc/$pid/fd/$fd" при условии что знаем PID и FD в котором открыт файл (или килльнуть PID который держит открытым)
# 4. 
нет, только слот PID
# 5. 
../lib64/..                            
# 6.
Part of the utsname information is also accessible via /proc/sys/kernel/{ostype, hostname, osrelease, version, domainname}.
# 7. 
при && следующие команды исполняются только после удачного завершения предыдущих. Да, есть смысл для решения задач автоматизации
# 8. 
e  Exit immediately if a command exits with a non-zero status.
x  Print commands and their arguments as they are executed.
u  Treat unset variables as an error when substituting.
o option-name Set the variable corresponding to option-name
Смысла использовать этот набор модификаторов не было, т.к. необходимо было научиться видеть и системные вызовы когда что-то идет не так (что невозможно с -х)
# 9. 
s - interruptible sleep
