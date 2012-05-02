CodeExport
==========

The CodeExport component facilitates automatic export of all methods in the host database to text files on disk.  If the host database is under revision control, these text files are suitable for committing to the repository, thus giving the developer to ability to track changes to methods over time. Most importantly, the CodeExport component is designed to have zero impact on the host database.  There is no startup code to install and nothing to configure.