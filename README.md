ARM ARCH LINUX repos
====================

* /etc/pacman.conf
```
[cloud-source]
Server = https://github.com/the-cloud-source/arch-linux/releases/download/$arch
```

* Import and Sign Key
```
pacman-key --recv-keys 4666318FD4EAC6130AE21DAE608CEB758872E058 && \
pacman-key --lsign-key 4666318FD4EAC6130AE21DAE608CEB758872E058
```
