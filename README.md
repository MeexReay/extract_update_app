splitupdate (formerly split_updata.pl)
===============

Improved tool for splitting UPDATE.APP for Huawei phones

To extract execute:
```
./splitupdate UPDATE.APP
```

The img files will be extracted in the output/ folder.

To split crc.img for huawei_crc_check:

```
./splitcrc
```

To generate \<image_file\>_crc for huawei_crc_check:
```
./generatecrc16 <image_file> [image_file] ...
```
