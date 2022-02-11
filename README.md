# resumeGen
                                                    ______         
               ________  _______  ______ ___  ___  / ____/__  ____ 
              / ___/ _ \/ ___/ / / / __ `__ \/ _ \/ / __/ _ \/ __ \
             / /  /  __(__  ) /_/ / / / / / /  __/ /_/ /  __/ / / /
            /_/   \___/____/\__,_/_/ /_/ /_/\___/\____/\___/_/ /_/ 
                                                                   

Generate my own Resume and Cover Letter using Bash Scripting and Unix commands. For computer science related job posting only. 

More general job posting resume generating script in the future.

### Dependencies

* macOS with bash and zsh
* Google chrome installed


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

* Get the Job you desire ready, then copy them into the clipboard
To get a full package (resume + cover letter):

```
  ./package
```

When is asked for the Company requirement, remember to Enter and press Ctrl + D to continue.

* To generate only the resume:
```
  ./resume
```
The list of single Resume can be found in SingleResume folder

* To generate only the cover Letter:
```
  ./cover
```
The list of single Cover Letter can be found in SingleCover folder

* To check for keywords scanned from job posting
```
  ./kwCheck
```

* Generating Alternative cover letter:
```
  ./package <number>
  ./cover <number>
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
Adding function and modifiers will be update in the future

- Samuel -
