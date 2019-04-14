## PHP编码规范

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