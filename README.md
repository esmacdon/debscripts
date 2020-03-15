# debscripts
Scripts that I use for nvidia-xrun

linux	/boot/vmlinuz-5.4.0-4-amd64 root=UUID=1353a94f-c209-4f10-87b7-8b75cb26cc99 acpi_osi=! acpi_osi="Windows 2009" ro  quiet

resume should go in /lib/systemd/system-sleep/
  do chown root and chmod a+rx

nvpstate should go in /etc/sudoers.d/*'
  make sure user is in group pstate
