# wipastudio.github.io

Root site for `wipastudio.github.io`. Exists so that
`/.well-known/apple-app-site-association` is served from the domain
root — iOS reads it there and nowhere else.

Universal links: `https://wipastudio.github.io/kadra/j/<CODE>` opens a
Kadra room in the app. The page itself lives in the `kadra` repo.

The file must be served as-is, with no extension and no Jekyll
processing — hence `.nojekyll`.

Universal links: `https://wipastudio.github.io/emanet/d/?c=<CODE>` (invite) and
`https://wipastudio.github.io/emanet/o/<route>` open Emanet. The pages live in
the `emanet` repo.
