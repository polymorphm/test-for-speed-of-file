test-for-speed-of-file
======================

``test-for-speed-of-file`` is tiny utility for speed measuring of
file reading or writing.


Status
------

Developer version (git master branch).


Usage Example
-------------

Write speed measuring of SD (memory card) with GNU/Linux file system implementation:

    $ sudo mount /dev/disk/by-id/usb-Multiple_Card_Reader_058F63666433-0\:0 /mnt
    FUSE exfat 1.0.1
    
    $ sudo ./test-for-speed-of-file --write-test --file=/mnt/test_file.bin --size=5000
    preparing data...
    preparing data: done
    testing...
    testing: done
    worse time per 1MB:
    0 days 0 seconds 303196 microseconds
    0 days 0 seconds 293084 microseconds
    0 days 0 seconds 292808 microseconds
    0 days 0 seconds 289245 microseconds
    0 days 0 seconds 272668 microseconds
    0 days 0 seconds 270624 microseconds
    0 days 0 seconds 269755 microseconds
    0 days 0 seconds 257012 microseconds
    0 days 0 seconds 239566 microseconds
    0 days 0 seconds 236666 microseconds
    0 days 0 seconds 236110 microseconds
    0 days 0 seconds 232797 microseconds
    0 days 0 seconds 226115 microseconds
    0 days 0 seconds 223716 microseconds
    0 days 0 seconds 213383 microseconds
    0 days 0 seconds 213382 microseconds
    0 days 0 seconds 213176 microseconds
    0 days 0 seconds 213171 microseconds
    0 days 0 seconds 213159 microseconds
    0 days 0 seconds 213146 microseconds
    worse time per 10MB:
    0 days 2 seconds 708218 microseconds
    0 days 2 seconds 25782 microseconds
    0 days 1 seconds 998808 microseconds
    0 days 1 seconds 932301 microseconds
    0 days 1 seconds 886082 microseconds
    0 days 1 seconds 742142 microseconds
    0 days 1 seconds 718967 microseconds
    0 days 1 seconds 688939 microseconds
    0 days 1 seconds 648769 microseconds
    0 days 1 seconds 608733 microseconds
    0 days 1 seconds 601803 microseconds
    0 days 1 seconds 599027 microseconds
    0 days 1 seconds 535730 microseconds
    0 days 1 seconds 528413 microseconds
    0 days 1 seconds 499139 microseconds
    0 days 1 seconds 499000 microseconds
    0 days 1 seconds 495677 microseconds
    0 days 1 seconds 448483 microseconds
    0 days 1 seconds 438481 microseconds
    0 days 1 seconds 432132 microseconds
    worse time per 100MB:
    0 days 17 seconds 309413 microseconds
    0 days 11 seconds 982987 microseconds
    0 days 11 seconds 771497 microseconds
    0 days 11 seconds 758990 microseconds
    0 days 11 seconds 726788 microseconds
    0 days 11 seconds 538764 microseconds
    0 days 11 seconds 497897 microseconds
    0 days 11 seconds 480967 microseconds
    0 days 11 seconds 395397 microseconds
    0 days 11 seconds 361988 microseconds
    0 days 11 seconds 321591 microseconds
    0 days 11 seconds 275554 microseconds
    0 days 11 seconds 141126 microseconds
    0 days 10 seconds 758393 microseconds
    0 days 10 seconds 594748 microseconds
    0 days 10 seconds 577715 microseconds
    0 days 10 seconds 534256 microseconds
    0 days 10 seconds 454467 microseconds
    0 days 10 seconds 407499 microseconds
    0 days 10 seconds 337835 microseconds
    worse time per 1000MB:
    0 days 108 seconds 875172 microseconds
    0 days 106 seconds 6623 microseconds
    0 days 104 seconds 834288 microseconds
    0 days 101 seconds 446594 microseconds
    0 days 32 seconds 345572 microseconds
    
    $ 
