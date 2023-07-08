The "data" directory is intended to hold data files that will be used by this module and will
not end up in the .jar file, but will be present in the zip or tar file.  Typically, data
files are placed here rather than in the resources directory if the user may need to edit them.

The data/languages directory exists for the purpose of containing various Sleigh language
specification files and importer opinion files.  

The data/buildLanguage.xml is used for building the contents of the data/languages directory.

See the Sleigh language documentation (docs/languages/index.html) for details Sleigh language 
specification syntax.
 