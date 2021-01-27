.libPaths("F:/R/R-4.0.3/library")
# BINPREF="F:/R/rtools40/usr/bin"

# rtools path
rtools_path <- paste0(strsplit(getwd(), "/")[[1]][1], "\\R\\rtools40\\usr\\bin")

# git path
git_path <- paste0(strsplit(getwd(), "/")[[1]][1], "\\Git\\bin\\bash.exe")

# append rtools and git to PATH
Sys.setenv(PATH = paste(rtools_path, 
                        git_path,
                        Sys.getenv("PATH"), sep=";"))
Sys.setenv(BINPREF = paste0(rtools_path, "mingw$(WIN)/bin/"))
rm(rtools_path)


# system(`bash --login -i -c "git config user.name "brettmrice"`)

# require(devtools)
# install_version("", version = "", repos = "http://cran.us.r-project.org")
