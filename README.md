# resumeGen
                                                    ______         
               ________  _______  ______ ___  ___  / ____/__  ____ 
              / ___/ _ \/ ___/ / / / __ `__ \/ _ \/ / __/ _ \/ __ \
             / /  /  __(__  ) /_/ / / / / / /  __/ /_/ /  __/ / / /
            /_/   \___/____/\__,_/_/ /_/ /_/\___/\____/\___/_/ /_/ 
                                                                   

Generate my own Resume and Cover Letter using Bash Scripting and Unix commands. For computer science related job posting only. 

More general job posting resume generating script in the future.

## Requirement:

* This script works with macOS and Linux
* [Headless Chrome convert html to pdf](https://developers.google.com/web/updates/2017/04/headless-chrome) or if you already have google Chrome installed on your Mac

* Some set up, including setting your own Resume format, with names, contact number, keywords for job you're looking for, the work experience files. If you want to edit these keywords file,
```
  cd .files
  ls
```
Adding function and modifiers will be update in the future

### Installing

* Git clonning
Copy these steps for installing into your terminal. Run this script using terminals.
```
  cd ~/Desktop
  git clone https://github.com/etarakoem/resumeGen.git 
```

### Executing program
* Before running, update this repo by running
```
 ./update
```

* Alternatively, you can simply updating the Path to ensure this tool runs without issues (Copy and paste to your terminal)
```
  cd resumeGen
  export PATH=$PATH:$(pwd)
```

#### For Public use:

* To check for keywords scanned from job posting
```
  kwCheck
```

* Access menu:
```
  menu
```

* Editing your Contact info in menu 1:
```
  menu
  
  Would you like to renew your experience or add to the existing list?


 1) Setting contacts information


 2) Renew experience (Caution, this will overwrite your existing experience!)


 3) Adding to exisitng experience list  


 4) Customizing Profile Summary 


 5) Editing Qualification Summary list


 6) Setting Education


 7) Adding keywords list

Choose 1,2,3,4,5,6,7 or q to quit: 1

```
Then follow the prompt to set up your name, address, email

```
  setname
```	
#### For recruiters to see how Phuc Hua's resume and cover letter been created
* Get the Job posting you want ready, then copy them into the clipboard
To get a full package (resume + cover letter):

```
  package
```

When is asked for the Company requirement, remember to Enter and press Ctrl + D to continue.

* To generate only the resume:
```
  resume
```
The list of single Resume can be found in SingleResume folder

* To generate only the cover Letter:
```
  cover
```
The list of single Cover Letter can be found in SingleCover folder

* Generating Alternative cover letter:
```
  package <number>
  cover <number>
```
the default is 1 for Scripting Job requirement, and none for Cyber security related.


## Authors

Contributors by Samuel

## Requirement:

- [Headless Chrome convert html to pdf](https://developers.google.com/web/updates/2017/04/headless-chrome) or if you already have google Chrome installed on your Mac

- Some set up, including setting your own Resume format, with names, contact number, keywords for job you're looking for, the work experience files. If you want to edit these keywords file,
```
  cd .files
  ls
```
- Samuel -
