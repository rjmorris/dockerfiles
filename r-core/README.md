Run an R REPL with: `docker run -it rjmorris/r-core R`.

Run a script named `script.R` in the current directory with `docker run -v $(pwd):/code rjmorris/r-core Rscript script.R`.

Note that this directory is named `r-core` instead of my preferred `r` because Docker Hub has a minimum length of 2 for project names.
