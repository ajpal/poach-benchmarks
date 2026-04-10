# poach-benchmarks
Benchmarks for the POACH project

## Generating Benchmarks
### Herbie
- Clone the [herbie-fp/herbie](https://github.com/herbie-fp/herbie) repository and follow the installation instructions
- To generate egglog files for a set of benchmarks, run `racket -y src/main.rkt report --enable generate:egglog --enable dump:egglog path/to/benchmark(s) /tmp/out/` from the repo root
- Generated egglog files will be available in `dump-egglog/`
- `bench/arrays` benchmarks are not currently supported by herbie-egglog
