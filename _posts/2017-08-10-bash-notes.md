---
Title: "Bash Notes"
date: 2017-08-10 13:19:00 -0600
categories: scripts
permalink: bash-notes
---
Bash notes
==========


***`set -e`***
--------------
Sometimes I forgot to add a line to the script and I find myself hitting Ctrl+C to cancel the script.
However this will cancel the current line running and not interrupt the script.
Adding `set -e` to the beginning of the document ensures that if a line exits with a no success return, the script won't continue
