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

> FS Snapshot list
>  # Dataset             	 15Min Hourly  Daily Weekly  Mthly Annual
> ========================================================================
>  0 Pool0               	     5      1      0      0      0      0
>  1 Pool0/HOME          	     5      1      0      0      0      0
>  2 Pool0/SHARED        	     5      1      0      0      0      0
>  3 Pool0/VM_DS_01      	     5      1      0      0      0      0
>  4 Pool0/VM_DS_02      	     5      1      0      0      0      0
>  5 Pool0/VM_ISO        	     5      1      0      0      0      0
>  6 sandbox1            	     5      1      0      0      0      0
> ========================================================================
>				    35      7      0      0      0      0
> ========================================================================
>	Grand Total		    42

