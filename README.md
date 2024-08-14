# Steps to reproduce

1. Run `docker compose up -d`
2. Run `docker exec -it shopware /bin/bash`
3. Run `bin/console plugin:refresh`
4. Run `bin/console plugin:install --activate MyPlugin`
