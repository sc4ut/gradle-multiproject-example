This project is just to show my problem with overwriting a custom task.

When executing the generateAvro task, i wont to overwrite in my subprojects the source folder the task is using to avoid additional objects in the classpath of my other projects.

But only adding a closure in the subprojects build.gradle seems to not work. 