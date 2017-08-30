# error
Error in `python': free(): invalid pointer: 0x00007f394afd9050 ***
sudo apt-get install libtcmalloc-minimal4
export LD_PRELOAD="/usr/lib/libtcmalloc_minimal.so.4"
Fixes the error.
