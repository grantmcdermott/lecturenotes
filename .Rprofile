source("renv/activate.R")
options(repos = c(RSPM = "https://packagemanager.rstudio.com/all/latest"))

## For Mac we'll rather use CRAN since RSPM doesn't ship binaries for it
if (!(Sys.info()[['sysname']] %in% c('Linux', 'Windows'))) {
  options(repos = c(CRAN = "https://cran.rstudio.com"))
  options(renv.config.repos.override = getOption('repos'))
}
