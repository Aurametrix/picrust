BIOM, an R package for interfacing with the BIOM format.

To install, open R and run the command:
  install.packages("biom")

Possible Warning message:
package ‘biom’ is not available (for R version 3.3.4) 


    ## try http:// if https:// URLs are not supported
    source("https://bioconductor.org/biocLite.R")
    biocLite("biomformat")
    
    
Convert to biom:

    biom convert -i otu_table.txt -o new_otu_table.biom --to-hdf5 --table-type="OTU table" --process-obs-metadata taxonomy
