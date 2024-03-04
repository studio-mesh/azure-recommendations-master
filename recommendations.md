# 推奨事項マスタ

## AI Service

| en-us                                                         | ja-jp                                                     |
| ------------------------------------------------------------- | --------------------------------------------------------- |
| Potential Cost Savings on this Document Intelligence Resource | この Document Intelligence リソースのコスト削減の可能性   |
| Potential Cost Savings on this Computer Vision Resource       | この Computer Vision リソースで可能なコスト削減           |
| Potential Cost Savings on this Speech Service Resource        | この Speech Service リソースで可能なコスト削減            |
| Potential Cost Savings on this Translator Resource            | この Translator リソースで可能なコスト削減                |
| Potential Cost Savings on this LUIS Resource                  | この LUIS リソースで可能なコスト削減                      |
| Potential Cost Savings on this Language Service Resource      | この Language Service リソースで可能なコスト削減          |
| Enable Autoscaling for Azure Databricks Clusters              | Azure Databricks クラスターの自動スケーリングを有効にする |

## Analytics

| en-us                                                                            | ja-jp                                                                             |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Unused, stopped, Data Explorer resources                                         | 未使用の停止した Data Explorer リソース                                           |
| Unused/Empty Data Explorer resources                                             | 未使用または空の Data Explorer リソース                                           |
| Right-size Data Explorer resources for optimal cost                              | コストを最適化するために Data Explorer のリソースを適切なサイズにする             |
| Reduce Data Explorer table cache policy to optimize costs                        | Data Explorer のテーブル キャッシュ ポリシーを減らし、コストを最適化する          |
| Unused running Data Explorer resources                                           | 未使用の実行中の Data Explorer リソース                                           |
| Cleanup unused storage in Data Explorer resources                                | Data Explorer リソース内の未使用ストレージをクリーンアップする                    |
| Enable optimized autoscale for Data Explorer resources                           | Data Explorer のリソースの最適化された自動スケーリングを有効にする                |
| Change Data Explorer clusters to a more cost effective and better performing SKU | Data Explorer クラスターを、コスト効率とパフォーマンスがさらに高い SKU に変更する |
| Consider Changing Pricing Tier                                                   | 価格帯の変更を検討する                                                            |
| Consider configuring the low-cost Basic logs plan on selected tables             | 選択したテーブルで低コストの基本ログ プランを構成することを検討してください       |
| Consider removing unused restored tables                                         | 未使用で復元されたテーブルの削除を検討する                                        |
| Consider enabling autopause on Spark compute                                     | Spark コンピューティングで自動一時停止を有効にすることを検討する                  |
| Consider enabling autoscale on Spark compute                                     | Spark コンピューティングで自動スケーリングを有効にすることを検討する              |

## Compute

| en-us                                                                                                          | ja-jp                                                                                                    |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Standard SSD disks billing caps.                                                                               | Standard SSD ディスクの課金上限。                                                                        |
| Underutilized Disks Identified                                                                                 | 使用率の低いディスクが特定されました                                                                     |
| You have disks that have not been attached to a VM for more than 30 days. Evaluate if you still need the disk. | 30 日を超えて VM に接続されていないディスクがあります。 ディスクがまだ必要かどうかを評価してください。   |
| Right-size or shutdown underutilized virtual machine scale sets                                                | 使用率が低い仮想マシン スケール セットを適切なサイズに変更するかシャットダウンしてください               |
| Use Virtual Machines with Ephemeral OS Disk enabled to save cost and get better performance                    | エフェメラル OS ディスクが有効になっている仮想マシンを使用してコストを削減し、パフォーマンスを向上させる |

## Databases

