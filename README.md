# SquirrelMail

It's a docker image for SquirrelMail

## Run

docker run -p 22-p 80 -d -v /tmp:/tmp squirrelmail:latest /usr/bin/supervisord

## Set

and reset with the following command in SSH

# /etc/squirrelmail/conf.pl

-IMAP connection information
-Existence of IMAP TLS connections
- `2. Server Settings ' ==&gt; ' A. Update IMAP Settings '

