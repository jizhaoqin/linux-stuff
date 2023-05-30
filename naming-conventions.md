# The Naming Conventions Of Titles, Codes, Files, Folders And Other Things

- for tiles in like *.md files, use title case, e.g. `The Title Of This File.md`. This is to keep consistent with the naming conventions of most English titles.

- for most codes, use CamelCase
  - for functions, use lowerCamelCase, e.g. `def myFunction():`
  - for classes, use UpperCamelCase, e.g. `class MyClass():`
  - for variables, use UpperCamelCase, e.g. `MyGreatVariable = 1`
  - for variables in main code, the names start with the name of the specific instance, e.g. `EarthMass = 1`. This is to avoid confusion when there are multiple instances with same properties.
  - for variables inside functions, the names start with the properties of the instance, followed by the name of the specific class, e.g. `MassEarth = 1`. This is to keep consistent with most equations and formulas in physics, which are usually general without a specific instance, which means they start with the properties with additional information as subscripts.
  - exceptions: special word can use upper or lower case, like names, places, special terms with well known contents.

- for files and folders, use lower case dash line naming, e.g. `my-file-name.txt`, `my-folder-name`. This is to keep consistent with the naming conventions of most Linux files and folders.

- other conventions are to be added later.
