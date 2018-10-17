## 使用方式
#### 在vscode编辑器配置里面配置
* qiniu
* yuque
> 配置参考
```
{   
    // yuque token
    "yuque.token": "*************"
    "yuque.team_path": "starkwang"
    "yuque.doc_path": "blog"
    // https://www.yuque.com/starkwang/blog 相当于把文章发布到这个里面


    // 有效的七牛 AccessKey 签名授权
    "qiniu.access_key": "*****************************************",

    // 有效的七牛 SecretKey 签名授权
    "qiniu.secret_key": "*****************************************",

    // 七牛图片上传空间
    "qiniu.bucket": "blog",
    // 七牛图片上传路径，参数化命名，暂时支持 ${fileName}、${mdFileName}、${date}、${dateTime}
    // 示例：
    //   ${fileName}-${date} -> picName-20160725.jpg
    //   ${mdFileName}-${dateTime} -> markdownName-20170412222810.jpg
    "qiniu.remotePath": "${fileName}",
    // 七牛图床域名
    "qiniu.domain": "http://img.shudong.wang",
    // 本地储存位置
    "qiniu.localPath":"./img"
}
```
#### 问题 issue
https://github.com/wsdo/rd-note/issues
