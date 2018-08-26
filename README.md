# STLPrinterQue
3D printer STL management process, able to create and manage a print queue.


I'm not sure where this will eventually go, my initial need for creating this project was to be able to send multiple .STL files to Cura from Fusion 360.  To those ends I need the following.

1) A program to be selected in Fusion 360 as the printing application.  
    Because this needs to be a .EXE file, the JAR is built into a .EXE file
    This will queue the SQL files in a folder on my server (configurable by .properties file)
    
2) Send queued items to the specified slicer program
    Initially my desktop copy of Cura
    Eventualy perhaps a web-driven interface to multiple command line slicers, and automatic defaults.
    Be able to pull programs out of this queue with some intelligence.
    Always running monitor, because the queue can have files added to it at any point (from multiple machines)

