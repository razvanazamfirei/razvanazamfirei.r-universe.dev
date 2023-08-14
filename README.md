# Razvan Azamfirei's R Package Universe

https://razvanazamfirei.r-universe.dev/

To install packages from this universe, use

```r
# Enable this universe
options(repos = c(
    razvanazamfirei = 'https://razvanazamfirei.r-universe.dev',
    CRAN = 'https://cloud.r-project.org'))

# Install some packages
install.packages('dplyr')
```

The main file is `packages.yaml`. To get the json file, we run:

```
yq packages.yaml -o=json -i packages.json
```