| en-us                                                                                          | ja-jp                                                                                                |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| Right-size underutilized MariaDB servers                                                       | 使用率が低い MariaDB サーバーを適切なサイズに変更する                                                |
| Right-size underutilized MySQL servers                                                         | 使用率が低い MySQL サーバーを適切なサイズに変更する                                                  |
| Right-size underutilized PostgreSQL servers                                                    | 使用率が低い PostgreSQL サーバーを適切なサイズに変更する                                             |
| Review the configuration of your Azure Cosmos DB free tier account                             | Azure Cosmos DB の Free レベル アカウントの構成を確認する                                            |
| Consider taking action on your idle Azure Cosmos DB containers                                 | アイドル状態の Azure Cosmos DB コンテナーに対してアクションを実行することを検討する                  |
| Enable autoscale on your Azure Cosmos DB database or container                                 | Azure Cosmos DB データベースまたはコンテナーで自動スケーリングを有効にする                           |
| Configure manual throughput instead of autoscale on your Azure Cosmos DB database or container | Azure Cosmos DB のデータベースまたはコンテナーで自動スケーリングの代わりに手動スループットを構成する |

## **Management and Governance**

| en-us                                                           | ja-jp                                                                            |
| --------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| Purchasing a savings plan for compute could unlock lower prices | コンピューティングの節約プランを購入すると、価格を引き下げられる可能性があります |

## Networking

| en-us                                                                                  | ja-jp                                                                                            |
| -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| Delete ExpressRoute circuits in the provider status of Not Provisioned                 | プロバイダー内の未プロビジョニング状態の ExpressRoute 回線を削除する                             |
| Repurpose or delete idle virtual network gateways                                      | アイドル状態の仮想ネットワーク ゲートウェイを用途変更または削除する                              |
| Consider migrating to Front Door Standard/Premium                                      | Front Door Standard/プレミアム への移行を検討する                                                |
| Consider using multiple endpoints under one single Front Door Standard/Premium profile | 1 つの Front Door Standard/プレミアム プロファイルで複数のエンドポイントを使用することを検討する |

## Reserved instances

