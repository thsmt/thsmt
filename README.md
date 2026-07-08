# ポートフォリオ

## 経歴・資格

AWS を中心に、ネットワーク、サーバー、Linux、Webアプリケーション基盤、バックアップ運用を設計・構築・運用の観点で整理しています。CloudFormation による Infrastructure as Code、構成図、パラメータ例、セキュリティ上の考慮点、運用手順を残し、後から再現・説明できるインフラ構成としてまとめています。

| 項目 | 内容 |
| --- | --- |
| 認定ハイライト | 🏆2025 Japan All AWS Certifications Engineer<br>🏆🏆2026 Japan All AWS Certifications Engineer |
| 資格の認定状況 | Credly（https://www.credly.com/users/takahide-hashimoto.6625d2dc） |
| 横断的な運用手順・ツールメモ | [GitHub Pages](https://thsmt.github.io/Knowledge/) |

<details>
<summary>取得資格一覧</summary>

<br>

| 取得年月 | 資格名 |
| --- | --- |
| 2022/07 | CCNA |
| 2022/09 | LinuC-1 |
| 2022/10 | LinuC-3 304 |
| 2022/11 | LinuC-2 |
| 2022/11 | LinuC-3 303 |
| 2022/12 | AWS Certified Cloud Practitioner |
| 2023/01 | AWS Certified Solutions Architect - Associate |
| 2023/02 | AWS Certified Developer - Associate |
| 2023/04 | AWS Certified SysOps Administrator - Associate |
| 2024/04 | AWS Certified Solutions Architect - Professional |
| 2024/04 | AWS Certified: SAP on AWS - Specialty |
| 2024/04 | AWS Certified DevOps Engineer - Professional |
| 2024/05 | AWS Certified Data Engineer - Associate |
| 2024/11 | AWS Certified Security - Specialty |
| 2024/12 | AWS Certified Advanced Networking - Specialty |
| 2025/01 | AWS Certified AI Practitioner |
| 2025/01 | AWS Certified Machine Learning Engineer - Associate |
| 2025/02 | AWS Certified Machine Learning - Specialty |
| 2026/03 | AWS Certified CloudOps Engineer - Associate |
| 2026/03 | AWS Certified Generative AI Developer - Professional |
| 2026/04 | AWS Certified Security - Specialty |

</details>

<br>

## 代表リポジトリ

### PoC

勤務先で扱った技術課題や構築前検証を、機密情報を除外して一般化したリポジトリです。実案件で発生しやすい要件や運用上の論点を、再現しやすいCloudFormationテンプレート、構成図、手順として整理しています。

| Repository | 概要 | 主な技術・観点 |
| --- | --- | --- |
| [workspaces-ad-foundation-poc](https://github.com/thsmt/workspaces-ad-foundation-poc) | Amazon WorkSpaces検証用のAD基盤PoC | AWS Managed Microsoft AD、VPC Peering、AD Connector、WorkSpaces、Client VPN |
| [aws-windows-ilb-poc](https://github.com/thsmt/aws-windows-ilb-poc) | Windows Server + 内部Load Balancer構成の事前検証 | Windows Server、Internal Load Balancer、VPC、Security Group、CloudFormation |
| [aws-nfw-policy-switch-poc](https://github.com/thsmt/aws-nfw-policy-switch-poc) | Patch Managerのメンテナンス時間に合わせたNetwork Firewallポリシー切り替えPoC | AWS Network Firewall、Lambda、EventBridge Scheduler、Patch Manager、CloudFormation |
| [aws-backup-ops-baseline-poc](https://github.com/thsmt/aws-backup-ops-baseline-poc) | AWS Backupを利用したタグベースのバックアップ運用基盤PoC | AWS Backup、Backup Vault、EventBridge、SNS、KMS、CloudFormation |

### Lab

書籍や学習テーマをもとに、自主学習としてAWS構成を再現したリポジトリです。基礎理解、設計差分の整理、CloudFormationによるIaC化の練習を目的に、作成範囲や対象外にした内容も明記しています。

| Repository | 概要 | 主な技術・観点 |
| --- | --- | --- |
| [aws-nwsv-lab](https://github.com/thsmt/aws-nwsv-lab) | VPC + Web / DB 2層構成の基礎学習リポジトリ | VPC、Subnet、NAT Gateway、Security Group、CloudFormation |
| [aws-network-fundamentals-lab](https://github.com/thsmt/aws-network-fundamentals-lab) | ALB + Webサーバー2台 + DBサーバー構成の再現 | ALB、EC2、MariaDB、WordPress、ネットワーク分離 |
| [amznlinux-webapp-infra-lab](https://github.com/thsmt/amznlinux-webapp-infra-lab) | Amazon Linux 2023 上のWebアプリケーション基盤を再現 | Amazon Linux 2023、Apache、PHP、RDS、S3、UserData |
| [aws-webapp-infra-lab](https://github.com/thsmt/aws-webapp-infra-lab) | Railsアプリケーション基盤を想定したAWSインフラ構成 | RDS、S3、ElastiCache、Secrets Manager、Parameter Store、設計差分整理 |

<br>

## 技術スタック



### クラウド・インフラ

![AWS Badge](https://img.shields.io/badge/AWS-%23FF9900.svg?logo=amazon-aws&logoColor=white&style=flat)
![Azure Badge](https://img.shields.io/badge/Azure-0078D4?logo=microsoft-azure&logoColor=white&style=flat)
![CloudFormation Badge](https://img.shields.io/badge/CloudFormation-%23FF9900.svg?logo=amazon-aws&logoColor=white&style=flat)
![AWS Backup Badge](https://img.shields.io/badge/AWS%20Backup-%23FF9900.svg?logo=amazon-aws&logoColor=white&style=flat)
![Terraform Badge](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white&style=flat)
![Kubernetes Badge](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white&style=flat)
![Docker Badge](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat)
![Active Directory Badge](https://img.shields.io/badge/Active%20Directory-0078D4?logo=windows&logoColor=white&style=flat)
![Zabbix Badge](https://img.shields.io/badge/Zabbix-D40000?logo=zabbix&logoColor=white&style=flat)
![Apache Badge](https://img.shields.io/badge/Apache-D22128?logo=apache&logoColor=white&style=flat)
![NGINX Badge](https://img.shields.io/badge/NGINX-009639?logo=nginx&logoColor=white&style=flat)


### OS

![Red Hat Badge](https://img.shields.io/badge/Red%20Hat-EE0000?logo=redhat&logoColor=white&style=flat)
![Amazon Linux Badge](https://img.shields.io/badge/Amazon%20Linux-FF9900?logo=linux&logoColor=white&style=flat)
![Windows Server Badge](https://img.shields.io/badge/Windows%20Server-0078D6?logo=windows&logoColor=white&style=flat)


### 言語・スクリプト

![Python Badge](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat)
![PHP Badge](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white&style=flat)
![Shell Badge](https://img.shields.io/badge/Shell_Script-121011?logo=gnu-bash&logoColor=white&style=flat)
![JSON Badge](https://img.shields.io/badge/JSON-000000?logo=json&logoColor=white&style=flat)
![YAML Badge](https://img.shields.io/badge/YAML-CB171E?logo=yaml&logoColor=white&style=flat)


### データベース

![PostgreSQL Badge](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=flat)
![MySQL Badge](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=flat)
![MariaDB Badge](https://img.shields.io/badge/MariaDB-003545?logo=mariadb&logoColor=white&style=flat)
![Redis Badge](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white&style=flat)


### 開発・業務ツール

![Git Badge](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=flat)
![GitHub Badge](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=flat)
![Visual Studio Code Badge](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?logo=visual-studio-code&logoColor=white&style=flat)
![Salesforce Badge](https://img.shields.io/badge/Salesforce-00A1E0?logo=salesforce&logoColor=white&style=flat)
![ServiceNow Badge](https://img.shields.io/badge/ServiceNow-81B5A1?logo=servicenow&logoColor=white&style=flat)
![TeamSpirit Badge](https://img.shields.io/badge/TeamSpirit-F5A623?style=flat)
![Slack Badge](https://img.shields.io/badge/Slack-4A154B?logo=slack&logoColor=white&style=flat)
![Jira Badge](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white&style=flat)
![Confluence Badge](https://img.shields.io/badge/Confluence-172B4D?logo=confluence&logoColor=white&style=flat)
![Redmine Badge](https://img.shields.io/badge/Redmine-B32024?logo=redmine&logoColor=white&style=flat)
