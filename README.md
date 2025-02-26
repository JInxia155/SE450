
Download Link :https://programming.engineering/product/se450-assignment-2/


# SE450
 🔍 SE450 : Assignment 2 SE450 : Assignment 2
A software company MicroOffice has produced four generations of Word Processing Applications, called Word90, Word00, Word10, and Word18. Suppose you are writing a program to test their GUIs. The GUI components we are interested in are Panel, Button, and Textbox. These GUI components look a little different in different generation. Each generation has it own program for testing these GUI components. To know which test to run, you will need to instantiate objects that correspond to each one of the GUI components.

We assume that generations of the Word to be tested are stored in a configuration file (text file). Because this situation fits the Abstract Factory pattern so well, you can use that pattern to organize the creation of objects that correspond to GUI components. You will also need to use the variation of singleton pattern to ensure that at most two instances of each generation in each test run. Please note finishing running all generations specified in the configuration file is considered as one test run.

Here is an example of the configuration file content. You can create your own.

Word90

Word00

Word90

Word18

Word10

Word00

Word18

Word90

Word00

Questions

    Give the UML diagram. You should integrate singleton into abstract factory pattern.

    Give the code (in any language e.g. JAVA) based on the UML class diagram given in 1). As output, you need to display three different messages (e.g., “Panel Word90”, Button Word90”, and “Textbox Word90”) for the generation specified in configuration file. You should give a warning message if the same generation are asked to run more than twice.

    Zip your UML diagram, source code, output screen shot in one .zip file and upload to Assignment 2 folder in D2L before due.

Solution
