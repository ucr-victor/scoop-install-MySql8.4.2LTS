创建自定义 Scoop Bucket 并安装 MySQL
创建 ~\scoop\buckets\my-bucket\bucket 文件夹。
将 mysql.json 文件放入 bucket 文件夹中。
通过 Scoop 命令 scoop install mysql@8.4.2 安装 MySQL 8.4.2。

注意事项
确保 mysql.json 文件格式正确，并且包含 MySQL 8.4.2 的相关信息。
如果这是首次使用自定义 Bucket，请确保已通过 scoop bucket add my-bucket "~\scoop\buckets\my-bucket" 命令添加自定义 Bucket。
若安装失败，可使用 scoop update 更新 Scoop 并重试。
