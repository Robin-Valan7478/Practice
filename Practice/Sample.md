- ## __GIT COMMANDS:__ 

	- How to create a text file using Terminal:
		
		- To create a text file using the terminal, first type echo. "echo" is a command that simple displays a message on the screen. The code should be echo Filename.txt. It will create a text file.

			-echo Robin.txt			-> it will create a text file named Robin
			-echo "Hello World" > Robin.txt	-> It will create a text file named Robin and stores the content in double quotes.
			-type Robin.txt 			-> It will display the content in the Robin.txt
			-notepad Robin.txt		-> It will open the text file


		- To create a repository and store a text file in the repository and connect it with GitHub:

		First download GIT from browser and to create a repository there are two ways. One is the easiest way (Automatic mode) by clicking files in GitHub and creating a new repository; the other one is using the GIT terminal(manual mode). To create a repository, mkdir Repository name and type git init

			-mkdir Internship	-> Creates a folder called Internship
			-git init 		-> Creates an empty repository
	
		-To add a text file, we can create it using the terminal or in a simple way. Using the terminal, we should give the corresponding command to add the file to the repository

			-git add Sample.txt	-> It adds a text file named Sample in the Internship repository.

		-To check the status of the repository,

			-git status 		-> It shows the commits made and the untracked files and changes made locally.


		-To commit a file in the repository,
		
			-git commit -m "first Commit"	->  It will create a new commit in the Git with the message "first commit" and saves the current changes made in the repository

		-To push the file, 

			-git push origin main 	-> It will upload the committed changes from our local GIT to GitHub, i.e., it uploads(pushes) the committed changes from our local main branch to the main branch. We can access the file from the Other system also.

		-To view the remote repository URLs,

			-git remote -v 		-> Lists the remote repositories linked with our local Git repository along with fetch and push URLs.





- ## __POWERSHELL:__

	- To create a text file we can use different codes to create a file. we can use echo "Hello World" > sample.md, and it creates a new md file with the contents Hello World. There is also an another way to create a file in powershell which is Set-Content Sample.md "Hello World", Set-content is a powershell command that writes text to a file, whereas echo command is used for displays output in console. if we want to add contents in echo we should    append(>>) it, ex: echo "New line" >> sample.md. We can also use the Add-Content sample.md "new line".

	- To add the file in GitHub, we can use the same commands used in GITCMD.
                                git add Sample.md
                                git commit -m "First Commit"
                                git push origin main

	- pwd -> To print the directory

	- ls  -> To list files and folders in the current directory

	- mkdir Sample -> Creates a new directory called Sample

	- rm sample.txt -> Deletes the file sample.txt

	- rm -r Internship -> Deletes the Internship folder

	- cp smaple.txt Internship\ -> Copies the sample.txt to the Internship folder

	- mv sample1.txt sample2.txt -> It moves or renames sample1.txt to sample2.txt

	- cat sample.txt / type sample.txt -> Displays the contents of sample.txt

	- clear -> It will clear the powershell screen





- ## __Some basic Markdown Syntax:__

	- ___Headings___ #_Heading, ##_Sub-Heading, ###_Sub-Sub-heading. The text size will be larger for headings and will be smaller for sub-heading and vice versa.

	- ___Bold:___ To represent a text in bold format. we have to use double quote two times in starting and ending __ (Your text here) __.For example, __ HELLO WORLD __.
              
	- ___Italic:___ To represent a text in italic format, we have to use double quote one time in starting and ending _ (Your Text Here) _. For example, _ Hello Surfboard _

	- ___Bold & Italic:___ To represent a text in both bold and italic format, we have to use double quote three times in starting and ending of a text. For example, ___ Hello Guys ___.

	- ___Unordered Lists:___ To represent a item in lists we use "Unordered lists". It shoulde be represented as (-)before an statement.
For Example,
             - Item 1
             - Item 2
                     - Sub Item 1
                     - Sub item 2
	- ___Ordered Lists:___ To represent a item in an ordered lits we use "Ordered Lists". It can be represented using numbers.
For Example,
             1. Item 1
             2. Item 2
                     1. Sub Item 1
                     2. Sub Item 2


	- ___Links:___  To attach a URL link with the word, we use Links. For example, [Google](https://www.google.com)

	- ___Tables:___ To create a table, there is a syntax, we should use pipe(|), for example:

                                                                        | Name | Age | Country |
                                                                        |______|_____|_________|
                                                                        |Robin | 21  | India   |
                                                                        |Rohan | 25  | USA     |




- ## ___VIM:___

	- VIM stands for _Vi IMproved_. It is a also a text editor used in command-line interface(CLI). It can be used on Linux, macOS, and Windows.VIM is very useful than other editors. It is very fast and lightweight, easily customizable and it works in terminal itself.

	- Install the latest VIM application and run it in the terminal. To open VIM, use this code "vim day_six_report.md". It will open a new     terminal in which we can type our content. But, before typing we have to give "i" or "a" or "o" command then only it will go to insert mode so that we can  type.

	- Some basic VIM commands:
		- i -> insert before cursor

		- a -> insert after cursor

		- 0 -> opens a new line below

		- Esc key -> It will exit insert mode.

		- :w -> It will save the file.

		- :q -> It will quit the file.

		- :wq -> It will save and quit the file.

		- :q! -> It will quit the file without saving.

		-  dd -> It will delete the current line.

		-  yy -> It will copy a line.

		-  p  -> Paste







