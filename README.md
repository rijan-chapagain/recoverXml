# recoverXml
This repo demonstrate how to recover xml files.
..* If we want to recover our crash word documents then follow this:
**You cannot recover the whole files as similar as before by following these steps, but you can get all the content you had written before.**
1. Open terminal
2. Go to the dir containing your crash word file. My dir is at: >/home/joe/test/
3. Rename your file with ".zip" extinsion. Here myfile name is "demo.docx" > mv demo.dox demo.zip
4. Now, unzip the folder or you can open the folder directly >unzip test.zip 
5. open the unzipped/zipped folder
6. Now you can see dir named word
7. open the dir word
8. Then, open an xml file named "document.xml" in any of your text editor.
9. Add and sytle sheet link *<?xml-stylesheet type="text/css" href="demo.css"?>* below the xml opened tag line *<?xml version="1.0" encoding="UTF-8" standalone="yes"?>*
10. make an stylesheet of your choice. You can check mine st.css for demo.
11. Finally, open the xml file including stylesheet in your browser. 
12. you can see only your words are there everything in one paragraph. 
13. if you want to make it more easier for you to understand the single paragraph words, you can add styles by changing the tags of xml code and add style on it.
14. You can use vs code or notepad ++ where you can change all the occurance for easy editing large xml code to add style.
13. Again, you can check my demo.xml for your help.
16. Enjoy :)