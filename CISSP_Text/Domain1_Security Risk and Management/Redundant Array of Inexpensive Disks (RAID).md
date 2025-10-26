
RAID levels use multiple hard drives to provide data redundancy and protection against single or multiple drive failures, with the specific level of protection determined by the chosen RAID level.

RAIDレベルは複数のハードディスクドライブを使用することでデータ冗長性を確保し、単一または複数のドライブ障害からデータを保護します。具体的な保護レベルは、選択したRAIDレベルによって異なります。

---

- RAID 0 (Striping): 
	- Data is split into "stripes" and distributed across multiple drives, so read and write operations can occur simultaneously. 
- RAID 1 (Mirroring): 
	- Data is duplicated and written to two separate disks, creating a mirror image. 
- RAID 5 (Striping with Parity): 
	- Data is striped across multiple disks, and a single parity block is calculated and distributed among the drives. 
- RAID 6 (Striping with Double Parity): 
	- Like RAID 5, but it uses two independent parity blocks distributed across the drives, allowing it to tolerate two drive failures. 

- RAID 0（ストライピング）：
	- データを複数のディスクに分割して分散配置することで、読み書き処理を同時に実行できます。
- RAID 1（ミラーリング）：
	- データを2つのディスクに複製して保存することで、データの冗長性を確保します。
- RAID 5（パリティ付きストライピング）：
	- データを複数のディスクに分散配置し、パリティデータを計算して各ディスクに分散配置することで、1台のディスク故障に耐えることができます。
- RAID 6（二重パリティ付きストライピング）：
	- RAID 5と同様ですが、2つの独立したパリティブロックを各ディスクに分散配置することで、2台のディスク故障に耐えることができます。

---

RAID2, RAID3, and RAID4 are practically no longer used today.

現在では実質的に RAID2、RAID3、RAID4 は使用されていない。

![[Pasted image 20251027053851.png]]