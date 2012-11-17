# Pager
Pager consists of a commandline program 'Pager2' by Richard Conn and a
frontend (this).

NOTE: This is a RISC OS app.

PAGER2 is a tool for creating paged files, extracting the component
files from a paged file, and scanning paged files, where a paged file is
a file composed of one or more files prefixed by banners. PAGER2 is
based in concept on the UNPAGE tool submitted to the Ada Software
Repository on SIMTEL20 by Mitre Corporation. 

Paged files are convenient mechanisms for storing related files. They
reduce cluttering in the directories and simplify the file transfer
process by requiring the user to transfer only one file in order to
obtain all files pertinent to a particular project or tool.
Additionally, paged files are text files which can be handled more
readily than the 8-bit binary images associated with other file grouping
mechanisms (see the file OILBR.DOC in the directory PD2:<ADA.GENERAL> in
the Ada Software Repository). Paged files may be manipulated by a text
editor if necessary. 

For these reasons, paged files have been adopted as a standard for file
storage in the Ada Software Repository. The file type of SRC (as in
MYFILE.SRC) indicates that a file is paged. 

## Frontend use

1. Double click on the !Pager icon - this will place an icon on the iconbar.
2. SELECT clicking on the iconbar icon will open a setup window.
3. Fill in the information needed and SELECT click on 'Run'. Use the
  interactive help to get information about what to fill in where.

This will start the Pager command line program and open a window showing
the status. Extracted components will be written into the current set work directory.