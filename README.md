# Financial Friend: Dr. Stox
This is our project for 2024 AthenaHacks: a stock simulator using generated stock data to help people, especially people who are financially illiterate, learn about finance in a fun and approachable way! We use Flask to render our HTML, CSS, and Javascript files. 

To run our project:
1.) Create a virtual environment if desired by running `python -m venv venv`. Activate by running `source venv/bin/activate` for Unix and `venv\Scripts\activate` for Windows.
2.) Run `pip install requirements.txt` to download dependencies for the project.

To run the application, make sure you are in the backend folder. Run the python file, server.py. 

Here is the link to our submitted project on Devpost for the hackathon: https://devpost.com/software/athenahacks-project?ref_content=my-projects-tab&ref_feature=my_projects. 

Github commands:

We'll be using pull, add, commit, and push as git commands.

All the files in this project are called a repository. There is the remote repository, which is what is shown at https://github.com/llennemann/Financial-Friend-Dr-Stox, and you have a local version that is on your machine (you downloaded the repository onto your computer when you ran the git clone command). The remote repository is also known as "origin" and should be "the truth" or like a functional version. Your local version can have whatever changes you're making right now. When you have made changes and your local repository works, you can then add and commit your changes. It is important for the remote and your local repositories to be kept up to date with each other. 

```
git pull
```
pulls all changes from the remote repository to your local repository.

```
git add fileName1 fileName2 fileNameEtc
```
adds your changes to be ready to be committed. Be sure to add every file that you changed (feel free to ask for help if you're getting errors here)

```
git commit -m "Your message"
```
commits your added changes and you can say a quick message (just a few words) about what you changed


```
git push origin main
```
pushes all your changes from your local repository to the remote repository

