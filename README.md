# A collection of some julia shell tools I use in my julia workflow

Inspired by using the command line tool `go fmt` whilst programming in golang.

List of tools
- `jfmt path`: Formats `path` by `JuliaFormatter.jl`s default `format(path)`.
- `jservedocs [-l] YourPackage.jl`: Serves documentation for `YourPackage.jl` locally with `LiveServer.jl`. The l switch stands for `Literate.jl` and currently it's assumed literate files are in `Yourpackage.jl/examples` and that they're processed markdown version is exported to `docs/src/generated` (I didn't bother using good programming principles here soz)
