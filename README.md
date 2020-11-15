# CultData_ExamProject
This is a repository that will contain our exam project, which consists of a script that can visualise some of your Netflix activity.

The script is in RMarkdown format and should be able to run, so long as you clone the entire repository yourself. 
You can choose to use the .csv file that is provided in this repository, which consists of my (Nanna's) own viewing history, and therefore you do not need to have a Netflix account to run this script. 

However, if you are interested in visualising your own data from your own Netflix account, do the following:

- Log into your Netflix account on desktop. 
- Click on your personal account (each person on the Netflix account has their own viewing history)
- Click on the icon in the top right corner 
- Click "Account"
- Scroll down and click on your accounts icon
- Next to "Viewing History" click on "View"
- Scroll down and click "Download all" 

Now you have a file called "NetflixViewingHistory.csv" 

It's important that the .csv file you want to use is in the same folder as your working directory. 
Also, seeing as the Netflix data that we provided is already called "NetflixViewingHistory.csv", you may want to rename the file you downloaded yourself.

Note: while the script should be able to run from the get go, we identified some possible bugs that might occur. These are pointed out in the script underneath each chunk of code. Here you can also find explanations of things that might not be obvious when looking at the plots.

---
Files included in this repository (so far):

- An Rmarkdown with the code used for setup and visualisation
- A .csv file with an example of Netflix viewing  history
- An html file which contains the knitted code from the Rmarkdown using the data from the .csv file
