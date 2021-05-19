# `camsaul/cljfmt`

Fork of [`weavjester/cljfmt`](https://github.com/weavejester/cljfmt) with support for `:style/indent` metadata. Work
in progress.

```bash
clojure -Sdeps \
  '{:deps {camsaul/cljfmt {:git/url "https://github.com/camsaul/cljfmt.git" \
                           :sha "d01a835cb74104fd9cb2f39cb3d4d87c5e8ab52d"}}}' \
  -M -m cljfmt.main [check|fix] 
```
