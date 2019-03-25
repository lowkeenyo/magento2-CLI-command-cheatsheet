# magento2-CLI-command-cheatsheet
Cheatsheet for magento 2 default CLI commands. Helpful for when in development


admin

    php bin/magento admin:user:create              php bin/magento a:u:c
    php bin/magento admin:user:unlock              php bin/magento a:u:u   
cache

    php bin/magento cache:clean                  php bin/magento c:c
    php bin/magento cache:disable                php bin/magento c:d
    php bin/magento cache:enable                 php bin/magento c:e
    php bin/magento cache:flush                  php bin/magento c:f
    php bin/magento cache:status                 php bin/magento c:s
catalog

    php bin/magento catalog:images:resize                   php bin/magento c:i:r
    php bin/magento catalog:product:attributes:cleanup      php bin/magento c:p:a:c
cron

    php bin/magento cron:run              php bin/magento c:r
customer

    php bin/magento customer:hash:upgrade     php bin/magento c:h:u
deploy

    php bin/magento deploy:mode:set           php bin/magento d:m:se
    php bin/magento deploy:mode:show          php bin/magento d:m:sh
dev

    php bin/magento dev:source-theme:deploy        php bin/magento d:source-theme:d
    php bin/magento dev:tests:run                  php bin/magento d:t:r
    php bin/magento dev:urn-catalog:generate       php bin/magento d:urn-catalog:g
    php bin/magento dev:xml:convert                php bin/magento d:x:c
i18n

    php bin/magento i18n:collect-phrases           php bin/magento i:collect-phrases
    php bin/magento i18n:pack                      php bin/magento i:p
    php bin/magento i18n:uninstall                 php bin/magento i:u
indexer

    php bin/magento indexer:info                   php bin/magento i:i
    php bin/magento indexer:reindex                php bin/magento i:rei
    php bin/magento indexer:reset                  php bin/magento i:res
    php bin/magento indexer:set-mode               php bin/magento i:set
    php bin/magento indexer:show-mode              php bin/magento i:show
    php bin/magento indexer:status                 php bin/magento i:st
info

    php bin/magento info:adminuri                              php bin/magento i:a
    php bin/magento info:backups:list                          php bin/magento i:b:l
    php bin/magento info:currency:list                         php bin/magento i:c:l
    php bin/magento info:dependencies:show-framework           php bin/magento i:d:show-framework
    php bin/magento info:dependencies:show-modules             php bin/magento i:d:show-modules
    php bin/magento info:dependencies:show-modules-circular    php bin/magento i:d:show-circular
    php bin/magento info:language:list                         php bin/magento i:l:l
    php bin/magento info:timezone:list                         php bin/magento i:t:l
maintenance

    php bin/magento maintenance:allow-ips          php bin/magento ma:a
    php bin/magento maintenance:disable            php bin/magento ma:d
    php bin/magento maintenance:enable             php bin/magento ma:e
    php bin/magento maintenance:status             php bin/magento ma:s
module

    php bin/magento module:disable                 php bin/magento mo:d
    php bin/magento module:enable                  php bin/magento mo:e
    php bin/magento module:status                  php bin/magento mo:s
    php bin/magento module:uninstall               php bin/magento mo:u
sampledata

    php bin/magento sampledata:deploy            php bin/magento ma:d
    php bin/magento sampledata:remove            php bin/magento sa:rem
    php bin/magento sampledata:reset             php bin/magento sa:res
setup

    php bin/magento setup:backup                            php bin/magento se:b
    php bin/magento setup:config:set                        php bin/magento se:c:se
    php bin/magento setup:cron:run                          php bin/magento se:c:r
    php bin/magento setup:db-data:upgrade                   php bin/magento se:db-data:u
    php bin/magento setup:db-schema:upgrade                 php bin/magento se:db-schema:u
    php bin/magento setup:db:status                         php bin/magento se:d:st
    php bin/magento setup:di:compile                        php bin/magento se:d:c
    php bin/magento setup:install                           php bin/magento se:i
    php bin/magento setup:performance:generate-fixtures     php bin/magento se:p:generate-fixtures
    php bin/magento setup:rollback                          php bin/magento se:r
    php bin/magento setup:static-content:deploy             php bin/magento se:s:d
    php bin/magento setup:store-config:set                  php bin/magento se:sto:s 
    php bin/magento setup:uninstall                         php bin/magento se:un
    php bin/magento setup:upgrade                           php bin/magento se:up
theme

    php bin/magento theme:uninstall                         php bin/magento t:u
