# mojverse

The `mojverse` is an ecosystem of packages containing functions useful for automating various tasks when building reproducible analytical pipelines.

## Installation

To use packages within the `mojverse`, please install it as follows: 
````
remotes::install_github("moj-analytical-services/mojverse") 
````
This will automatically install all packages belonging to the `mojverse`.

## Packages within the mojverse

Currently, the `mojverse` includes the following packages:

* [mojrap](https://github.com/moj-analytical-services/mojrap): Generalised functions for RAP
* [mojspeakr](https://github.com/moj-analytical-services/mojspeakr): Formatting RMarkdown into govspeak for publishing on gov.uk
* [mojchart](https://github.com/moj-analytical-services/mojchart): Formatting ggplot2 charts and applying MoJ corporate colours

## Usage

To use functions from the above packages, prefix the function name with the following: 

````
[package_name]::function_name()
````

## Contributing to the mojverse

If you feel there is something missing from packages in the `mojverse` which could benefit others, please contribute to them via pull requests, or raise Issues if you find any bugs or to suggest improvements. Alternatively, create a new package, and create a pull request here. An admin will then review the package and decide whether to include it.



