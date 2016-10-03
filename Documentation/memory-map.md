Memory Map
==========

DRAM (0x3ffe8000 - 3fffbfff)
-----------------------------

```
0x3ffe8000 - 0x3fff3fff: firmware (48KB)
0x3fff4000 - 0x3fff6fff: firmware heap (12KB)
0x3fff7000 - 0x3fff8fff: Base OS (8KB)
0x3fff9000 - 0x3fffbfff: Base OS / used in do_update() (12KB)
```

IRAM (0x40100000 - 0x40107fff)
------------------------------

```
0x40100000 - 0x401059ff: firmware (32KB)
0x40105a00 - 0x40107fff: Base OS (9.5KB)
```

IROM
----

```
0x40201010 - 0x4026b000: firmware (423KB)
```
