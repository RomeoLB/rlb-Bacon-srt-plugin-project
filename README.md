# rlb-Bacon-srt-plugin-project
BAcon project for displaying srt subtitles / captioning

<img width="882" alt="image" src="https://github.com/user-attachments/assets/1bdf260f-d594-45a1-bced-c229387384d7">


This BACon presentation/plugin uses 2 .srt files (JeffH_ISE2018_EN.srt – English version, JeffH_ISE2018_FR.srt – French version) that follows the [SubRip subtitle format](https://en.wikipedia.org/wiki/SubRip), as per what can be seen in the below picture:

<img width="652" alt="image" src="https://github.com/user-attachments/assets/1241c416-2981-463a-83db-ba904916fb73">

In order to load the .srt subtitle for a state, the state name has to match the .srt filename without the .srt file extension. 
For example, there is a state called “JeffH_ISE2018_EN” and a state called “JeffH_ISE2018_FR” in this presentation: 

<img width="983" alt="image" src="https://github.com/user-attachments/assets/bfcf3a07-a1a1-49b6-a240-4b2620ea2d65">

To load the relevant .srt file for the state “JeffH_ISE2018_EN”, there should be a .srt subtitle file named “JeffH_ISE2018_EN.srt” added to the presentation as an auxiliary file. For the state “JeffH_ISE2018_FR” there should also be a .srt subtitle file named “JeffH_ISE2018_FR.srt” also loaded as an auxiliary file. New .srt subtitle files can be added via "Presentation Settings" > "Support Content" > "Files" > "+" 

<img width="390" alt="image" src="https://github.com/user-attachments/assets/ce092d8c-c4a5-4615-bf1e-bfe8b33a9238">

This presentation also uses a plugin which was added via "Presentation Settings" > "Support Content" > "Script plugin" > "subtitles_widget.brs" . Please make sure that the plugin name is "srtSub". 

<img width="384" alt="image" src="https://github.com/user-attachments/assets/d2414895-4135-4f26-94b9-b56a70192d3a">

