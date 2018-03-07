# KitchenSink.jl
Load lots of stuff!

To use this, copy and paste the following into `~/.juliarc.jl`:

```julia
if isdir(Pkg.dir("KitchenSink"))
  Pkg.checkout("https://github.com/AustinPrivett/KitchenSink.jl")
end
using KitchenSink
```
