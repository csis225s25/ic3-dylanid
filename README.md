# In Class Problem Set 3 - Dylan Iddings, Colin Fisher

I used ComboBoxDemo.java a few years ago.  It used to compile cleanly.  Even though the code has not changed, it now  will not compile without throwing warnings.

Doing everything from a command prompt or Git Bash (no IDEs allowed), your mission is to debug the code and find out why it stopped compiling cleanly.  When you have figured it out,  note what you changed and why it stopped working in the README.md file.


**Changes to code**
Updated the constructor to include the type (in this case String)

**What caused it to stop working?**
Java SE8 changed JComboBox constructer to use Generics to make them type safe. Since this code was made a few years ago, the code needs to be updated to reflect the later version of Java.
