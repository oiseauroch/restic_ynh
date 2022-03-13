## Overview

A [Restic](https://restic.net/) package for YunoHost (heavily inspired by [the Borg package](https://github.com/YunoHost-Apps/borg_ynh/)).

Restic is a backup tool that can make local and remote backups.
This package uses restic to make backups to a sftp server.
The package does not handle local backups yet but you can work around that by using the local sftp server as target server (see my comment [here](https://forum.yunohost.org/t/sauvegarde-yunohost-avec-restic/10275/33)).
