# 0x02. Shell, I/O Redirections and filters
  
 [0-Hello_World](./0-Hello_World)  - Write a script that prints “Hello, World”, followed by a new line to the standard output. 
  
 [1-Confused_smiley](./1-Confused_smiley) - Write a script that prints the effective username of the current user.  
  
 [2-Let's_display_a_file](./2-Let's_display_a_file) - Display the content of the /etc/passwd file.
  
 [3-What_about_2?](./3-What_about_2?) - Display the content of /etc/passwd and /etc/hosts
  
 [4-Last_lines_of_a_file](./4-Last_lines_of_a_file) - Display the last 10 lines of /etc/passwd

 [5-I'd_prefer_the_first_ones_actually](./5-I'd_prefer_the_first_ones_actually) - Display the first 10 lines of /etc/passwd 
  
 [6-Line_#2](./6-Line_#2) - Write a script that displays the third line of the file iacta.
The file iacta will be in the working directory
You’re not allowed to use sed
  
 [7-It_is_a_good_file_that_cuts_iron_without_making_a_noise](./7-It_is_a_good_file_that_cuts_iron_without_making_a_noise) - Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
  
 [8-Save_current_state_of_directory](./8-Save_current_state_of_directory) - Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

 [9-Duplicate_last_line](./Duplicate_last_line) - Write a script that duplicates the last line of the file iacta
The file iacta will be in the working directory

 [10-No_more_javascript](./10-No_more_javascript) - Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.  

 [11-Don't_just_count_your_directories,make_your_directories_count](./11-Don't_just_count_your_directories,make_your_directories_count) - Write a script that counts the number of directories and sub-directories in the current directory.
The current and parent directories should not be taken into account
Hidden directories should be counted  

 [12-What’s_new](./12-What’s_new) - Create a script that displays the 10 newest files in the current directory.
Requirements:
One file per line
Sorted from the newest to the oldest
  
 [13-Being_unique_is_better_than_being_perfect](./13-Being_unique_is_better_than_being_perfect) - Create a script that takes a list of words as input and prints only words that appear exactly once.
Input format: One line, one word
Output format: One line, one word
Words should be sorted

[14-It_must_be_in_that_file](./14-It_must_be_in_that_file) - Display lines containing the pattern “root” from the file /etc/passwd

[15-Count_that_word](./15-Count_that_word) - Display the number of lines that contain the pattern “bin” in the file /etc/passwd

[16-What's_next?](./16-What's_next?) - Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

[17-I_hate_bins](./17-I_hate_bins) - Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

[18-Letters_only_please](./18-Letters_only_please) - Display all lines of the file /etc/ssh/sshd_config starting with a letter.
include capital letters as well

[19-A_to_Z](./19-A_to_Z) - Replace all characters A and c from input to Z and e respectively.

[20-Without_C,_you_would_live_in_hiago](./20-Without_C,_you_would_live_in_hiago) - Create a script that removes all letters c and C from input.

[21-esreveR](./21-esreveR) - Write a script that reverse its input.

[22-DJ_Cut_Killer](./22-DJ_Cut_Killer) - Write a script that displays all users and their home directories, sorted by users.
Based on the the /etc/passwd file
