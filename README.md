# NTFS-Compression
Use NTFS-Compression WITHOUT calling conpact.exe, a pure powershell method. Solves following issues:
 - Can handle filenames with spaces
 - Can handle filenames with "&" character
 - Can handle unicode filenamed from, for example, Japan.

The example script NTFS-compact-uncompact.ps1 is tailored to compress log files more than three days old.
