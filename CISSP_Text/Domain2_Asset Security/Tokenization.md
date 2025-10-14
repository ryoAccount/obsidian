
Tokenization is a technology that replaces highly sensitive information with a random value (token). 
Using tokens in everyday interactions reduces the risk of information leakage.

トークン化は、機密性の高い情報をランダムな値（トークン）に置き換える技術です。普段のやり取りではトークンを使用することで、情報漏えいのリスクを低減します。



### 🧩 それぞれの定義と違い

| 手法                   | 定義                                  | 識別性 | 可逆性          | 主な用途                   |
| -------------------- | ----------------------------------- | --- | ------------ | ---------------------- |
| [[Tokenization]]     | 元のデータをランダムな「トークン」に置き換え、マッピングテーブルで管理 | 不可  | ✅（マッピングがあれば） | クレジットカード番号などのPCI DSS対応 |
| [[Anonymization]]    | 個人を特定できないようにデータを完全に加工               | 不可  | ❌（元に戻せない）    | 統計分析、GDPRでの「非個人データ」化   |
| [[Data Masking]]     | 表示上のデータを隠す（例：****1234）              | 一部可 | ❌（通常は不可）     | テスト環境、開発環境でのデータ利用      |
| [[Pseudonymisation]] | 本人識別情報を仮名に置き換え、元データとの対応表を保持         | 可   | ✅（対応表があれば）   | GDPRでの「個人データ」扱い、分析用途   |
