# Steps

Using MacOS with homebrew and node v16:

```shell
brew install mkcert
mkcert -install
mkcert nuxt.wip
mkcert localhost

yarn install
```

> You will need to add an entry to your `/etc/hosts`

```
127.0.0.1       nuxt.wip
```

To test SSL using localhost
`yarn dev-localhost -o`

To test with custom domain
`yarn dev-custom -o`
