FROM rocker/tidyverse

RUN Rscript -e "install.packages('argparse')"
RUN Rscript -e "install.packages('rjson')"

COPY bin/* /usr/local/bin/
