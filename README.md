  Canvas is an academic architecture for manipulating grades, posting files, hosting discussions, facilitating tests, etc. When it comes time to grade, it is useful to have all
the files related to a specific student organized into subdirectories. Additionally, Canvas attaches a filename prefix and suffix, which obscures the original filename causing issues:

Issue 1: (CAD systems)

CAD systems that rely on a hierarchy of file names loose that capability as the prefixes and suffixes change the overal file name. This system aims to clean up the filenames as it is sorting to allow these systems to function properly.

Issue 2: (Volume)

Canvas Download provides a large folder with all the student's uploaded files. Searching for these files can be tedious and impede the framework, especially if multiple files need to be observed. The subdirectories created by this system allow a grader to open up a student's folder, and all related files will be stored in one place.

Issue 3: (Tracking)

Some students submit items late. If there is a grade penalty, it would be good to easily identify which students this rule applies to. Each subdirectory will inherit information from the added suffix to the filename to ensure file submission times are tracked properly.

Issue 4: (Speed)

If files do need to be renamed for any reason, an edit to the original filename is much faster than deleting the suffix and prefix attachments.


How do you use this system?

1. To effectively use this system, an EXE or EXEC can be downloaded from the IOS or WindowsOS folders in this repository.
   
2. Next download your submissions from Canvas, they should arrive in a zip file, extract these to a folder you want to operate in.
   
3. Drop either the EXE (Windows) or EXEC (MAC) into the directory with all the files. Make sure this file is in the same directory as all those files.
   
4. Double-click the EXE/EXEC and a Terminal window will automatically pop up. Once finished, close the terminal window, and return to your file location.
   
5. All the files (Ones that fit the naming scheme) are now in subdirectories, and their original file names are preserved.


Safety features and information:

- These programs are built to ignore Directories "/example/" and Hidden files ".example.txt" and if accidentally run in an unwanted place will leave these entities alone.
  
- Files that are tampered with by these programs are ONLY renamed and moved one directory level down. No files are deleted or added by this process!
  
- Files that are not Directories or Hidden files that also do not fit the Canvas naming scheme will not be moved.
  
- Everything here is open source so feel free to double-check before running anything.

- All file renaming follows this format: 
"\[name]\_\[LATE]\_123456\_12345678\_\[OriginalFilename]\[-1 redundancy suffix].\[extension]" -> "\[OriginalFilename].\[extension]"

- All directory creations follow this format: 
"./\[name] \[Late]/"


If you have any questions feel free to contact me at:   nathan@fikesfarm.com
