# Population admixture with STRUCTURE

### Input files
To run Structure you need 2 input files: 1) the `.snps.hdf5` file (from ipyrad output files) and 2) a population file \

The population file should look like this:

      imap = {
          "Pop_name1": ["indiv_name1", "indivi_name2"],
          "pop_name2": ["indiv_name3, indiv_name4"],
          "pop_name3": ["indiv_name5", "Sibara_filifolia_HES_SIFI111_9599", "Sibara_filifolia_HES_SIFI124_Bunkers2_9612", "Sibara_filifolia_HES_SIFI128_Bunkers2_9616", "Sibara_filifolia_HES_SIFI129_Bunkers2_9617", "Sibara_filifolia_HES_SIFI130_Bunkers2_9630", "Sibara_filifolia_HES_SIFI44_9519","Sibara_filifolia_HES_SIFI94_9590", "Sibara_filifolia_SNK_SIFI100_9596", "Sibara_filifolia_SNK_SIFI141_Bunkers2_9631","Sibara_filifolia_SNK_SIFI98_9594", "Sibara_filifolia_SNK_SIFI99_9595"],
          }

In terminal
