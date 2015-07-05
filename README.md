# SquirrelMail

It's a docker image for SquirrelMail

## Run

```sh
# docker run -p 22-p 80 -d -v /tmp:/tmp squirrelmail:latest /usr/bin/supervisord
```

## Set

1. Use root/root to login
2. config SquirrelMail with the following command in SSH
> # /etc/squirrelmail/conf.pl
3. Config IMAP connection information
>  `2. Server Settings ' ==&gt; ' A. Update IMAP Settings '

