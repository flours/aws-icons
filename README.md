# aws-icons

AWS構成図を作ってもらうためのアイコン集です。
figma Makeからアクセスすることを前提としています。

## Architecture-Group-Icons（枠線用アイコン）

以下のアイコンは構成図の枠線として使用します。すべて40x40pxの正方形アイコンで、角は丸くない矩形です。

### ネットワーク関連
- **VPC枠線**: `Architecture-Group-Icons_02072025/Virtual-private-cloud-VPC_32.svg` - 紫色 `#8C4FFF`
- **Public Subnet枠線**: `Architecture-Group-Icons_02072025/Public-subnet_32.svg` - 緑色 `#7AA116`
- **Private Subnet枠線**: `Architecture-Group-Icons_02072025/Private-subnet_32.svg` - 青緑色 `#00A4A6`
- **Region枠線**: `Architecture-Group-Icons_02072025/Region_32.svg` - 青緑色 `#00A4A6`
- **AWS Cloud枠線**: `Architecture-Group-Icons_02072025/AWS-Cloud_32.svg` - ダークグレー `#242F3E`
- **AWS Account枠線**: `Architecture-Group-Icons_02072025/AWS-Account_32.svg` - ピンク `#E7157B`

### コンピューティング関連
- **Auto Scaling Group枠線**: `Architecture-Group-Icons_02072025/Auto-Scaling-group_32.svg` - オレンジ `#ED7100`
- **EC2 Instance Contents枠線**: `Architecture-Group-Icons_02072025/EC2-instance-contents_32.svg` - オレンジ `#ED7100`
- **Spot Fleet枠線**: `Architecture-Group-Icons_02072025/Spot-Fleet_32.svg` - オレンジ `#ED7100`
- **Server Contents枠線**: `Architecture-Group-Icons_02072025/Server-contents_32.svg` - グレー `#7D8998`
- **Corporate Data Center枠線**: `Architecture-Group-Icons_02072025/Corporate-data-center_32.svg` - グレー `#7D8998`

### IoT関連
- **AWS IoT Greengrass Deployment枠線**: `Architecture-Group-Icons_02072025/AWS-IoT-Greengrass-Deployment_32.svg` - 緑色 `#7AA116`

## Figma Makeへの指示

### 枠線の描画方法
各種枠線は以下のように描画する：
- **Rectangle（矩形）を使用**
- **Fill（塗りつぶし）**: なし（透明）
- **Stroke（線）**: 2px、上記の各アイコンと同じ色を使用
- **Corner Radius（角丸）**: 0px（角を丸くしない）
- **線のスタイル**: 実線

例：
- VPC枠線: Rectangle、Stroke 2px、色 `#8C4FFF`、Fill なし、Corner Radius 0px
- Public Subnet枠線: Rectangle、Stroke 2px、色 `#7AA116`、Fill なし、Corner Radius 0px
- Private Subnet枠線: Rectangle、Stroke 2px、色 `#00A4A6`、Fill なし、Corner Radius 0px

### 矢印の描画方法
- Figma標準の線を使用
- Stroke 2px
- 角丸
- 矢印ヘッドは終端のみ（Arrow）
- 色は `#111827` / 80% 不透明度

### 必須リソースの場所
- VPC本体: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_Virtual-private-cloud-VPC_48.svg`
- ルートテーブル: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-Route-53_Route-Table_48.svg`
- インターネットゲートウェイ: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_Internet-Gateway_48.svg`
- NATゲートウェイ: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_NAT-Gateway_48.svg`
- ルーター: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_Router_48.svg`
- ENI: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_Elastic-Network-Interface_48.svg`
- VPCエンドポイント: `Resource-Icons_02072025/Res_Networking-Content-Delivery/Res_Amazon-VPC_Endpoints_48.svg`

## 主要なAWSサービス100選

### Compute（コンピューティング）
1. **Amazon EC2**: `Architecture-Service-Icons_02072025/Arch_Compute/48/Arch_Amazon-EC2_48.svg`
2. **AWS Lambda**: `Architecture-Service-Icons_02072025/Arch_Compute/48/Arch_AWS-Lambda_48.svg`
3. **Amazon ECS**: `Architecture-Service-Icons_02072025/Arch_Containers/48/Arch_Amazon-Elastic-Container-Service_48.svg`
4. **Amazon EKS**: `Architecture-Service-Icons_02072025/Arch_Containers/48/Arch_Amazon-Elastic-Kubernetes-Service_48.svg`
5. **AWS Fargate**: `Architecture-Service-Icons_02072025/Arch_Containers/48/Arch_AWS-Fargate_48.svg`
6. **AWS Batch**: `Architecture-Service-Icons_02072025/Arch_Compute/48/Arch_AWS-Batch_48.svg`
7. **AWS Elastic Beanstalk**: `Architecture-Service-Icons_02072025/Arch_Compute/48/Arch_AWS-Elastic-Beanstalk_48.svg`
8. **Amazon Lightsail**: `Architecture-Service-Icons_02072025/Arch_Compute/48/Arch_Amazon-Lightsail_48.svg`
9. **Amazon EC2 Auto Scaling**: `Architecture-Service-Icons_02072025/Arch_Compute/48/Arch_Amazon-EC2-Auto-Scaling_48.svg`
10. **AWS App Runner**: `Architecture-Service-Icons_02072025/Arch_Compute/48/Arch_AWS-App-Runner_48.svg`

