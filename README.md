add alias for your .bashrc or .zshrc

```
alias php73_composer='docker run --rm -it -v $(pwd):/usr/src/app -v ~/.composer:/home/composer/.composer -v ~/.ssh/id_rsa:/home/composer/.ssh/id_rsa:ro amoydavid/php73-composer:latest'
```

