Linux Lab
 ----------
 
    1- Create a user account with the following attribute
    •  username: islam
    •  Fullname/comment: islam yahia
    •  Password: islam
    

    2- Create a user account with the following attribute
    •  Username: baduser
    •  Full name/comment: Bad User
    •  Password: baduser

    3- Create a supplementary (Secondary) group called pgroup with group ID of 30000

    4- Create a supplementary group called badgroup
 
    5- Add islam user to the pgroup group as a supplementary group
    
    6- Modify the password of islam's account to password
    
    7- Modify islam's account so the password expires after 30 days

    8- Lock bad user account so he can't log in
    
    9- Delete bad user account
    
    10- Delete the supplementary group called badgroup.

    11- Create a folder called myteam in your home directory and change its permissions to
     read only for the owner.
     
    12- Log out and log in by another user
 
    13- Try to access (by cd command) the folder (myteam)
   
    14- Using the command Line
        ◦ Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute and execute only for the others (using chmod in 2 different ways)
        ◦ change your default permissions to be as above.
        
    15- What is the maximum permission a file can have, by default when it is just created? And what is that for directory.
    • For Files is 644 
    • Default permission is 666  = 110 110 110 
    • Umask value is 002  = 000 000 010
    • Abstract them = 644 110 110 100
    • For Directories  is 755
    • Default permission is 777 = 111 111 111
    • Umask value is 002  = 000 000 010
    • Abstract them = 755 11 101 010
    16- Change your default permissions to be no permission to everyone then create a directory and a file to verify.
   
    17- What are the minimum permission needed for:
        ◦ Copy a directory (permission for source directory and permissions for target parent directory)
        ◦ Copy a file (permission for source file and and permission for target parent directory)
        ◦ Delete a file
        ◦ Change to a directory
        ◦ List a directory content (ls command)
        ◦ View a file content (more/cat command)
        ◦ Modify a file content
        ◦ Copy a Directory.
        
    18- Create a file with permission 444. Try to edit in it and to remove it? Note what happened.
      
    19- Using vi write your CV in the file mycv. Your CV should include your name, age, school, college, experience,…
      
    20- Open mycv file using vi command then: Without using arrows state how to:
        ◦ Show all lines numbers
          1
        ◦ 2 MY CV
        ◦ 3 
        ◦ 4 Name: Ola Youssef Mohammed
        ◦ 5 Age: 21
        ◦ 6 School: Sadat Academy for Management Sciences
        ◦ 7 College: Computer Science
        ◦ 8 Experience: Software Development Internship                                                                               
      
    21- List the available shells in your system.
 
    22- List the environment variables in your current shell.
    
    23- List all of the environment variables for the bash shell.
    
    24- What are the commands that list the value of a specific variable?

    25- Display your current shell name.

    26- Execute the following command :
        ◦ echo \ then press enter
        ◦ What is the purpose of \ ?
        ◦ The \ character at the end of a command tells the shell that the command is not complete and more input is needed. 
        ◦ Notice the prompt ”>” what is that? and how can you change it from “>” to “:”. (Search PS1, PS2, …)
        ◦ When you press Enter, the shell displays a > prompt, waiting for additional input.
        
    27- Create a Bash shell alias named ls for the “ls –l” command
      