### Storage（ストレージ）
11. **Amazon S3**: `Architecture-Service-Icons_02072025/Arch_Storage/48/Arch_Amazon-Simple-Storage-Service_48.svg`
12. **Amazon EBS**: `Architecture-Service-Icons_02072025/Arch_Storage/48/Arch_Amazon-Elastic-Block-Store_48.svg`
13. **Amazon EFS**: `Architecture-Service-Icons_02072025/Arch_Storage/48/Arch_Amazon-EFS_48.svg`
14. **Amazon S3 Glacier**: `Architecture-Service-Icons_02072025/Arch_Storage/48/Arch_Amazon-Simple-Storage-Service-Glacier_48.svg`
15. **AWS Storage Gateway**: `Architecture-Service-Icons_02072025/Arch_Storage/48/Arch_AWS-Storage-Gateway_48.svg`
16. **Amazon FSx**: `Architecture-Service-Icons_02072025/Arch_Storage/48/Arch_Amazon-FSx_48.svg`
17. **AWS Backup**: `Architecture-Service-Icons_02072025/Arch_Storage/48/Arch_AWS-Backup_48.svg`

### Database（データベース）
18. **Amazon RDS**: `Architecture-Service-Icons_02072025/Arch_Database/48/Arch_Amazon-RDS_48.svg`
19. **Amazon DynamoDB**: `Architecture-Service-Icons_02072025/Arch_Database/48/Arch_Amazon-DynamoDB_48.svg`
20. **Amazon Aurora**: `Architecture-Service-Icons_02072025/Arch_Database/48/Arch_Amazon-Aurora_48.svg`
21. **Amazon Redshift**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_Amazon-Redshift_48.svg`
22. **Amazon ElastiCache**: `Architecture-Service-Icons_02072025/Arch_Database/48/Arch_Amazon-ElastiCache_48.svg`
23. **Amazon Neptune**: `Architecture-Service-Icons_02072025/Arch_Database/48/Arch_Amazon-Neptune_48.svg`
24. **Amazon DocumentDB**: `Architecture-Service-Icons_02072025/Arch_Database/48/Arch_Amazon-DocumentDB_48.svg`
25. **Amazon Keyspaces**: `Architecture-Service-Icons_02072025/Arch_Database/48/Arch_Amazon-Keyspaces_48.svg`
26. **Amazon MemoryDB**: `Architecture-Service-Icons_02072025/Arch_Database/48/Arch_Amazon-MemoryDB_48.svg`
27. **Amazon Timestream**: `Architecture-Service-Icons_02072025/Arch_Database/48/Arch_Amazon-Timestream_48.svg`

### Networking & Content Delivery（ネットワーキング）
28. **Amazon VPC**: `Architecture-Service-Icons_02072025/Arch_Networking-Content-Delivery/48/Arch_Amazon-Virtual-Private-Cloud_48.svg`
29. **Amazon CloudFront**: `Architecture-Service-Icons_02072025/Arch_Networking-Content-Delivery/48/Arch_Amazon-CloudFront_48.svg`
30. **Amazon Route 53**: `Architecture-Service-Icons_02072025/Arch_Networking-Content-Delivery/48/Arch_Amazon-Route-53_48.svg`
31. **Amazon API Gateway**: `Architecture-Service-Icons_02072025/Arch_App-Integration/48/Arch_Amazon-API-Gateway_48.svg`
32. **AWS Direct Connect**: `Architecture-Service-Icons_02072025/Arch_Networking-Content-Delivery/48/Arch_AWS-Direct-Connect_48.svg`
33. **AWS Transit Gateway**: `Architecture-Service-Icons_02072025/Arch_Networking-Content-Delivery/48/Arch_AWS-Transit-Gateway_48.svg`
34. **Elastic Load Balancing**: `Architecture-Service-Icons_02072025/Arch_Networking-Content-Delivery/48/Arch_Elastic-Load-Balancing_48.svg`
35. **AWS Global Accelerator**: `Architecture-Service-Icons_02072025/Arch_Networking-Content-Delivery/48/Arch_AWS-Global-Accelerator_48.svg`
36. **AWS VPN**: `Architecture-Service-Icons_02072025/Arch_Networking-Content-Delivery/48/Arch_AWS-Site-to-Site-VPN_48.svg`
37. **AWS PrivateLink**: `Architecture-Service-Icons_02072025/Arch_Networking-Content-Delivery/48/Arch_AWS-PrivateLink_48.svg`

### Security, Identity & Compliance（セキュリティ）
38. **AWS IAM**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_AWS-Identity-and-Access-Management_48.svg`
39. **AWS KMS**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_AWS-Key-Management-Service_48.svg`
40. **AWS Secrets Manager**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_AWS-Secrets-Manager_48.svg`
41. **AWS WAF**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_AWS-WAF_48.svg`
42. **AWS Shield**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_AWS-Shield_48.svg`
43. **Amazon GuardDuty**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_Amazon-GuardDuty_48.svg`
44. **AWS Security Hub**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_AWS-Security-Hub_48.svg`
45. **Amazon Macie**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_Amazon-Macie_48.svg`
46. **AWS Certificate Manager**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_AWS-Certificate-Manager_48.svg`
47. **Amazon Inspector**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_Amazon-Inspector_48.svg`
48. **AWS CloudHSM**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_AWS-CloudHSM_48.svg`

