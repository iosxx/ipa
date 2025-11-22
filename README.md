# IPA 数据仓库

这个仓库用于存储从 TrollStore-IPA 自动化生成的数据文件。

## 文件说明
- `apps_esign.json` - 完整的应用信息和下载链接
- `apps.json` - 转换格式的应用数据
- `bundleId.csv` - 应用包名和ID映射表
- `icons/` - 应用图标文件

## 自动化更新
此仓库由 [TrollStore-IPA](https://github.com/iosxx/TrollStore-IPA) 仓库的 GitHub Actions 自动维护。

当有新的 IPA 文件发布时，会自动更新此仓库中的数据文件。
