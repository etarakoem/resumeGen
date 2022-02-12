# resumeGen
                                                    ______         
               ________  _______  ______ ___  ___  / ____/__  ____ 
              / ___/ _ \/ ___/ / / / __ `__ \/ _ \/ / __/ _ \/ __ \
             / /  /  __(__  ) /_/ / / / / / /  __/ /_/ /  __/ / / /
            /_/   \___/____/\__,_/_/ /_/ /_/\___/\____/\___/_/ /_/ 
                                                                   

Generate my own Resume and Cover Letter using Bash Scripting and Unix commands. For computer science related job posting only. 

## Update:
-- Version 2.0 (Feb 11, 2022) --
Greate news! ResumeGen is now open for public use, with customizable resume and you can craft your own set of Keywords!

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

### For Public use:

* To check for keywords scanned from job posting
```
  kwCheck
```

* Access menu:
```
  menu
```
* Editing your Contact info in menu 1:
Go for option 1 in menu to set your name, address and email

![menu 1](https://user-images.githubusercontent.com/50989367/153696046-00050605-772a-4df6-933c-175b525aa589.png)

* Making a new set of experience with menu 2:

![menu 2](https://user-images.githubusercontent.com/50989367/153696000-6563301d-a280-4912-8818-8cc04d526258.png)

* Adding to your existing experience list with menu 3:

![menu 3](https://user-images.githubusercontent.com/50989367/153696088-cfd22b57-da4d-4362-af67-3fd1f3f86fc5.png)

* Customize your 1 sentence Profile Summary with menu 4:

![menu 4](https://user-images.githubusercontent.com/50989367/153696119-6136980f-ab2f-489c-8415-6b99b6ca949f.png)

* Adding to your existing Qualification Summary List for scanning keywords with menu 5:

![menu 5](https://user-images.githubusercontent.com/50989367/153696415-d449b566-ca5a-4ca2-97c0-d48b2868959f.png)

* Adding your Education history with menu 6:

![menu 6](https://user-images.githubusercontent.com/50989367/153696469-7e1fff30-c544-4457-827e-f3c9a783d8e6.png)

* Setting up your own Keyword list with menu 7:

![menu 7](https://user-images.githubusercontent.com/50989367/153696693-4fce563e-4e17-411a-a7e4-92c2dbab5792.png)

![menu 7 1](https://user-images.githubusercontent.com/50989367/153696765-9f6b6f81-30f3-45cd-90bd-c78eba6dd124.png)

You can even remove your existing keywords with this follow up options:

![menu 7 remove](https://user-images.githubusercontent.com/50989367/153696725-55d7a545-8422-4aef-b0db-4fdd612a66a4.png)

* Making your own Resume base on any job posting by this built-in scanning:

```
  reumegen
```
Gather your keyword ready. The more you have, the better classifies, and be sure to fill tons of qualification summary in your file so they can alter and select corresponding job!

![Screen Shot 2022-02-11 at 11 55 06 PM](https://user-images.githubusercontent.com/50989367/153697278-f327b2fb-0ea6-4785-afd4-14209fc84701.png)

Then paste the job posting directly to the screen.

![Screen Shot 2022-02-11 at 11 56 05 PM](https://user-images.githubusercontent.com/50989367/153697298-2d6d662a-f3b8-454c-b63c-bcaf220fbb36.png)

Remember, press 'Enter' before pressing Ctrl + D to continue

![Screen Shot 2022-02-11 at 11 56 51 PM](https://user-images.githubusercontent.com/50989367/153697318-4987ff8d-3e66-41a6-983c-8063ab3e1048.png)

An analyze screen will show up to show how many keywords match with your own keywords, determine the type of job

![Screen Shot 2022-02-12 at 12 05 51 AM](https://user-images.githubusercontent.com/50989367/153697566-905a5edc-d1fd-4c48-9177-13f85cad7de9.png)

Then you'll be prompt to choose how to edit your resume.
Choose both if your resume content is short, choose only qualification summary if you have many.

![Screen Shot 2022-02-12 at 12 06 39 AM](https://user-images.githubusercontent.com/50989367/153697584-e5be2e7a-24d1-4bea-b2f5-27385b7c331b.png)

### Sample result:

Following the steps above, and a sample job posting would result in this resume in pdf: 
![Screen Shot 2022-02-12 at 12 12 18 AM](https://user-images.githubusercontent.com/50989367/153697730-911ae970-7b93-4884-b705-e9fa4330ba92.png)


### For recruiters to see how Phuc Hua's resume and cover letter been created
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
Remember to have your keywords file ready first

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
