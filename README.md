# Magisk_Files_Broker

代理 Magisk Manager 更新通道

将[Magisk File Host](https://github.com/topjohnwu/magisk_files)的.Json 文件内链接重新指向代理镜像网站<https://fastgit.org/>

文件内容每 8 小时同步更新一次

## 自定义更新通道

|  版本  |                                  链接                                   |
| :----: | :---------------------------------------------------------------------: |
| stable | <https://cdn.jsdelivr.net/gh/RC1844/Magisk_Files_Broker@master/stable.json> |
|  beta  |  <https://cdn.jsdelivr.net/gh/RC1844/Magisk_Files_Broker@master/beta.json>  |
| canary | <https://cdn.jsdelivr.net/gh/RC1844/Magisk_Files_Broker@master/canary.json> |

## 其他

如果需要更换镜像网站，请[New issues](https://github.com/RC1844/Magisk_Files_Broker/issues/new/choose)

或者 Fork 该仓库，并修改[main.yml](.github/workflows/main.yml)
