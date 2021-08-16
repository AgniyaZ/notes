## Configure Git username/email
### To set global username/email configuration:

    git config --global user.name "FIRST_NAME LAST_NAME"
    git config --global user.email "MY_NAME@example.com"

### To set repository-specific username/email configuration:

    git config user.name "FIRST_NAME LAST_NAME"
    git config user.email "MY_NAME@example.com"
    cat .git/config

## Настройка алиасов

Добавьте следующее в файл .gitconfig в вашем $HOME каталоге:

    [alias]
        co = checkout
        ci = commit
        st = status
        br = branch