| en-us                                                                                                       | ja-jp                                                                                                               |
| ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Buy virtual machine reserved instances to save money over pay-as-you-go costs                               | 従量課金のコストより費用を節約する仮想マシンの予約インスタンスを購入する                                            |
| Consider App Service reserved instances to save over your on-demand costs                                   | オンデマンドの場合よりもコストを削減するために App Service の予約インスタンスを検討する                             |
| Consider Azure Cosmos DB reserved instances to save over your pay-as-you-go costs                           | 従量課金制の場合よりもコストを削減するために Azure Cosmos DB の予約インスタンスを検討する                           |
| Consider virtual machine reserved instances to save over your on-demand costs                               | オンデマンドの場合よりもコストを削減するために仮想マシンの予約インスタンスを検討する                                |
| Consider Cosmos DB reserved instances to save over your pay-as-you-go costs                                 | 従量課金制の場合よりもコストを削減するために Cosmos DB の予約インスタンスを検討する                                 |
| Consider SQL PaaS DB reserved instances to save over your pay-as-you-go costs                               | 従量課金制の場合よりもコストを削減するために SQL PaaS DB の予約インスタンスを検討する                               |
| Consider App Service stamp fee reserved instances to save over your on-demand costs                         | オンデマンドの場合より節約するために App Service スタンプ料金の予約インスタンスを検討する                           |
| Consider Database for MariaDB reserved instances to save over your pay-as-you-go costs                      | 従量課金制の場合よりもコストを削減するために Database for MariaDB の予約インスタンスを検討する                      |
| Consider Database for MySQL reserved instances to save over your pay-as-you-go costs                        | 従量課金制の場合よりもコストを削減するために Database for MySQL の予約インスタンスを検討する                        |
| Consider Database for PostgreSQL reserved instances to save over your pay-as-you-go costs                   | 従量課金制の場合よりもコストを削減するために Database for PostgreSQL の予約インスタンスを検討する                   |
| Consider Cache for Redis reserved instances to save over your pay-as-you-go costs                           | 従量課金制の場合よりもコストを削減するために Cache for Redis の予約インスタンスを検討する                           |
| Consider Azure Synapse Analytics (formerly SQL DW) reserved instances to save over your pay-as-you-go costs | 従量課金制の場合よりもコストを削減するために Azure Synapse Analytics (旧称 SQL DW) の予約インスタンスを検討する     |
| (Preview) Consider Blob storage reserved instances to save on Blob v2 and Data Lake storage Gen2 costs      | (プレビュー) BLOB v2 と Data Lake Storage Gen2 のコストを削減するために BLOB ストレージの予約インスタンスを検討する |
| Consider Azure Dedicated Host reserved instances to save over your on-demand costs                          | Azure Dedicated Host の予約インスタンスを購入してオンデマンドの場合よりもコストを削減することを検討する             |
| Consider Data Factory reserved instances to save over your on-demand costs                                  | Data Factory の予約インスタンスを購入してオンデマンドの場合よりもコストを削減することを検討する                     |
| Consider Azure Data Explorer reserved instances to save over your on-demand costs                           | オンデマンドの場合よりもコストを削減するために Azure Data Explorer の予約インスタンスを検討する                     |
| Consider Azure Files reserved instances to save over your on-demand costs                                   | Azure Files の予約インスタンスを購入してオンデマンドの場合よりもコストを削減することを検討する                      |
| Consider Azure VMware Solution reserved instances to save over your on-demand costs                         | オンデマンドの場合よりもコストを削減するために Azure VMware Solution の予約インスタンスを検討する                   |
| Consider NetApp Storage reserved instances to save over your on-demand costs                                | オンデマンドの場合よりもコストを削減するために NetApp Storage の予約インスタンスを検討する                          |
| Consider Azure Managed Disk reserved instances to save over your on-demand costs                            | オンデマンドの場合よりもコストを削減するために Azure マネージド ディスクの予約インスタンスを検討する                |
| Consider Red Hat reserved instances to save over your on-demand costs                                       | オンデマンドの場合よりもコストを削減するために RedHat の予約インスタンスを検討する                                  |
| Consider RedHat OSA reserved instances to save over your on-demand costs                                    | オンデマンドの場合よりもコストを削減するために RedHat OSA の予約インスタンスを検討する                              |
| Consider SapHana reserved instances to save over your on-demand costs                                       | オンデマンドの場合よりもコストを削減するために SapHana の予約インスタンスを検討する                                 |
| Consider SuseLinux reserved instances to save over your on-demand costs                                     | オンデマンドの場合よりもコストを削減するために SuseLinux の予約インスタンスを検討する                               |
| Consider VMware Cloud Simple reserved instances                                                             | VMware Cloud Simple の予約インスタンスを検討する                                                                    |
| Configure automatic renewal for your expiring reservation                                                   | 期限切れ間近の予約の自動更新を構成する                                                                              |
| Purchasing a savings plan for compute could unlock lower prices                                             | コンピューティングの節約プランを購入すると、価格を引き下げられる可能性があります                                    |
| Consider Cosmos DB reserved instances to save over your pay-as-you-go costs                                 | 従量課金制の場合よりもコストを削減するために Cosmos DB の予約インスタンスを検討する                                 |

## Storage

| en-us                                                                                  | ja-jp                                                                                              |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Use Standard Storage to store Managed Disks snapshots                                  | マネージド ディスクのスナップショットを格納するために Standard Storage を使用する                  |
| Revisit retention policy for classic log data in storage accounts                      | ストレージ アカウントのクラシック ログ データの保持ポリシーを見直す                                |
| Based on your high transactions/TB ratio, premium storage might be more cost effective | 高いトランザクション/TB 比率に基づいて、Premium Storage の方がコスト効率が高くなる可能性があります |
| Use differential or incremental backup for database workloads                          | データベースのワークロードに差分または増分バックアップを使用する                                   |

## Web

| en-us                                      | ja-jp                                                             |
| ------------------------------------------ | ----------------------------------------------------------------- |
| Right-size underutilized App Service plans | 十分に活用されていない App Service プランのサイズを適切に設定する |
| Unused/Empty App Service plans             | 未使用/空の App Service プラン                                    |
