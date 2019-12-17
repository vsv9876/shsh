# shsh
Miscellaneous shell scripts

*path/path.sh - work with $PATH environment variable:
 - list elements
 - list command which will be invoked
 - list all commands with name given (which shows only 1st)

*commdir.sh - 'comm' wrapper able compare 2 directories
 - automatic (inline) produce listing of both directories
  
*rs2.sh - rsync wrapper for daily mirroring/backup
 - implements model try-check-do, intended for mirroring
   of very significant working data, where CMS (git or mercurial) is not appropriate -
   photoarchives, home directory, document collections, etc.
   
*ddwipe.sh - wrapper for dd
 - safely (real) destroy confidential data
 - test new flash media for real write speed

*lsrpm/lsdeb - tool to manipulate with large garbaged collections
  of installation packages in popular format (.rpm/.deb)

*bren - Batch REName - script to organize Your photo archive
 - looking for a EXIF data, and choose new file names
 - create directories
 - find duplicates, able copy/link/rename/remove files
 - prevent extra writing/formatting source flash media

