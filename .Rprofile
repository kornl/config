# Mainly from ?Startup:

local({
  r <- getOption("repos")
  r["CRAN"] <- "http://ftp5.gwdg.de/pub/misc/cran/"
  options(repos = r)
  ## (for Unix terminal users) set the width from COLUMNS if set
  cols <- Sys.getenv("COLUMNS")
  if(nzchar(cols)) options(width = as.integer(cols))
  # interactive sessions get a fortune cookie (needs fortunes package)
  if (interactive()) {
    fortunes::fortune()
  }
  #options(stringsAsFactors=FALSE)
})

# Ideas from http://stackoverflow.com/questions/1189759/expert-r-users-whats-in-your-rprofile

#.Last <- function() {
#  if (!any(commandArgs()=='--no-readline') && interactive()){
#    require(utils)
#    try(savehistory(Sys.getenv("R_HISTFILE")))
#  }
#}


