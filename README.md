![Bash CI](https://github.com/pforret/baShrinqDB/workflows/Bash%20CI/badge.svg) 
![Shellcheck CI](https://github.com/pforret/baShrinqDB/workflows/Shellcheck%20CI/badge.svg)
![version](https://img.shields.io/github/v/release/pforret/baShrinqDB?include_prereleases)
![activity](https://img.shields.io/github/commit-activity/m/pforret/baShrinqDB)
![license](https://img.shields.io/github/license/pforret/baShrinqDB)
![repo size](https://img.shields.io/github/repo-size/pforret/bash-boilerplate)

### baShrinqDB.sh

Export all your mySQL databases to files on disk, for backup or migration purposes

### Usage

    Usage: baShrinqDB.sh [-h] [-q] [-v] [-f] [-l <logd>] [-t <tmpd>] [-d <dbserver>] [-u <user>] [-p <pass>] [-i <include>] [-x <exclude>] <action> <output>
    Flags, options and parameters:
        -h|--help      : [flag] show usage [default: off]
        -q|--quiet     : [flag] no output [default: off]
        -v|--verbose   : [flag] output more [default: off]
        -f|--force     : [flag] do not ask for confirmation (always yes) [default: off]
        -l|--logd <val>: [optn] folder for log files   [default: log]
        -t|--tmpd <val>: [optn] folder for temp files  [default: .tmp]
        -d|--dbserver <val>: [optn] Database Server (mySQL/MariaDB)  [default: localhost]
        -u|--user <val>: [optn] USER to use  [default: pforret]
        -p|--pass <val>: [secr] password to use
        -i|--include <val>: [optn] databases to export/import  [default: *]
        -x|--exclude <val>: [optn] databases NOT to export/import  [default: -]
        <action>  : [parameter] action to perform: list/backup/restore
        <output>  : [parameter] backup folder


### Inspiration

* [ma.ttias.be: MySQL back-up: take a mysqldump with each database in its own SQL File](https://ma.ttias.be/mysql-back-up-take-a-mysqldump-with-each-database-in-its-own-sql-file/)
