# Thinker
# 环境要求
- php >= 7.0 
- composer > 1.4
# 安裝
```bash
git clone https://github.com/diiyw/thinker.git
```

```bash
# cd thinker
# composer install
```
#### 目录结构
```
.
├── app
│   ├── composer.json
│   ├── composer.lock
│   ├── database
│   │   ├── db
│   │   │   ├── migrations
│   │   │   └── seeds
│   │   └── phinxConfig.php
│   ├── modules
│   │   └── home
│   │       ├── config
│   │       │   ├── db.php
│   │       │   └── router.php
│   │       └── Index.php
│   ├── plugins
│   │   ├── Session.php
│   │   └── Whoops.php
│   └── vendor
├── README.md
├── views
│   └── default
│       ├── common
│       │   └── footer.phtml
│       └── home
│           └── index.phtml
└── www
    ├── cache
    │   └── default
    │       ├── common
    │       │   ├── footer.html
    │       │   └── footer.phtml
    │       └── home
    │           ├── index.html
    │           └── index.phtml
    ├── index.php
    └── logs
```

# 快速创建模块
```
# cd app/module
# ../vendor/bin/thinker create
```
按照提示即可一步创建

# 模型使用
- https://medoo.in