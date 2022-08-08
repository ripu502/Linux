# Linux

### grep
```
grep "Jane Williams" names.txt
grep "John Williams" names.txt

grep -w "John Williams" names.txt 
grep -wi "John Williams" names.txt 
grep -win "John Williams" names.txt

grep -win -B 4 "John Williams" names.txt
grep -win -A 4 "John Williams" names.txt
grep -win -C 2 "John Williams" names.txt

grep -win "John Williams" ./*
grep -win "John Williams" ./*.txt
grep -winr "John Williams" .
grep -wirl "John Williams" .
grep -wirc "John Williams" .

history
history | grep "git commit"
history | grep "git commit" | grep "dotfile"

grep "...-...-...." names.txt
```

#### flag
- w complete word
- i case insensitive
- n complete line
- B 4 (4 line before) : A after : C surrounding line
- r means recursive
- grep -wirl "John Williams" . (current dir mai complete indept search with i and w)
