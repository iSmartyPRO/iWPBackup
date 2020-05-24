# Wordpress Backup Script

This bash script is simplify your life backup process of Wordpress site from CLI.

It's automatically check is wp-config.php file exist in current directory.
If backups folder not exist - It's create backups folder in up-parent directory.
Then script will archive current directory by tar command and then will backup Wordpress MySql Database.

## How to install

Put ibackup script file to bin folder: 
```
mv iWPBackup ~/bin/
```

Apply required permission: 
```
chmod 755 ~/bin/iWPBackup
```

## How to use?

Go to Wordpress folder and use following command:
```
iWPBackup
```

Sample of output:
```
================================================================
Backup folder is created
================================================================
Started files archiving - public_html_2020-05-24_23-13-33.tar.gz
Started MySQL Backup - 2020-05-24_23-13-33.sql
Files size   : 297 Mb (312015405 bytes)
Database Size: 128 Mb (134365845 bytes)
Done!
```
