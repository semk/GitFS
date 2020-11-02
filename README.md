# GitFS
A FUSE based filesystem for using Git(Hub) as a storage.

# Usage
To mount already existing git repo, run

  python gitfs.py git@github.com:<username>/<repo> <branch> <local_repo_dir> <mount_point>

To unmount use

  fusermount -u <mount_point>

Licensed under FreeBSD license
