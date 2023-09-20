FROM rocker/verse

WORKDIR /home/rstudio
# Dump in repo contents
COPY . CV
WORKDIR /home/rstudio/CV
# Install python; install yamllint
# for checking yaml file structure and graphviz to
# enable dot language diagramming
# --
# the `export MAKEFLAGS="-j `nproc`"` command is included to ensure the build fails
# if an error occurs.
#RUN export MAKEFLAGS="-j `nproc`" ; \
#  apt-get update -y ; \
#  apt-get install -y yamllint ; \
  # Install Radian to support vscode R console
#  pip3 install -U radian ; \
  # Install common R packages
  # languageserver supports the R LSP extension in vscode, it allows
  # intellisence for R in vscode
#  install2.r --error --skipinstalled pander kableExtra git2r spelling DiagrammeR here languageserver gh tippy flextable ; \
