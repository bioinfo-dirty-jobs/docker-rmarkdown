# docker-rmarkdown
Rmarkdown typesetter
To run

    $ docker run -it --rm -v $PWD:/rdoc rmarkdown Rscript -e 'rmarkdown::render("/rdoc/input.Rmd")'
