# Data Indexer

Find datasets on your disk!

### Usage

```bash
julia
```

```julia
julia> import Pkg
(v1.3 pkg> add "https://github.com/innerlee/DataIndexer.jl"
```

```bash
./bin/dataindex /mnt > res.txt # note: julia should be in your $PATH, so that it can run.
```

or
```julia
julia> using DataIndexer
julia> dataindex(".")
```

