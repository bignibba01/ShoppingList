# ShoppingList
Simple bash script to store in a txt file your shopping list

To add things to your list just call ListAdd (with execution permission) and pass for arguments the things you need; if you need to use space for a thing just use "Quotation marks".
- When you call ListAdd if the list is not exist it will create an hidden directory called '.db' and a 'list.txt' file in the directory where files are stored.

To delete list call ListDelete, it will delete hidden directory with ALL files in it.

To show list call ListShow (it use the comman less, should be preinstalled file viewer).

If you don't want to use './ListAdd' to call scripts, you can execute ConfigurePATH, it simply add at the end of '.bashrc' file, stored in your home directory, an export command to export the scripts direcotry to $PATH variable and after it will update with 'source' command.
