# Learning Git and GitHub
This is the repository for the LinkedIn Learning course Learning Git and GitHub. The full course is available from [LinkedIn Learning][lil-course-url].

![Learning Git and GitHub][lil-thumbnail-url] 
aabbbcccc
main wala 112
Version Control lets you manage changes you've made to files over time, and is an essential skill for developers to master. Git is by far the most popular version control system on the web. In this fast-paced course, Ray Villalobos shows you the fundamental commands that you need to work with most Git projects. He explains how to use checkpoints called commits, which let you leave messages documenting what happened at each checkpoint, as well as how to create branches that are alternate versions of your project that you can work on without changing the original. Plus, he shows how to work with the popular GitHub website to explore existing projects, clone them to your local hard drive, and use them as templates for your new projects.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

### Instructor

Ray Villalobos 
                            
Author, Multimedia Developer

                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/ray-villalobos).

[lil-course-url]: https://www.linkedin.com/learning/learning-git-and-github-14213624
[lil-thumbnail-url]: https://cdn.lynda.com/course/2421501/2421501-1629911102468-16x9.jpg
