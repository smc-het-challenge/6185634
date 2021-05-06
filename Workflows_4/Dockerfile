FROM r-base

# install packages
RUN echo 'install.packages(c("matrixStats", "mixtools"), repos = "http://cran.us.r-project.org", dependencies = TRUE)' > /tmp/packages.R && Rscript /tmp/packages.R
RUN echo 'install.packages("data.table", type = "source", repos = "http://Rdatatable.github.io/data.table", dependencies = TRUE)' > /tmp/packages.R && Rscript /tmp/packages.R
