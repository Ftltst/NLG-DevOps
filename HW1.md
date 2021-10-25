5. 2 cores, 1 gb ram
6. vi vagrantfile 
   config.vm.provider "virtualbox" do |v|
   v.memory = XXXX #mb
   v.cpus = X #cpus
   end
8
   1. _echo export HISTSIZE=10000 >> /etc/bash.bashrc_ 684 строка
   2. игнорировать команды начинающиеся с пробела И дупликаты
9 {} задает list для команд (ниже пример) на 221 строке
10 10000 через touch file-{1..10000}, 300000 не влезет в 128кб команда (лимит системы).
11 проверяет наличие /tmp и что это является папкой
12   mkdir -p /tmp/new_path_dir/
     ln -s /bin/bash /tmp/new_path_dir/bash
     PATH="/tmp/new_path_dir:$PATH" type -a bash
13 ``` batch используется только в интерактивном режиме,
   вместо работы джобов по расписанию - загружает их в очередь и исполняет ее только при низкой загрузке системы
   отсюда разница в том что нет возможности задать конкретное время и дату исполнения```
