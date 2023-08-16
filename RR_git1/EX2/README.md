#  Exercise 2: adding commits (go down for more)
In your RR_git1 directory, initiate a git repository named EX2
(check git status and git diff to get a better feel of this)

cd ..
git init EX2

Go inside the new repository.
cd EX2

Create a file named README.md, add a single line of text inside, save the file [hint: you can use echo or create it manually with e.g. Notepad]
(check git status and git diff to get a better feel of this)

git status
echo "a line of text" > README.md
git status

Exercise 3: adding commits (go down for more)
Add another line of text to the file you created.
echo "add a second line of text" > README.md

Create a new file named “readme.txt”.
touch readme.txt

Exercise 4: using .gitignore
Create data/data1.csv file and fill it with a random data line (can be just comma-separated text, it doesn’t matter), check status and diff
echo -e "Var1, Var2\n5, 7" > data/data1.csv
git status
git diff


