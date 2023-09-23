# Docker Alpine Sample

Alpine container with *ssh* access to *root* user (Docker)

### Run
- Run `./configure.sh` (or generate ssh key into `key` folder manually)
- Update `.env` with own values
- Run `./up.sh`

### Usage
- Run `ssh -p 2222 -i ./key/key -o IdentitiesOnly=yes root@localhost 'whoami`

### Notes
- For clean Docker stopped resources and up again, run `reup.sh`