### Analytics（分析）
49. **Amazon Athena**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_Amazon-Athena_48.svg`
50. **Amazon EMR**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_Amazon-EMR_48.svg`
51. **Amazon Kinesis**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_Amazon-Kinesis_48.svg`
52. **Amazon QuickSight**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_Amazon-QuickSight_48.svg`
53. **AWS Glue**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_AWS-Glue_48.svg`
54. **Amazon OpenSearch Service**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_Amazon-OpenSearch-Service_48.svg`
55. **Amazon MSK**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_Amazon-Managed-Streaming-for-Apache-Kafka_48.svg`
56. **Amazon Data Firehose**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_Amazon-Data-Firehose_48.svg`
57. **AWS Lake Formation**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_AWS-Lake-Formation_48.svg`
58. **Amazon DataZone**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_Amazon-DataZone_48.svg`

### Machine Learning & AI（機械学習・AI）
59. **Amazon SageMaker**: `Architecture-Service-Icons_02072025/Arch_Analytics/48/Arch_Amazon-SageMaker_48.svg`
60. **Amazon Bedrock**: `Architecture-Service-Icons_02072025/Arch_Artificial-Intelligence/48/Arch_Amazon-Bedrock_48.svg`
61. **Amazon Rekognition**: `Architecture-Service-Icons_02072025/Arch_Artificial-Intelligence/48/Arch_Amazon-Rekognition_48.svg`
62. **Amazon Comprehend**: `Architecture-Service-Icons_02072025/Arch_Artificial-Intelligence/48/Arch_Amazon-Comprehend_48.svg`
63. **Amazon Transcribe**: `Architecture-Service-Icons_02072025/Arch_Artificial-Intelligence/48/Arch_Amazon-Transcribe_48.svg`
64. **Amazon Translate**: `Architecture-Service-Icons_02072025/Arch_Artificial-Intelligence/48/Arch_Amazon-Translate_48.svg`
65. **Amazon Polly**: `Architecture-Service-Icons_02072025/Arch_Artificial-Intelligence/48/Arch_Amazon-Polly_48.svg`
66. **Amazon Lex**: `Architecture-Service-Icons_02072025/Arch_Artificial-Intelligence/48/Arch_Amazon-Lex_48.svg`
67. **Amazon Textract**: `Architecture-Service-Icons_02072025/Arch_Artificial-Intelligence/48/Arch_Amazon-Textract_48.svg`
68. **Amazon Q**: `Architecture-Service-Icons_02072025/Arch_Artificial-Intelligence/48/Arch_Amazon-Q_48.svg`

### Developer Tools（開発者ツール）
69. **AWS CodeCommit**: `Architecture-Service-Icons_02072025/Arch_Developer-Tools/48/Arch_AWS-CodeCommit_48.svg`
70. **AWS CodeBuild**: `Architecture-Service-Icons_02072025/Arch_Developer-Tools/48/Arch_AWS-CodeBuild_48.svg`
71. **AWS CodeDeploy**: `Architecture-Service-Icons_02072025/Arch_Developer-Tools/48/Arch_AWS-CodeDeploy_48.svg`
72. **AWS CodePipeline**: `Architecture-Service-Icons_02072025/Arch_Developer-Tools/48/Arch_AWS-CodePipeline_48.svg`
73. **AWS Cloud9**: `Architecture-Service-Icons_02072025/Arch_Developer-Tools/48/Arch_AWS-Cloud9_48.svg`
74. **AWS X-Ray**: `Architecture-Service-Icons_02072025/Arch_Developer-Tools/48/Arch_AWS-X-Ray_48.svg`
75. **Amazon CodeGuru**: `Architecture-Service-Icons_02072025/Arch_Developer-Tools/48/Arch_Amazon-CodeGuru_48.svg`
76. **Amazon CodeWhisperer**: `Architecture-Service-Icons_02072025/Arch_Developer-Tools/48/Arch_Amazon-CodeWhisperer_48.svg`

