### INTRODUCTION

The existence of shells is linked to the very existence of IT.
At the time, all developers agreed that communicating with a computer using aligned
1/0 switches was seriously irritating.
It was only logical that they came up with the idea of creating a software to communicate with a computer using interactive lines of commands in a language somewhat
close to the human language.
Thanks to Minishell, you’ll be able to travel through time and come back to problems
people faced when Windows didn’t exist.

---

### ABOUT

Program should (and actually do):

* Display a prompt when waiting for a new command.
* Have a working history.
* Search and launch the right executable (based on the PATH variable or using a
relative or an absolute path).
* Not use more than one global variable.
* **Single quote ’** prevents the shell from interpreting the metacharacters in the quoted sequence.
* **Double quote "** prevents the shell from interpreting the metacharacters in the quoted sequence except for **$ (dollar sign)**.
* Redirections:
  - **<** redirects input.
  - **\>** redirects output.
  - **<<** should be given a delimiter, then read the input until a line containing the
delimiter is seen.
  - **>>** redirects output in append mode.
* Pipes (| character). The output of each command in the pipeline is
connected to the input of the next command via a pipe.
* Environment variables (**$** followed by a sequence of characters) which
expands to their values.
* **$?** expands to the exit status of the most recently executed
foreground pipeline.
* **ctrl-C**, **ctrl-D** and **ctrl-\\** behaves like in bash.
* In interactive mode:
  - **ctrl-C** displays a new prompt on a new line.
  - **ctrl-D** exits the shell.
  - **ctrl-\\** does nothing.
* Builtins:
  - echo with option -n
  - cd with only a relative or absolute path
  - pwd with no options
  - export with no options
  - unset with no options
  - env with no options or arguments
  - exit with no options
* **&&** and **||** for priorities.
* Wildcards **\*** working for the current working directory.

---

<img width="1191" alt="Screen Shot 2022-09-04 at 19 17 46" src="https://user-images.githubusercontent.com/89987795/188323169-6aa808d2-466a-4c87-8088-cc0a321df01e.png">
