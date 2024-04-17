## Motivation:

At Averlon, our interview process has some interviews where you write
code, typically on your laptop.

This is a maven project to help candidates determine if their laptops were
setup to write Java, so interviews can be about evaluating the candidate,
and not the way their environment is setup.

# Getting Ready

If you can run these commands, your development environment is probably
ready for Java interview questions:

```bash
$ java -version
$ git clone [the project\'s URL]
$ cd [into the project]
$ mvn clean -e install
$ java -jar target/sample-HEAD-SNAPSHOT.jar
```

# About This Project:

## Dependencies & Configuration:

Don't read into the chosen libraries too much.
We've added them to help alleviate two main problems that may be seen
after maven is setup:

- Maven works correctly with third-party dependencies
- Maven's classpath is setup correctly

## Useful References:

- [Installing Maven](https://maven.apache.org/install.html)
  - [using Homebrew, on OS X](https://formulae.brew.sh/formula/maven)
  - [more instructions for Windows](https://maven.apache.org/guides/getting-started/windows-prerequisites.html)
- [Apache Maven FAQ](https://maven.apache.org/general.html)
