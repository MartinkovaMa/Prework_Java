![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)

# Java Prework
> A few important pieces of information

Before starting to solve the tasks, please read the following guidelines.

## How to start?
1. Create a [*fork*](https://guides.github.com/activities/forking/) of the repository with tasks.
2. Clone the repository to your computer. Use the command git clone repository_address.
   The repository address can be found on the repository page by pressing the "Clone or download" button.

   Pay attention to use the address of your own fork, it should look according to the scheme: ```https://github.com/your-login/repository_address```

3. Import the project as a Maven project, according to the following guidelines:
   * In IntelliJ, choose: File –> New –> Project from Existing Sources...
   * Indicate the location of the cloned project directory and confirm.
   * Then in the new window, select: Import project from external model and indicate Maven
   * Choose the option: Finish, (in IntelliJ before 2020: Next –> Next –> Next –> Finish)

4. Solve the tasks and commit the changes to your repository. Use the commands git add file_name.
   If you want to add all changed files use `git add .`
   Remember that the dot at the end is important!
   Then commit the changes with the command `git commit -m "commit_name"`
5. Push the changes to your repository on GitHub. Use the command `git push origin main`.
6. Create a [*pull request*](https://help.github.com/articles/creating-a-pull-request) to the original repository when you finish all tasks.

### Layout of this repository
Here you will find tasks for the classes. Upload them systematically to GitHub.
   * src/main/java/pl/coderslab/afirstprogram
   * src/main/java/pl/coderslab/bvariablesandoperators
   * src/main/java/pl/coderslab/cflowcontrol
   * src/main/java/pl/coderslab/darrays
   * src/main/java/pl/coderslab/eparametrystartowe

Solve individual tasks in the appropriate files.

Tests for tasks operate on messages displayed in methods. Avoid additional calls, e.g.:

```java
System.out.println("some message");
```
The exercise repository will be deleted 2 weeks after the course ends. This will also remove all forks that are made from this repository.
