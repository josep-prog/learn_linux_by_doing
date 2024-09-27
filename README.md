# learn_linux_by_doing
task 1 one required the use of rm to remove the test-1 file and also required the use of mv to move te temperature files.
task2 involved using sort -u to remove duplicates in csv file or use sort csv | uniq.
then for extracting the top 5 temperatures inlvolved using sort -t, k3 to specify the field where the temp is and sort in descending order then use the head -n 5 :sort -t, k3 rnk 3 | head -n5 > filefortheoutput.
for the lowest you do the same put instead of head use tail 5 for the top 5.
finally for extracting your codes you can use grep -i "your country" > country-heat_data.csv
