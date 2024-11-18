Answer 1:
git version 2.34.1
Answer 2:
user.name=Sam Quang Huy
user.email=24100391@st.phenikaa-uni.edu.vn
Answer 3:
GIT-ADD(1)                                              Git Manual                                              GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive | -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update | -u]] [--sparse]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-missing] [--renormalize]
                 [--chmod=(+|-)x] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                 [--] [<pathspec>...]

DESCRIPTION
       This command updates the index using the current content found in the working tree, to prepare the content staged
       for the next commit. It typically adds the current content of existing paths as a whole, but with some options it
       can also be used to add content with only part of the changes made to the working tree files applied, or remove
       paths that do not exist in the working tree anymore.

       The "index" holds a snapshot of the content of the working tree, and it is this snapshot that is taken as the
       contents of the next commit. Thus after making any changes to the working tree, and before running the commit
       command, you must use the add command to add any new or modified files to the index.

       This command can be performed multiple times before a commit. It only adds the content of the specified file(s) at
       the time the add command is run; if you want subsequent changes included in the next commit, then you must run git
       add again to add the new content to the index.

       The git status command can be used to obtain a summary of which files have changes that are staged for the next
       commit.	
Answer 4:
 
Answer 5:
 

