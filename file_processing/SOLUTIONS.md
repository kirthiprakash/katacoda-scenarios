Task 1 (possible) solution
grep -oP '(?<=\?code=)\w+' sample.log | sort | uniq | xargs -I {} touch {}.txt
