# Draft post: the Apriso database recovery (for Featured)

Outline only. Fill the bracketed details, keep it under 1,300 characters, no more than one em dash.

```
Our 2-node storage cluster failed to resync after a reboot. The volume metadata was gone. So was the plant's MES database.

No usable backup. The vendor could not help with raw disk.

What was left: one intact SQL Server MDF, scattered across the disk with no file table pointing to it.

So I went page by page.

1. Found the boot page by its signature and repaired it in a hex editor.
2. Walked the page chain and wrote a Python script to merge the MDF fragments back into one file.
3. Rebuilt the transaction log and attached the database.

[fill: hours from failure to ONLINE]. [fill: rows or days of production data] recovered. A company-wide incident became a minor disruption.

Three things I would tell anyone running a plant on a 2-node S2D cluster:

- Two nodes is not high availability. It is a coin flip with extra steps.
- Test the restore, not the backup. Ours had not been tested since 2022.
- Know your file format. SQL Server pages are 8 KB with a documented header. That is enough to put a database back together.

What is the oldest system your plant still depends on?
```