### Management & Governance（管理・ガバナンス）
77. **Amazon CloudWatch**: `Architecture-Service-Icons_02072025/Arch_Management-Governance/48/Arch_Amazon-CloudWatch_48.svg`
78. **AWS CloudTrail**: `Architecture-Service-Icons_02072025/Arch_Management-Governance/48/Arch_AWS-CloudTrail_48.svg`
79. **AWS CloudFormation**: `Architecture-Service-Icons_02072025/Arch_Management-Governance/48/Arch_AWS-CloudFormation_48.svg`
80. **AWS Systems Manager**: `Architecture-Service-Icons_02072025/Arch_Management-Governance/48/Arch_AWS-Systems-Manager_48.svg`
81. **AWS Config**: `Architecture-Service-Icons_02072025/Arch_Management-Governance/48/Arch_AWS-Config_48.svg`
82. **AWS Auto Scaling**: `Architecture-Service-Icons_02072025/Arch_Management-Governance/48/Arch_AWS-Auto-Scaling_48.svg`
83. **AWS Organizations**: `Architecture-Service-Icons_02072025/Arch_Management-Governance/48/Arch_AWS-Organizations_48.svg`
84. **AWS Control Tower**: `Architecture-Service-Icons_02072025/Arch_Management-Governance/48/Arch_AWS-Control-Tower_48.svg`
85. **AWS Trusted Advisor**: `Architecture-Service-Icons_02072025/Arch_Management-Governance/48/Arch_AWS-Trusted-Advisor_48.svg`

### Application Integration（アプリケーション統合）
86. **Amazon SNS**: `Architecture-Service-Icons_02072025/Arch_App-Integration/48/Arch_Amazon-Simple-Notification-Service_48.svg`
87. **Amazon SQS**: `Architecture-Service-Icons_02072025/Arch_App-Integration/48/Arch_Amazon-Simple-Queue-Service_48.svg`
88. **Amazon EventBridge**: `Architecture-Service-Icons_02072025/Arch_App-Integration/48/Arch_Amazon-EventBridge_48.svg`
89. **AWS Step Functions**: `Architecture-Service-Icons_02072025/Arch_App-Integration/48/Arch_AWS-Step-Functions_48.svg`
90. **AWS AppSync**: `Architecture-Service-Icons_02072025/Arch_App-Integration/48/Arch_AWS-AppSync_48.svg`
91. **Amazon MQ**: `Architecture-Service-Icons_02072025/Arch_App-Integration/48/Arch_Amazon-MQ_48.svg`

### Containers（コンテナ）
92. **Amazon ECR**: `Architecture-Service-Icons_02072025/Arch_Containers/48/Arch_Amazon-Elastic-Container-Registry_48.svg`

### Migration & Modernization（移行・モダナイゼーション）
93. **AWS Database Migration Service**: `Architecture-Service-Icons_02072025/Arch_Migration-Modernization/48/Arch_AWS-Database-Migration-Service_48.svg`
94. **AWS Application Migration Service**: `Architecture-Service-Icons_02072025/Arch_Migration-Modernization/48/Arch_AWS-Application-Migration-Service_48.svg`
95. **AWS DataSync**: `Architecture-Service-Icons_02072025/Arch_Migration-Modernization/48/Arch_AWS-DataSync_48.svg`
96. **AWS Transfer Family**: `Architecture-Service-Icons_02072025/Arch_Migration-Modernization/48/Arch_AWS-Transfer-Family_48.svg`

### Front-End Web & Mobile（フロントエンド・モバイル）
97. **AWS Amplify**: `Architecture-Service-Icons_02072025/Arch_Front-End-Web-Mobile/48/Arch_AWS-Amplify_48.svg`
98. **Amazon Cognito**: `Architecture-Service-Icons_02072025/Arch_Security-Identity-Compliance/48/Arch_Amazon-Cognito_48.svg`

### Business Applications（ビジネスアプリケーション）
99. **Amazon SES**: `Architecture-Service-Icons_02072025/Arch_Business-Applications/48/Arch_Amazon-Simple-Email-Service_48.svg`
100. **Amazon Connect**: `Architecture-Service-Icons_02072025/Arch_Business-Applications/48/Arch_Amazon-Connect_48.svg`
