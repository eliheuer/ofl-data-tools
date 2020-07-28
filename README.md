# Libretype Data Tools
Scripts for working with the whole libre/open-source typeface ecosystem.

# Tools
### backup-ofl-complete.sh

>⚠️Warning: The [CSV spreadsheet](csv-data/OFL.txt) this uses is under active development and currently only backs up popular repositories on GitHub up to about 16 stars. Pull requests are welcome to improve the [CSV spreadsheet](csv-data/OFL.txt), I hope to have this populated with at least the top 3000 OFL fonts ASAP. -Eli

This script makes a backup of the full known OFL ecosystem, as defined by a [spreadsheet](csv-data/OFL.csv) located in this repository.
You will need a [BASH-like](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html) terminal with [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed for it to work correctly. From the root directory of this repository, run the script and a backup directory with the current date appended with be created in the same location. To run the script ennter the command:
```
sh backup-ofl-complete.sh
```
If there is a typeface you want to see included, please make a pull request or issue to add it.

![example image](screenshots/screenshot-02.png)
