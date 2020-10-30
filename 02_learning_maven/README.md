# Lesson 02 Learning Maven

You will have to use a build automation tool of some sort in this class. If you proceed in a career in software construction you will have to use several build automation tools in your career.

You have probably heard of Gradle, Ant, Maven, Buildr, and etc.  Since this course deals with Java, you will be using maven (later you might be using make, but for now just maven).

Your assignment is to do the following:

1. Create a branch for this lesson.
1. Get maven running on your machine
1. Create a folder called:
    
    ```
    (last)_(first)_(M.I.)
    ```

1. Using whatever terminal you prefer, iside the folder you created, use maven to generate project with the group id as:

    ```
    com.(lastName).app
    ```

1. When successful, cd into that doorectory and ensure the pom is correct. (you can test if it was successful by building your project using maven and running it)
1. Capture the files you created when you had maven generate your project as a commit.
    
    * By default, we've included a .gitignore file that will ignore files generated in the target directory. This is expected.

1. In your folder, create a README.md file and write the following:

    * A little bit about what maven is
    * a brief summary about what happens in each of the most common default maven lifecycle phases.

1. Push your branch to github, create a pull request, review other peoples work, merge when ready. 
