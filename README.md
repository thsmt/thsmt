# ポートフォリオ

## 経歴・資格

AWS を中心に、ネットワーク、サーバー、Linux、Webアプリケーション基盤、バックアップ運用を設計・構築・運用の観点で整理しています。CloudFormation による Infrastructure as Code、構成図、パラメータ例、セキュリティ上の考慮点、運用手順を残し、後から再現・説明できるインフラ構成としてまとめています。

Scrapbox.io、Notion、Confluenceに分散していた技術メモや運用手順は、GitHub / GitHub Pagesへ移行中です。現時点で掲載している内容は、整理済みの一部です。

| 項目 | 内容 |
| --- | --- |
| 認定ハイライト | 🏆2025 Japan All AWS Certifications Engineer<br>🏆🏆2026 Japan All AWS Certifications Engineer |
| 資格の認定状況 | [Credly](https://www.credly.com/users/takahide-hashimoto.6625d2dc) |
| 横断的な運用手順・ツールメモ | [GitHub Pages](https://thsmt.github.io/Knowledge/) |

### 取得資格一覧

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

<br>

## 代表リポジトリ

### 技術検証

<table>
  <thead>
    <tr>
      <th width="42%">リポジトリ</th>
      <th width="58%">主な技術・観点</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/thsmt/workspaces-ad-foundation-poc">workspaces&#8209;ad&#8209;foundation&#8209;poc</a></td>
      <td>【該当】Amazon WorkSpaces検証用AD基盤の技術検証<br>【サービス・技術】AWS Managed Microsoft AD、VPC Peering、AD Connector、WorkSpaces、Client VPN</td>
    </tr>
    <tr>
      <td><a href="https://github.com/thsmt/aws-windows-ilb-poc">aws&#8209;windows&#8209;ilb&#8209;poc</a></td>
      <td>【該当】Windows Server + 内部Load Balancer構成の事前検証<br>【サービス・技術】Windows Server、Internal Load Balancer、VPC、Security Group、CloudFormation</td>
    </tr>
    <tr>
      <td><a href="https://github.com/thsmt/aws-nfw-policy-switch-poc">aws&#8209;nfw&#8209;policy&#8209;switch&#8209;poc</a></td>
      <td>【該当】Patch Managerのメンテナンス時間に合わせたNetwork Firewallポリシー切り替えの技術検証<br>【サービス・技術】AWS Network Firewall、Lambda、EventBridge Scheduler、Patch Manager、CloudFormation</td>
    </tr>
    <tr>
      <td><a href="https://github.com/thsmt/aws-backup-ops-baseline-poc">aws&#8209;backup&#8209;ops&#8209;baseline&#8209;poc</a></td>
      <td>【該当】AWS Backupを利用したタグベースのバックアップ運用基盤の技術検証<br>【サービス・技術】AWS Backup、Backup Vault、EventBridge、SNS、KMS、CloudFormation</td>
    </tr>
  </tbody>
</table>

### 学習履歴

<table>
  <thead>
    <tr>
      <th width="42%">リポジトリ</th>
      <th width="58%">主な技術・観点</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/thsmt/aws-nwsv-lab">aws&#8209;nwsv&#8209;lab</a></td>
      <td>【該当】VPC + Web / DB 2層構成の基礎学習リポジトリ<br>【サービス・技術】VPC、Subnet、NAT Gateway、Security Group、CloudFormation</td>
    </tr>
    <tr>
      <td><a href="https://github.com/thsmt/aws-network-fundamentals-lab">aws&#8209;network&#8209;fundamentals&#8209;lab</a></td>
      <td>【該当】ALB + Webサーバー2台 + DBサーバー構成の再現<br>【サービス・技術】ALB、EC2、MariaDB、WordPress、ネットワーク分離</td>
    </tr>
    <tr>
      <td><a href="https://github.com/thsmt/amznlinux-webapp-infra-lab">amznlinux&#8209;webapp&#8209;infra&#8209;lab</a></td>
      <td>【該当】Amazon Linux 2023 上のWebアプリケーション基盤を再現<br>【サービス・技術】Amazon Linux 2023、Apache、PHP、RDS、S3、UserData</td>
    </tr>
    <tr>
      <td><a href="https://github.com/thsmt/aws-webapp-infra-lab">aws&#8209;webapp&#8209;infra&#8209;lab</a></td>
      <td>【該当】Railsアプリケーション基盤を想定したAWSインフラ構成<br>【サービス・技術】RDS、S3、ElastiCache、Secrets Manager、Parameter Store、設計差分整理</td>
    </tr>
  </tbody>
</table>

<br>
