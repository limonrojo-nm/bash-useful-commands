# NM Bash Useful Commands

This is a bash script to be imported in other scripts to easily add styles and other useful features

1. Place `_lib.sh` where is fine to you.
2. Import it in your new script using:
   ```bash
   #!/bin/bash
   my_dir="$(dirname "$0")"
   source $my_dir/_lib.sh
   ```
3. Then, all the variables and functions will be available
