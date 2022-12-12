# ZFS_scripts
# Initiated: 2022-04-11

ZFS Filesystem & Snapshot management
Creation & Management of Snapshots
 -  Frequent (15-min) :: keep  96 (1 day)
 -  Hourly            :: keep 168 (1 week)
 -  Daily             :: keep  90 (3 months)
 -  Weekly            :: keep  52 (1 year)
 -  Monthly           :: keep  24 (2 years)
 -  Annual            :: keep  10 (10 years)

Self enumerates your zfs datasets and snapshots them all on a schedule. All snapshots are date-stamped within the filename for easy finding. Programs provided for automatically purging old, listing available, and manual deletions.

```
 ZFS Snapshot list
  # Dataset             	 15Min Hourly  Daily Weekly  Mthly Annual
 ========================================================================
  0 Prod0               	     5      1      0      0      0      0
  1 Prod0/HOMEDIRS          	     5      1      0      0      0      0
  2 Prodd/GROUPSHARES        	     5      1      0      0      0      0
  3 Prod0/ESXi_DS_01      	     5      1      0      0      0      0
  4 Prod0/ESXi_DS_02      	     5      1      0      0      0      0
  5 Prod0/ESXi_ISO        	     5      1      0      0      0      0
  6 Sandbox0            	     5      1      0      0      0      0
 ========================================================================
				    35      7      0      0      0      0
 ========================================================================
	Grand Total		    42
```

