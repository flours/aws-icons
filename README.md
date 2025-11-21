# aws-icons

AWS構成図を作ってもらうためのアイコン集です。
figma Makeからアクセスすることを前提としています。

## Figma Makeへの指示

- VPC枠線は `Architecture-Group-Icons_02072025/Virtual-private-cloud-VPC_32.svg` を使う
- 矢印はFigma標準の線を使い、Stroke 2px・角丸・矢印ヘッドは終端のみ（Arrow）・色は `#111827` / 80% 不透明度で描画してもらう
- 必須リソースの場所
  - VPC本体: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_Virtual-private-cloud-VPC_48.svg`
  - ルートテーブル: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-Route-53_Route-Table_48.svg`
  - インターネットゲートウェイ: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_Internet-Gateway_48.svg`
  - NATゲートウェイ: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_NAT-Gateway_48.svg`
  - ルーター: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_Router_48.svg`
  - ENI: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_Elastic-Network-Interface_48.svg`
  - VPCエンドポイント: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_Endpoints_48.svg`
  - サブネットの専用アイコンは未収録（必要なら追加して利用）
