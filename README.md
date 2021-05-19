# `camsaul/cljfmt`

Fork of [`weavjester/cljfmt`](https://github.com/weavejester/cljfmt) with support for `:style/indent` metadata. Work
in progress.

```bash
clojure -Sdeps \
  '{:deps {camsaul/cljfmt {:git/url "https://github.com/camsaul/cljfmt", :sha "ec3884db9b0961c59fd74972c1ca4594f0ab477f"}}}' \
  -M -m cljfmt.main [check|fix]
```
