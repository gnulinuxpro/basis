Некоторые команды и ключи разбираются в разных темах.

#### [05. Текстовый интерфейс пользователя](05._Текстовый_интерфейс_пользователя.md)

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

#### [06. Пути и директории](06._Пути_и_директории.md)

```
pwd
cd
mkdir
mkdir -p
rmdir
rm -r
ls -R
```

#### [07. Создание и копирование файлов](07._Создание_и_копирование_файлов.md)

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

#### [08. Перемещение, переименование, удаление. Жёсткие и символические ссылки](08._Перемещение,_переименование,_удаление._Жесткие_и_символические_ссылки.md)

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

#### [09. Чтение текстовых файлов](09._Чтение_текстовых_файлов.md)

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

#### [10. Текстовые редакторы nano и vi](10._Текстовые_редакторы_nano_и_vi.md)

```
nano
vi
vim
```

#### [11. Стандартные потоки](11._Стандартные_потоки.md)

```
>
>>
2>
&>
|
tee
```

#### [12. bash №1: bash-completion, alias, type](12._bash_№1:_bash-completion,_alias,_type.md)

```
alias
ls -d
type
type -a
```

#### [13. bash №2: переменные](13._bash_№2:_переменные.md)

```
echo
env
export
```

#### [14. Процессы №1: Информация о процессах №1](14._Процессы_№1:_Информация_о_процессах_№1.md)

```
ps
ps -e
ps -f
less -S
watch
```

#### [15. Процессы №2: Информация о процессах №2](15._Процессы_№2:_Информация_о_процессах_№2.md)

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

#### [16. Процессы №3: Работа с процессами](16._Процессы_№3:_Работа_с_процессами.md)

```
kill
kill -l
kill -9
kill -SIGKILL
pkill
pkill -19
pkill -18
```

#### [17. su](17._su.md)

```
wc -l
exit
su
su -
su -c
```

#### [18. sudo](18._sudo.md)

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

#### [19. Пользователи](19._Пользователи.md)

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

#### [20. Права на файлы](20._Права_на_файлы.md)

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

#### [21. Ядро Linux](21._Ядро_Linux.md)

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

#### [22. Работа с дисками](22._Работа_с_дисками.md)

```
lsscsi
lsscsi -s
fdisk
fdisk -l
cfdisk
lsblk
```

#### [23. Основы файловых систем](23._Основы_файловых_систем.md)

```
iostat
```

#### [24. Работа с файловыми системами](24._Работа_с_файловыми_системами.md)

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

#### [25. Управление логическими томами - LVM](25._Управление_логическими_томами_-_LVM.md)

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

#### [26. Программный RAID - MD](26._Программный_RAID_-_MD.md)

```
mdadm
mdadm -D
```

#### [27. bash скрипты №1](27._bash_скрипты_№1.md)

```
read
read -p
```

#### [28. bash скрипты №2](28._bash_скрипты_№2.md)

```
if
[
test
```