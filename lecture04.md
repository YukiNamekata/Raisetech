## 第４回講座の課題

１．VPC構築

![VPC構築](https://github.com/YukiNamekata/Raisetech/assets/139564081/c9e04792-37fe-4037-8b9b-b7d784904dcf)



２．EC2構築

![EC2(1)](https://github.com/YukiNamekata/Raisetech/assets/139564081/f0a7ef44-5314-4a53-85bd-fe46524e6315)



３．EC2のセキュリティグループのルール（接続元を自身のIPアドレスのみに絞りました）

![EC2(2)](https://github.com/YukiNamekata/Raisetech/assets/139564081/e94e4a8d-d75e-4ced-a30a-909c4d3f7bc7)


４．RDS構築（サブネットグループはプライベートサブネットのみにしました※下2枚の画像）

![RDS(1)](https://github.com/YukiNamekata/Raisetech/assets/139564081/66039314-6c79-460f-b3f1-0d287c33a4cc)


![RDS(2)](https://github.com/YukiNamekata/Raisetech/assets/139564081/f58f38eb-db06-4b8b-be6e-f77a93f208aa)

![RDS(3)](https://github.com/YukiNamekata/Raisetech/assets/139564081/38f354aa-3cdc-4707-88d2-75dc03501905)


５．RDSのセキュリティグループのルール（接続元をEC2のみに絞りました）

![RDS(4)](https://github.com/YukiNamekata/Raisetech/assets/139564081/df893841-2ef6-4d1e-b98f-d53f94ab2dfc)
※　ご指摘いただいた「22番ポートは何のために開いているか？」と「IPv6用のルールは何のために開いていますか？」の２点ですが、わけもわからず設定をいじっているうちにルールに追加されたようなので、不要と判断し削除しました。


６．EC2起動後、RDSに接続

![EC2起動](https://github.com/YukiNamekata/Raisetech/assets/139564081/4a67d1b4-9f4b-4125-b42f-5669ecbfece4)

![EC2→RDS接続](https://github.com/YukiNamekata/Raisetech/assets/139564081/1cbe1d59-e5dd-4510-a625-dba950049d67)
