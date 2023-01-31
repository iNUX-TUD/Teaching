> For the sake of consistency and better learning experience the Structual Design is to be followed strictly. If it happens that you want to extend or change the design, please contact [Thomas Reimann](Thomas.Reimann@tu-dresden.de).

# Structual Design
Each `Lecture Unit` had its own directory which is stored inside the [Lecture directory](../../Lectures). A `Lecture Unit` is structured in didactically chunks each of them comprising one notebook, the `Lecture Notebook`. In addition, there exists a `Index Notebook` functioning as general overview. In the following both are further explained.

## Lecture Notebook
### General
The `Lecture Notebook` presents the content of one didactical chunk within the `Lecture Unit`. This can be anything, ranging from pure text to videos and animations. `Lecture Notebook` are always numbered and so together comprise a logical structure for the student about where to start and end.

### Naming convention
The notebook naming has a fixed prefix:
xx_Anyname.ipynb
xx is the number of the notebook, starting from 1 with leading zero notation. That is, 01, 02, etc.

### Layout convention
The layout contains the logo at the top, as well as links to the previous and following notebook at the top and bottom. At the very bottom the Authors as well as the Creative Commons batch is shown.
Please use the [template](lectureNotebook_template.ipynb).

## Index Notebook
### General
The `Index Notebook` is always the first notebook the student will open in a `Lecture Unit`. It provides an overview about the topic, the learning outcome as well as the table of contents.

### Naming convention
The naming is always:
00_Index.ipynb

### Layout convention
The layout contains the logo at the top. At the very bottom the Authors as well as the Creative Commons batch is shown. Besides, it at least has one section which summarizes the topic and one which explains the learning outcome. At also shows the  table of contents.
Please use the [template](indexNotebook_template.ipynb).
