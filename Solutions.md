cd /mnt/c/users/USER/Downloads

1. (B) Extract the "challenges.tar.gz" archive; you'll need its contents to
   solve some of the challenges.

##unzip command-line-challenges-master.zip -d command-line-challenges

tar -xf challenges.tar.gz

 

 

2. (B) Change your working directory to the "challenges" directory that was
   created when you extracted "challenges.tar.gz"

 


3. (B) List the contents of the "challenges" directory. 


4. (B) Create a new directory named "foo".
 

5. (I) Create a new directory named "foo/bar/1/2/3"


 

6. (B) Remove the directory "foo" and all of its contents
 

7. (B) Print the text "Hello World".
 

8. (B) Create a file named "hello.txt" that contains the text "Hello World".
 

9. (B) Create an empty file named "empty.txt"
 

10. (B) Remove the file "empty.txt"
 

11. (I) Find a second way to solve challenge 9.
 

12. (I) Find a third way to solve challenge 9.

13. (B) Copy "hello.txt" and name the copy "goodbye.txt".
 

14. (B) Rename "goodbye.txt" to "hello_copy.txt".
 

15. (I) Prove that the contents of "hello.txt" and "hello_copy.txt" are
    identical.
 
The -s flag will let you know when two files are identical, otherwise it will report the differences

16. (B) Concatenate the contents of "hello.txt" and "hello_copy.txt" and store
    the result in a file named "2_hellos.txt".

 

17. (B) Get the full path of your present working directory ("challenges").
 

18. (B) List the contents of the "challenges" directory (like challenge 3), but
    show the permissions for each file.
 

19. (B) Append some text to the end of "restricted.txt". It's OK to do this in
    2 steps.
 
20. (B) Run the "hello_executable" program.

21. (B) Run the "challenge_20" program. It's OK to do this in 2 steps.

22. (B) Compile and run "compile_me.c". It's OK to do this in 2 steps.

23. (A) Run the "redirect" program and collect all of its output in a file
    named "output.txt".

24. (B) Get the current date and time.
 

25. (B) Show all of the running processes on your computer.
 

26. (B) Show the number of processors/cores in your computer.

27. (B) Find out what version of the Linux kernel is currently running.

28. (B) Find the file in the "bunch_of_files/" directory that contains the string:
    "You found the needle in the haystack!"
 

29. (B) Print the first 25 lines of people.csv.
 

30. (B) Print the last 25 lines of people.csv.
 
31. (I) Display just the differences between greeting1.txt and greeting2.txt
 

32. (I) Print "Hello", then wait 5 seconds, then print "world!".

33. (I) Create a 1MB file full of zeros.

34. (I) Create a 2MB file full of random data.

35. (I) Count the number of lines in README.txt.
 

36. (B) Display the contents of README.txt in reverse (last line first).
 

37. (I) Display all of the last names in people.csv.
cut -d , -f 2 people.csv
 

38. (A) Count the number of unique last names in people.csv.
 

39. (A) Did you accidentally count the CSV header in the previous challenge?
Ermm…yes
 
40. (A) There's a second way to exclude the CSV header from your count. Find it.
 
41. (A) Now that you've found two ways to correctly count the number of unique
    last names in people.csv, can you prove whether or not one is more efficient
    (faster) than the other?

42. (A) Count the number of people with the first name "Josiah" in people.csv.
 

43. (I) Count the number of files (not directories) in the "challenges" directory .

44. (I) Count the number of subdirectories in the "challenges" directory.

45. (I) Remove all files with "deleteme" in the name.

46. (I) In challenge 28 you found a file. Replace the string "You found the
    needle in the haystack!" with "The needle has been removed."

47. (A) Transform people.csv from ',' delimited to '|' delimited and save the result in people_pipe.csv.

48. (A) Find all of the files in "bunch_of_files/" that are duplicates of "file001.rand".

49. (A) Execute this challenge in exactly 2 steps

    1) (B) Create an empty file named "supercalifragilisticexpialidocious.txt".
    2) (A) Remove "supercalifragilisticexpialidocious.txt". Your command may
           only use a maximum 5 total characters (no wildcards or globs).

50. (A) Create a set of empty files. Each file has a name in the form "L-N.txt"
    where L is a letter and N is a number. Valid letters are a,b,c, while valid
    numbers are 1,2,3. Create all permutations (total of 9 files). Make your
    command as short as possible. I can do it in 25 characters, can you do
    better?

