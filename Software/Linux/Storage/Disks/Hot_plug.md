# Hot plug
Created Donnerstag 18 August 2022

The device can automatically apear in the device list if not scan the bus:
# echo "- - -" > tee /sys/class/scsi_host/host<Number>/scan

OPTIONAL: [Reload](../Partition/Reload_partition_table.md) partition table.
