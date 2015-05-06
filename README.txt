
                                       README
                                      HOMEWORK 3

Scripts to create massive HTTP/HTTPS connections

run.sh : Runs 1000 simultaneus HTTP conections to the target server

runS.sh: Runs 1000 simultaneus HTTP conections to the target server


Commands to capture performance metrics

top -b -d3 -n300 > top.out

Initial preprocessing: filtering of lines with measurements of Memory comsumption
and CPU processing time.
 grep "Cpu(" top.out
 grep "Mem:" top.out
 
Final preprocessing/graphincs are made in EXCEL