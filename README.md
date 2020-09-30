# Manage your email aliases on Namecheap

I'll make this into a gem someday, but for now:

1. Fork or clone the repo

2. In the repo's directory, copy `config.yml.sample` to `config.yml`
and edit with your Namecheap credentials

3. In the repo's directory, you should now be able to run these
commands:

```
./email-alias get
./email-alias create aliasname
./email-alias create aliasname forwarding_target@email.com
./email-alias delete aliasname
```

