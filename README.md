# GitHub Classroom Quick Start

### Requirements
- You will need a Github account. If you don't have one already, [signup here](https://github.com/join).
- [Git](https://git-scm.com/downloads) to clone and submit the assignment. On Windows, we recommend [Git Bash](https://gitforwindows.org).

### Accepting an assignment
Your instructor will share a link to the assignment with you. The video below demonstrates how to accept the assignment and access the repository.

**Important:** please make sure to select *your* correct NetID when self-identifying.

[![Watch the video](https://img.youtube.com/vi/owXDy_bGRmA/hqdefault.jpg)](https://youtu.be/owXDy_bGRmA)

### Cloning the repository
Once you accept an assignment, GitHub classroom will create a repository for you containing the starter code. The repository URL will have the format ``https://github.com/CISC422/<assignment_name>-<your_username>``.
The video below shows how to clone the assignment's repository from the command line. Alternatively, you may use your favourite IDE or [GUI tool](https://git-scm.com/downloads/guis/).

[![Watch the video](https://img.youtube.com/vi/6PcjaXI5vu8/hqdefault.jpg)](https://youtu.be/6PcjaXI5vu8)

Example:
```
git clone https://github.com/CISC422/example-assignment-holdmypoutine my_submission
ls my_submission
```

### Working on the assignment
Follow the instructions in the assignment's README.md file to solve, build, and test your assignment. You may commit and push your changes to the repository at any time. The last commit pushed to the **master** branch **before** the assignment's deadline is considered your final submission.

**Important:** After the deadline, your push access to the repository will be automatically revoked and *you will not be able to perform any further modifications*. However, you can still fork a copy of the repository into your own account and perform any modifications there. Note that changes past the deadline won't be considered unless a *valid reason is submitted and approved by the course instructor*.

[![Watch the video](https://img.youtube.com/vi/1l_pffeR7u8/hqdefault.jpg)](https://youtu.be/1l_pffeR7u8)

Example:
```
# add all the files you've modified (you can also use `git add -A` to add all changed files)
git add src/main/java/Solution.java
# commit the changes to your local repository
git commit -m 'Solved!'
# push the changes to your GitHub repository
git push -u origin master
```

### Interacting with the TAs
If you're facing problems or have any questions, feel free to open an issue in your repository and tag the course TAs.

## IDEs
Feel free to use any IDE to work on your assignment. Many IDEs such as [IntelliJ IDEA](https://www.jetbrains.com/idea/) and [Eclipse](https://www.eclipse.org/downloads/) have built-in support for git. 
Many assignments in this course uses the [Gradle](https://gradle.org/) build system. Make sure your IDE supports Gradle projects.

### IntelliJ IDEA
The video below demonstrates how to clone, build, and run an example Gradle-based assignment using IntelliJ IDEA.

[![Watch the video](https://img.youtube.com/vi/_mm_fBIS4Fw/hqdefault.jpg)](https://youtu.be/_mm_fBIS4Fw)

### Eclipse
The video below demonstrates how to clone, build, and run an example Gradle-based assignment using Eclipse.

[![Watch the video](https://img.youtube.com/vi/djMjKRyexc0/hqdefault.jpg)](https://youtu.be/djMjKRyexc0)

## Resources
- [A simple guide to Git](https://rogerdudler.github.io/git-guide/).
- GitHub uses Markdown everywhere, including for formatting messages in issues and pull-requests. If you want your questions to look nice, checkout [this short Markdown tutorial](https://guides.github.com/features/mastering-markdown/).
