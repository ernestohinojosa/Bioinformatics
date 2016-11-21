#Nanopore Run 2
  
  1. Software crashed after 8 hours of running. Could be restarted succesfully but total run was only ~30 hours.
  2. Downloaded the reads from the 8 hours run (Run2A-8h) and the 30 hours run (Run2B-30h)
  3. Use poretools to process the reads.
  
##Stats
###Run2A-8h
*pass*

  poretools stats pass/ > stats.pass.txt
  
  less stats.pass.txt
    
    total reads     16530
    total base pairs        41949006
    mean    2537.75
    median  1210
    min     92
    max     17457
    N25     7667
    N50     5718
    N75     3377
    
*fail*

  poretools stats fail/ > stats.fail.txt
  
  less stats.fail.txt
  
    total reads     68912
    total base pairs        118541822
    mean    1720.19
    median  835
    min     5
    max     97564
    N25     4158
    N50     3343
    N75     2657

###Run2B-30h

*pass*

  poretools stats pass/ > stats.pass.txt
  
  less stats.pass.txt
  
    total reads     28743
    total base pairs        72631285
    mean    2526.92
    median  1199
    min     92
    max     17457
    N25     7681
    N50     5661
    N75     3349