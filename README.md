yiiframework.com Website
========================

This project contains the source code for the yiiframework.com Website.

## INSTALLATION

```
# clone the project
git clone git@github.com:qiangxue/yiiframework.com.git

cd yiiframework.com

# install the composer asset plugin. This can be skipped if you already installed this before
composer global require "fxp/composer-asset-plugin:1.0.0-beta4

# install the dependent composer packages
composer update

# initialize the application, choose "development"
./init

# clone yii repositories for generating API and guide documentation
cd data
git clone git@github.com:yiisoft/yii.git yii-1.1
git clone git@github.com:yiisoft/yii2.git yii-2.0
```


## REQUIREMENTS

- PHP 5.4.0


## DIRECTORY STRUCTURE

      assets/             contains assets definition
      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      docs/               contains Yii documentation files
      env/                contains environment-dependent files
      mail/               contains view files for e-mails
      models/             contains model classes
      runtime/            contains files generated during runtime
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      web/                contains the entry script and Web resources