# use-voice-controlled-image-processing-software
 We use the speak to text sphinx4 tool to control the functionality of our software under netbeans

1- Download sphinx4 tools using the following link:
https://osdn.net/frs/g_redir.php?m=kent&f=cmusphinx%2Fsphinx4%2F1.0+beta6%2Fsphinx4-1.0beta6-bin.zip 
or
https://sourceforge.net/projects/cmusphinx/files/sphinx4/1.0%20beta6/sphinx4-1.0beta6-bin.zip/download
2- Extract zip file
3- goto folder "lib" and run the following file "jsapi.exe"
4- open my project in netbean
5- Import Spinx 4
	In the "Project Windows" rigth click on "TNI_audio"
	Then click "Add Jar/Folder"
	Go to the folder "lib" 
	Select all files (Crtl + A)
	Finaly click "open"
6- Open "TNI.java" file in netbeans
7- Replace all links "C:\\Users\\fayhj\\Pictures" by your own link in tour computer
8- Open "hello.gram"
9- Replace each sentence of the line "(function one|function two|function three|function for|function five|function six|rotate)" by your own sentence like "rotate"
10- In "TNI.java" uncomment lines 1550 to 1556
11- Then modify words like "function one" to his correspondence.
Ex: rotate correspond to rotate in "hello.gram"
That finish
Run project