0x03-shell_variables_expansions scripts

**alias ls="rm *"** The alias command was used to change the name of the value "rm *" to "ls".

**echo "hello $USER"**  The command echo "hello $USER" output the string "hello" followed by the username of the current user. 

**export PATH=$PATH:/action**  The command "export PATH=$PATH:/action" added the directory "/action" to the system's search path for executables.

**echo $PATH | tr ':' '\n' | wc -l**  The command "echo $PATH" printed the value of the PATH environment variable. tr ':' '\n' replaced all colons (:) in the output with newline characters (\n), which separated the directories in the PATH into separate lines. wc -l counted the number of lines in the output, which corresponded to the number of directories in the PATH.

**printenv**  The printenv command printed out the values of all or specified environment variables.

**set**  The set command displayed the values of all shell variables, including environment variables, user-defined variables, and shell options. 

**BEST="School"**  This command set a shell variable BEST to the string value "School". The variable BEST can now be accessed and referenced elsewhere in the shell session by using the $BEST syntax.

**export BEST="School"**  This command set an environment variable BEST to the string value "School" and exported it to the environment of the current shell session.

**echo $((TRUEKNOWLEDGE+128))** This command added 128 to the value stored in the environment variable TRUEKNOWLEDGE and printed the result to the standard output.

**echo $((POWER/DIVIDE))** This command performed integer division of the value stored in the shell variable POWER by the value stored in the shell variable DIVIDE. 

**echo $((BREATHxxLOVE))**  This command performed exponentiation of the value stored in the shell variable BREATH to the power of the value stored in the shell variable LOVE. The ** symbol is used to represent the exponentiation operator in shell arithmetic expressions.

**echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo"**  We used the brace expansion and the grep command to generate a list of all possible two-letter combinations of the English alphabet, then exclude any combinations that contain the letters "oo" using the -v option of grep.

