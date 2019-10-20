# ModxCaddyRewrite

```
rewrite {
        regexp ^/(.*)$
        to {path} {path}/ /index.php?q={1}&{query}
}
```
