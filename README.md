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
│   │   ├── migrations
│   │   ├── phinxConfig.php
│   │   └── seeds
│   ├── modules
│   │   └── home
│   │       ├── controller
│   │       │   ├── Index.php
│   │       │   └── IndexFilter.php
│   │       └── HomeConst.php
│   └── plugins
│       └── thinker
│           ├── Session.php
│           └── Whoops.php
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
    │       │   └── footer.phtml
    │       └── home
    │           └── index.phtml
    ├── index.php
    └── logs
        └── sys.log
```

# 快速创建模块
```
# cd app/module
# ../vendor/bin/thinker create
```
按照提示即可一步创建
