# Twee2-jEdit-Highlighting
Syntax highlighting for the Jedit editor (Homepage at http://jedit.org/).
How to install: Open up the Jedit source folder (usually /usr/share/jedit/ on linux machines). Copy and paste the file for the story format you want to use into the "modes" folder (currently only support for Sugarcube 1 and 2, I am working on a Harlowe version as well). Then add the following to the "catalog" file inside the "modes" folder:

<MODE NAME="[Your Story Format]" FILE="[File Name].xml" FILE_NAME_GLOB="*.tw2"/>

Then open up jEdit, and the keywords will be highlighted!
