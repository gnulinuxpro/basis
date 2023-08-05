# Commands

Some commands and options are covered in different topics.

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
systemctl list-units
systemctl enable --now
systemctl disable --now
```

#### [43. Работа с сетью](../43/43._Работа_с_сетью.md)

```
ip
ip address
ip route
ip link
ping
traceroute
nslookup
nmtui
```

#### [44. Удалённый доступ - SSH](../44/44._Удалённый_доступ_-_SSH.md)

```
ssh
ssh -X
ssh-copy-id
```

#### [45. Принудительный контроль доступа - SElinux](../45/45._Принудительный_контроль_доступа_-_SElinux.md)

```
sestatus
getenforce
setenforce
semanage
semanage login
semanage user
semanage port
semanage fcontext
semanage boolean
semanage export
id -Z
ps -Z
ls -Z
chconf
restorecon
getsebool
setsebool
setsebool -P
```

#### [46. Межсетевой экран - firewalld](../46/46._Межсетевой_экран_-_firewalld.md)

```
firewall-cmd
firewall-cmd --permanent
firewall-cmd --reload
firewall-cmd --add-port
firewall-cmd --remove-port
firewall-cmd --list-all
firewall-cmd --info-service
firewall-cmd --list-services
firewall-cmd --list-ports
firewall-cmd --remove-service
firewall-cmd --get-icmptypes
firewall-cmd --add-icmp-block-inversion
firewall-cmd --remove-icmp-block-inversion
firewall-cmd --set-target
firewall-cmd --get-zones
firewall-cmd --get-default-zone
firewall-cmd --change-interface
firewall-cmd --list-interfaces
firewall-cmd --add-source
firewall-cmd --add-masquerade
firewall-cmd --runtime-to-permanent
firewall-cmd --list-all-zones
firewall-cmd --panic-on
firewall-cmd --panic-off
firewall-cmd --add-rich-rule
firewall-cmd --remove-rich-rule
ss
ss -n
ss -l
ss -t
ss -a
nc
nc -z
nc -v
nc -u
nc -l
```

#### [47. Пакетный менеджер - dnf](../47/47._Пакетный_менеджер_-_dnf.md)

```
dnf
dnf install
dnf download
dnf deplist
dnf repolist
dnf info
dnf makecache
dnf search
dnf remove
dnf check-upgrade
dnf upgrade
dnf needs-restarting
dnf provides
dnf grouplist
dnf groupinfo
dnf groupinstall
dnf module
dnf module list
dnf module info
dnf module install
dnf history
dnf history info
dnf history undo
dnf history redo
dnf help
rpm --scripts
rpm -p
rpm -i
rpm -q
rpm -l
rpm -a
rpm --import
ldd
cpio
rpm2cpio
```

#### [48. Восстановление доступа](../48/48._Восстановление_доступа.md)

```
load_policy
chroot
```

#### [49. Виртуальная память, swap](../49/49._Виртуальная_память,_swap.md)

```
free -m
dd
mkswap
swapon
swapoff
sysctl
```

#### [50. Планировщик процессов](../50/50._Планировщик_процессов.md)

```
chrt
chrt -p
chrt -m
chrt -f
chrt -r
chrt -o
```

#### [51. Оптимизация производительности - tuned](../51/51._Оптимизация_производительности_-_tuned.md)

```
tuned-adm
tuned-adm list
tuned-adm active
tuned-adm recommend
tuned-adm profile
tuned-adm verify
tuned-adm off
```

#### [52. Управление многоуровневым хранилищем - stratis](../52/52._Управление_многоуровневым_хранилищем_-_stratis.md)

```
stratis
stratis pool
stratis pool create
stratis pool list
stratis pool init-cache
stratis pool add-data
stratis blockdev list
stratis filesystem create
stratis filesystem list
stratis filesystem destroy
stratis filesystem rename
```

#### [54. Настройка времени](../54/54._Настройка_времени.md)

```
hwclock
hwclock -s
timedatectl
timedatectl set-local-rtc
timedatectl list-timezones
timedatectl set-timezone
chronyc sources
firewall-cmd --add-service
```

#### [55. Работа с IPv6](../55/55._Работа_с_IPv6.md)

```
firewall-cmd --add-protocol
ip -6
traceroute -6
```

#### [56. Передача файлов по сети](../56/56._Передача_файлов_по_сети.md)

```
scp
scp -r
scp -C
rsync
rsync -a
rsync -v
rsync -z
rsync -P
```

#### [57. Сетевые файловые системы - NFS](../57/57._Сетевые_файловые_системы_-_NFS.md)

```
exportfs
exportfs -a
exportfs -v
exportfs -s
showmount
showmount -e
umount -f
umount -l
```

#### [58. Сетевые файловые системы - SMB](../58/58._Сетевые_файловые_системы_-_SMB.md)

```
testparm
smbpasswd
smbpasswd -a
smbclient -L
```

#### [59. Автоматическое монтирование - Autofs](../59/59._Автоматическое_монтирование_-_Autofs.md)

```
hostnamectl
ipa-client-install
```

#### [63. Работа с podman](../63/63._Работа_с_podman.md)

```
podman
podman search
podman pull
podman images
podman run
podman ps
podman logs
podman exec
podman tag
podman push
podman image
skopeo copy
podman stop
podman start
podman login
podman generate
systemctl --user
loginctl enable-linger
firewall-cmd --add-forward-port
```

#### [64. Про сертификацию RHCSA](../64/64._Про_сертификацию_RHCSA.md)

```
shutdown now
poweroff
systemctl poweroff
reboot
star
tar --selinux
```
