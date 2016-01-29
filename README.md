# udevil-bindfs
### Wraps udevil and bindfs to mount filesystems with full user privileges

Requires udevil >= 0.4.4 and bindfs >= 1.13.0. May work with earlier versions, 
but this is untested.

The two scripts can be used as drop-in replacements for `udevil mount` and 
`udevil umount`, except where unmount options are required 
(see `udevil --help`).
