# warp10r #

R client for executing Warpscript on a Warp10 instance

### Installation from source ###

Require devtools and roxygen2

```bash
Rscript install.R
```

### First step ###

```R
library(warp10r)
postWarpscript("'Hello world' NOW", outputType="pretty", endpoint="http://localhost:8080/api/v0/exec")
```

```R
Status: 200
[
  1487669519106000,
  "Hello world"
]
```

### Documentation ###

see `warp10r.pdf`
