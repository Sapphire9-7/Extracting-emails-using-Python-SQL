# Extracting-emails-using-Python-SQL
This is a Python model that takes in a text file as an input and uses SQLITE3 to locate the emails in the file and extract the domain names and how many times emails have been received from each domain. The program follows this schema to maintain the counts.
- CREATE TABLE Counts (org TEXT, count INTEGER).
