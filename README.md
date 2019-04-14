## PHP编码规范
本工具希望通过基于 [PSR](http://www.php-fig.org/psr/) 规范制定一些团队内部规范化的php代码编写规则，在提交代码前通过脚本自动检查以及修复不合规范的代码，以减少团队成员阅读代码时，因代码风格的不同造成的不便。

### 安装方法
```json
{
    "require-dev": {
        "code_standard":"dev-master"
    },
    "repositories": [
        {
            "type": "git",
            "url": "https://github.com/262cheng/code_standard"
        }
    ],
    "scripts": {
        "post-install-cmd": [
            "sh ./vendor/code_standard/setup_hooks.sh"
        ],
        "post-update-cmd": [
            "sh ./vendor/code_standard/setup_hooks.sh"
        ]
    }
}
```

### 使用方法
