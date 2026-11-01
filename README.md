# challange08
Start.
Read the grid size N.
Check whether N is between 3 and 6. If invalid, read again.
Read N × N risk scores.
Check every score is between 0 and 100. If invalid, read again.
Read warning threshold T between 1 and 100.
Calculate the total of each row and identify the highest row total, including ties.
Calculate the total of each column and identify the highest column total, including ties.
Find the maximum risk score and display all its positions.
Count cells whose scores are greater than or equal to T.
Calculate the main and secondary diagonal sums.
Compare both diagonal sums.
Calculate the boundary total, counting every boundary cell once.
Identify local hotspots by comparing interior cells with their four neighbours.
Display the decision:
CRITICAL – if at least one hotspot exists.
WARNING – if no hotspot exists and at least N cells meet the threshold.
NORMAL – otherwise.
Stop.
