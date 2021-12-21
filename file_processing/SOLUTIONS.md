Task 1 solution
grep -oP '(?<=?code=)\w+' sample.log | sort | uniq | xargs -I {} touch {}.txt
