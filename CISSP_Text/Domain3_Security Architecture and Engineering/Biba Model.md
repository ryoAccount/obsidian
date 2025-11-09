
The Biba Model is a state transition system describing a set of access control rules designed to ensure data **integrity**. 

- Simple Integrity Property: Cannot read down (cannot use information from a lower integrity level)
- Star-Integrity Property: Cannot write up (cannot contaminate information from a higher integrity level)

Bibaモデルは、データの**完全性**を確保するために設計された一連のアクセス制御ルールを記述した状態遷移システムです。

- 単純完全性属性 : read downできない（完全性が低い層の情報を使えない）
- スター属性 : write upできない（完全性が高い層の情報を汚染できない）


![[Pasted image 20251109102552.png]]

---
