# ExtractWhiteboardFromModules
Build a whiteboard doc from existing project

Prompts user for project directory and then the directory to drop the output file

Pulls out file names, and for each of them the description (top level annotation), pre condition (based on text parsing the annotation), post condition (also based on text parsing the annotation), and arguments

By default it ignores the Framework and Tests folders in the project and the Main.xaml and Process.xaml files in the top level folder.
