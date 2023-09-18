# kvm-cold-backup
kvm cold backup shell script, naive but always works.

```bash
$ ./virt-backup 
Usage: ./virt-backup [options]
Options:
  -b, --backup <domain> <backup_path>    Backup and package the KVM virtual machine.
  -r, --restore <backup_file_path>       Restore the KVM virtual machine from a backup file.
  -h, --help                             Show this help message.
```

