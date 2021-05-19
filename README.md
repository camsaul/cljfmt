# `camsaul/cljfmt`

Fork of [`weavjester/cljfmt`](https://github.com/weavejester/cljfmt) with support for `:style/indent` metadata. Work
in progress.

```bash
clojure -Sdeps \
  '{:deps {camsaul/cljfmt {:git/url "https://github.com/camsaul/cljfmt.git" \
                           :sha "<latest-hash>"}}}' \
  -M -m cljfmt.main [check|fix] & paths
```
