# shsh
Miscellaneous shell scripts, preferable Bourne classic syntax

path/path.sh - work with $PATH environment variable:
 - list elements
 - list command which will be invoked
 - list all commands with name given (which shows only 1st)

commdir.sh - 'comm' wrapper able compare 2 directories
 - automatic (inline) produce listing of both directories
  
rs2.sh - rsync wrapper for daily mirroring/backup
 - implements model try-check-do, intended for mirroring
   of very significant working data, where CMS (git or mercurial) is not appropriate -
   photoarchives, home directory, document collections, etc.
   
ddwipe.sh - wrapper for dd
 - safely (real) destroy confidential data
 - test new flash media for real write speed

rpm_ls/deb_ls/lsrpm/lsdeb - tool to manipulate with large garbaged collections
  of binary packages in popular format (.rpm/.deb)


