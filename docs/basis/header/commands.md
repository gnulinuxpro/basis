# Команды

Некоторые команды и ключи разбираются в разных темах.

#### [05. Текстовый интерфейс пользователя](../05/05._Текстовый_интерфейс_пользователя.md)

```
ls
ls -i
ls --help
man
man -k
info
history
!!
```

#### [06. Пути и директории](../06/06._Пути_и_директории.md)

```
pwd
cd
mkdir
mkdir -p
rmdir
rm -r
ls -R
```

#### [07. Создание и копирование файлов](../07/07._Создание_и_копирование_файлов.md)

```
touch
ls -a
cp
cp -v
cp -i
cp -n
cp -u
cp -l
cp -r
cp -a
```

#### [08. Перемещение, переименование, удаление. Жёсткие и символические ссылки](../08/08._Перемещение,_переименование,_удаление._Жесткие_и_символические_ссылки.md)

```
mv
mv -v
rm
rm -v
rm -r
rm -f
ln
ln -s
ln -v
ls -l
```

#### [09. Чтение текстовых файлов](../09/09._Чтение_текстовых_файлов.md)

```
cat
cat -n
tac
less
head
head -
tail
tail -
tail -n
tail -f
grep
grep -n
grep -r
grep -l
grep -v
```

#### [10. Текстовые редакторы nano и vi](../10/10._Текстовые_редакторы_nano_и_vi.md)

```
nano
vi
vim
```

#### [11. Стандартные потоки](../11/11._Стандартные_потоки.md)

```
>
>>
2>
&>
|
tee
```

#### [12. bash №1: bash-completion, alias, type](../12/12._bash_№1:_bash-completion,_alias,_type.md)

```
alias
ls -d
type
type -a
```

#### [13. bash №2: переменные](../13/13._bash_№2:_переменные.md)

```
echo
env
export
$()
```

#### [14. Процессы №1: Информация о процессах №1](../14/14._Процессы_№1:_Информация_о_процессах_№1.md)

```
ps
ps -e
ps -f
less -S
watch
```

#### [15. Процессы №2: Информация о процессах №2](../15/15._Процессы_№2:_Информация_о_процессах_№2.md)

```
top
w
ulimit
ulimit -u
ulimit -v
nice
nice -n
renice
renice -n
htop
```

#### [16. Процессы №3: Работа с процессами](../16/16._Процессы_№3:_Работа_с_процессами.md)

```
kill
kill -l
kill -9
kill -SIGKILL
pkill
pkill -19
pkill -18
```

#### [17. su](../17/17._su.md)

```
wc -l
exit
su
su -
su -c
```

#### [18. sudo](../18/18._sudo.md)

```
sudo
sudo -s
sudoedit
visudo
visudo -f
hostname
groups
which
```

#### [19. Пользователи](../19/19._Пользователи.md)

```
id
newgrp
chage
chage -l
useradd
useradd -D
useradd -b
useradd -d
useradd -c
useradd -g
useradd -G
useradd -u
passwd
usermod
usermod -m
usermod -aG
userdel
userdel -r
groupadd
groupmod
groupdel
gpasswd
gpasswd -A
gpasswd -M
gpasswd -a
gpasswd -d
lid
lid -g
```

#### [20. Права на файлы](../20/20._Права_на_файлы.md)

```
stat
ls -l
chown
chown -R
chown -v
chgrp
chmod
chmod -v
chmod -R
chmod [+-=][rwxts]
umask
umask -S
getfacl
setfacl
setfacl -m
setfacl -b
```

#### [21. Ядро Linux](../21/21._Ядро_Linux.md)

```
uname
uname -r
du
du -h
modinfo
lscpu
lspci
lsusb
lshw
hardinfo
dmesg
dmesg -w
dmesg -H
modprobe
modprobe -r
lsmod
```

#### [22. Работа с дисками](../22/22._Работа_с_дисками.md)

```
lsscsi
lsscsi -s
fdisk
fdisk -l
cfdisk
lsblk
```

#### [23. Основы файловых систем](../23/23._Основы_файловых_систем.md)

```
iostat
```

#### [24. Работа с файловыми системами](../24/24._Работа_с_файловыми_системами.md)

```
mkfs
mkfs.ext4
tune2fs
tune2fs -l
lsof
lsof +D
mount
df
df -h
blkid
cut
reboot
fsck
```

#### [25. Управление логическими томами - LVM](../25/25._Управление_логическими_томами_-_LVM.md)

```
pvcreate
pvs
pvsdisplay
vgcreate
vgs
vgdisplay
lvcreate
lvs
lvdisplay
lsblk -f
wipefs
wipefs -a
vgextend
lvextend
lvextend -r
resize2fs
lvremove
vgremove
pvremove
lvcreate -s
lvconvert
lvconvert --merge
```

#### [26. Программный RAID - MD](../26/26._Программный_RAID_-_MD.md)

```
mdadm
mdadm -D
```

#### [27. bash скрипты №1](../27/27._bash_скрипты_№1.md)

```
read
read -p
```

#### [28. bash скрипты №2](../28/28._bash_скрипты_№2.md)

```
if
[]
test
```

#### [29. bash скрипты №3](../29/29._bash_скрипты_№3.md)

```
id -u
exit 1
&&
||
[ -o ]
[ -z ]
[ -f ]
```

#### [30. bash скрипты №4](../30/30._bash_скрипты_№4.md)

```
for
select
case
```

#### [31. bash скрипты №5](../31/31._bash_скрипты_№5.md)

```
tr
grep -w
```

#### [32. bash скрипты №6](../32/32._bash_скрипты_№6.md)

```
while
++
--
sleep
until
```

#### [33. Загрузчик GRUB](../33/33._Загрузчик_GRUB.md)

```
grep -e
grub2-mkconfig
grub2-mkconfig -o
lsinitrd
dracut -f
```

#### [34. Система инициализации - systemd](../34/34._Система_инициализации_-_systemd.md)

```
systemctl
systemctl get-default
systemctl list-dependencies
systemctl set-default
systemctl cat
systemctl isolate
systemctl enable
systemctl disable
systemctl is-enabled
```

#### [35. Системный менеджер systemd](../35/35._Системный_менеджер_systemd.md)

```
systemctl stop
systemctl start
systemctl restart
systemctl reload
systemctl mask
systemctl unmask
systemctl status
systemctl --all
systemctl show
```

#### [36. Логирование](../36/36._Логирование.md)

```
journalctl
journalctl -e
journalctl -u
journalctl -f
journalctl -b
logger
logger -p
```

#### [37. Планировщики задач](../37/37._Планировщики_задач.md)

```
at
atq
at -l
at -c
at -f
at -r
atrm
crontab -e
crontab -l
systemd-run
```

#### [38. Создание backup скрипта](../38/38._Создание_backup_скрипта.md)

```
du -s
sort
ls -h
ls -S
find
find -type
find -name
find -user
find -perm
find -exec
find -ls
find -ok
find -mtime
find -delete
tar
tar -c
tar -f
tar -t
tar -x
tar -C
tar -u
tar -z
tar -v
gzip
gzip -k
bzip2
bzip2 -k
date
touch -t
```

#### [39. Инкрементальные бэкапы с tar](../39/39._Инкрементальные_бэкапы_с_tar.md)

```
tar -g
tar -vv
```

#### [40. Дедупликация с VDO](../40/40._Дедупликация_с_VDO.md)

```
vdo
vdo create
vdo status
vdostats
```

#### [41. Создание systemd юнитов](../41/41._Создание_systemd_юнитов.md)

```
systemctl daemon-reload
```