---
Name: Erneldy Reynoso
Semestre: Fall 23
Course: CIS 106 Linux Fundamentals
---

# Weekly Report

# 1. cat
**Purpose:** Concatenate and display the content of files.
**Syntax:** `cat [file]`
`cat "dracula.txt"`
`cat "books1.txt brooks2.txt"`
`cat "documents.txt"`

# 2. tac
**Purpose:** Display the content of files in reverse order.
**Syntax:** `tac [FILE]`
`tac "bibla.txt"`
`tac "cats.txt dogs.txt"`

# 3. head
**Purpose:** Output the first part of files.
**Syntax:** `head [OPTION] [FILE]`
`head -n 3 "document.txt"`
`head -c 15 "document.txt"`

# 4. tail
**Purpose:** Output the last part of files.
**Syntax:** `tail [OPTION] [FILE]`
`tail -n 3 "document.txt"`
`tail -f "document.txt"`

# 5. cut
**Purpose:** Remove sections from each line of files.
**Syntax:** `cut [OPTION] [FILE]`
`cut -d':' -f2 "document.txt"`
`cut -b 6-10 "document.txt"`
`cut -c 3-7 "document.txt"`

# 6. paste
**Purpose:** Merge lines of files.
**Syntax:** `paste [OPTION] [FILE]`
`paste -d ',' "example.txt example.txt"`
`paste -s "file.txt document.txt"`

# 7. sort
**Purpose:** Sort lines of text files.
**Syntax:** `sort [OPTION] [FILE]`
`sort "file.txt"`
`sort -r "document.txt"`
`sort -k3,3n "example.txt"`

# 8. wc
**Purpose:** Print the number of lines, words, and bytes in a file.
**Syntax:** `wc [OPTION] [FILE]`
`wc -l "document.txt"`
`wc -w "examplefile.txt"`

# 9. tr
**Purpose:** Translate or delete characters.
**Syntax:** `tr [OPTION] SET1 [SET2]`
`cat "document.txt" | tr 'a-z' 'A-Z'`
`cat "examplebook.txt" | tr ',' ';'`

# 10. diff
**Purpose:** Compare files line by line.
**Syntax:** `diff [OPTION] FILES`
`diff -y "fileA.txt fileB.txt"`
`diff --color=auto "fileA.txt fileB.txt"`

# 11. grep
**Purpose:** Search for patterns in files.
**Syntax:** `grep [OPTION] PATTERN [FILE]`
`grep 'apple' "document.txt"`
`grep -i 'orange' "document.txt"`
`grep -r 'pattern' "/path/to/directory"`

# 12. awk
**Purpose:** Process and display text.
**Syntax:** `awk [OPTION] [program] [input-file]`
`awk '{print $2}' "document.txt"`
`awk -F, '{print $1, $3}' "/etc/passwd"`
`awk 'NR > 2 {print}' "dracula.txt"`
`awk '{print length($0)}' "document.txt"`

# 13. sed
**Purpose:** Stream editor for performing operations on files and standard output.
**Syntax:** `sed [OPTION] {script} [file]`
`sed 's/apples/bananas/' "example.txt"`
`sed '1,$s/old/new/' "document.txt"`
`sed '/**.md/d' "document.txt"`
`sed '1,4 s/past/future/' "book.txt"`
