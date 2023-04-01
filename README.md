# WordCount
The repository use MapReduce framework and Hadoop architecture to solve the simplw word count problems.

The project is written in Java and run with Gradle wrapper (gradlew).

## Execution
Make sure you have the `gradlew` file in the current project folder.

In the proejct root folder, run the command
```=sh
./gradlew wordcount -Pinput="input.txt" -Poutput="output"
```
In the output folder, you will see the counting result in the file `part-r-00000`.

> 1. Make sure the output folder does not exist, otherwise there would throw an error.
> 2. If you have the problem of executing the gradlew file, try using `chmod` command to add execution privilege on the file.
> 3. If you try to use other documents, just replace the content in `input.txt`.
