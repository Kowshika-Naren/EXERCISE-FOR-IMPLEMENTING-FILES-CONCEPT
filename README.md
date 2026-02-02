# EXERCISE-FOR-IMPLEMENTING-FILES-CONCEPT
.file = "sample.txt"

# Write and append data
with open(file, "w") as f:
    f.write("Python is easy to learn.\n")
    f.write("File handling is important.\n")

with open(file, "a") as f:
    f.write("Practice makes perfect.\n")

# Read file
with open(file, "r") as f:
    text = f.read()
    print("File Content:\n", text)

# Count lines, words, characters
print("Lines:", text.count("\n"))
print("Words:", len(text.split()))
print("Characters:", len(text))

# Search word
print("Python count:", text.count("Python"))

output:File Content:
 Python is easy to learn.
File handling is important.
Practice makes perfect.

Lines: 3
Words: 12
Characters: 77
Python count: 1
