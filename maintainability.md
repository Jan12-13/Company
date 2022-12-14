---
marp: true
theme: future
footer: 　
header:  header
---
# maintabilityを小さくする
---
## maintainabilityとは
- 日本語では保守性
- [ISO/IEC 25010:2011](https://iso25000.com/index.php/en/iso-25000-standards/iso-25010)によって以下のように定義される。
- 製品やシステムを改良、修正、または環境や要求の変化に適応させるために、どの程度有効かつ効率的に変更できるかを表している。この特性は、以下の副特性から構成される。
  - モジュール性：独立具合？変更を加えても他の要素への影響が少ない。
  - 再利用性：他のシステムでも利用できる。
  - 分析可能性：分析のしやすさ。故障の原因であったりを診断特定しやすかったり。
  - 修正可能性：不具合や既存の製品の品質を低下させることなく修正できる。
  - 試験可能性：試験基準が満たされているか判断するために試験を行うことができる。

---
## 保守性が低い
- 疎結合でない
  - 影響が広範囲に及ぶソフトウェア構成。
- 可読性が低い
  - 他者が理解しにくい。
- トレーサビリティがない
  - 仕様書や設計書と整合が取れない。
- 機能分担がない
  - 処理の役割がわからない。統一性がない。
---
## 保守性の高め方

---
## 参考文献
静的解析でソースコードの保守性を計測する
https://blog.yagipy.me/analyze-maintainability-index
ベテランエンジニアが教える、ソフトウェア保守性を高める具体的な方法
https://blog.secondselection.com/column/software-maintainability/