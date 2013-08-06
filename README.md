test-for-speed-of-file
======================

``test-for-speed-of-file`` is tiny utility for speed measuring of
file reading or writing.

Status
------

Version (this branch) for developer.

Usage Example
-------------

Write speed measuring of SD (memory card) with GNU/Linux file system implementation:

    $ sudo mount /dev/disk/by-id/usb-Multiple_Card_Reader_058F63666433-0\:0 /mnt
    
    $ sudo ./test-for-speed-of-file --write-test --file=/mnt/test_file.bin --size=5000
