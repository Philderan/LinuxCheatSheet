# LinuxCheatSheet

## SCP y TAR

### TEST Server Insumos Legacy
En .252:

> scp -P 22855 crucijuegos@10.0.7.221:/opt/dumps/crm-backup-18122023.tar.gz /var/www/legacy-insumos-docker/bbdd/crm-backup-18122023.tar.gz
> tar -xvf crm-backup-18122023.tar.gz
> mv crm-backup-18122023.sql crm_optimizado.sql
