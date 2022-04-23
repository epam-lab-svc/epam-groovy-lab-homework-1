# Groovy Lab

## How to run and test your code

The tasks repository has a docker-compose file with a gradle image. To run a container,
run in your terminal:
```bash
docker-compose run gradle
```
In this container you can run and test your code. The recommended flow it to
edit `app/src/main/groovy/groovylab/App.groovy` file and then run
```bash
gradle run
```
in the container.

Example of `app/src/main/groovy/groovylab/App.groovy`:
```groovy
package groovylab

class App {
    static void main(String[] args) {
        println Task07.encryptThis("hello world")
    }
}
```

**IMPORTANT!** Please note that **every single** function has to return result
of the calculations, this is crucial for automated testing of your tasks

## How to use `Autocode`?
We use platform [Autocode](https://autocode-next.lab.epam.com) to track the homework, please use it to complete tasks.

To use autocode you must be registered on the platform (please specify your real name).
After registration, please authorize the platform to use your `github` account, platform will automatically fork the repo to your account when you start task.

You might code in any IDEA or TextEditor for the development, to sumbit the code you just need to commit it to the specific branch, after that you will have an ability to submit code on the platform and get all test results.

Good Luck!

