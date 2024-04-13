刷CDT
cdt-Arthur_1G_DDR3.rar

web页面上传到 /tmp/upload/
刷入 CDT分区
blkid |grep CDT
cd /tmp/upload/
dd if=cdt-Arthur_1G_DDR3.bin of=/dev/mmcblk0p10
dd if=cdt-Arthur_1G_DDR3.bin of=/dev/mmcblk0p11
