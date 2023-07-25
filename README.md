
# Work In Progress: Gone Phishing - A serious game to teach people to thwart phishing attacks. 
## Molina Lim, Molika Lim, Karen Shew, Crizl Rae Macaalay, Amanda Qian, Andriel Pernecita
## **Project Management: Trello Board**
We used the following Trello Board to manage our project:
https://trello.com/b/y1bFlWAj/development-kanban

## **Description**
This project focuses on developing a novel serious game (web browser-based platform) as an educational intervention to help computer users protect themselves against phishing attacks. The developed game aims to enhance users' confidence in thwarting phishing attacks through motivation to protect themselves against phishing threats.  [Check out our Final Report](https://docs.google.com/document/d/1bsWux882_4FEgvq8pLo0mWDNnLnud-eMdSgvkYTAdKc/edit?usp=sharing). 

## **Technologies that are used to build the project**
- C#
- Javascript
- HTML
- [FirebaseWebGL](https://github.com/rotolonico/FirebaseWebGL)
- Unity (Editor version 2020.3.33f1)  
- WebGL
- Firebase

## **Instructions on how to install and setup the project**
On your Terminal:
```
git clone https://github.com/uoa-compsci399-s1-2022/wip-gone-phishing.git
cd wip-gone-phishing
```
Open the main folder on your Unity, then: 
* File > Build Setting > WebGL > Switch Platform > Player Setting > Settings for WebGL > Publishing Setting > Set Compression Format to "Brotli"> Close the Player Setting window > Build and Run. <br/>
**NOTE:** If Unity prompts you to choose a folder, create a new folder in main called Build and select it. 
* After the project is running on your browser, navigate to main/Build in your file explorer, open index.html with a text editor, delete all the code in index.html and paste the code from [temp.html](https://github.com/uoa-compsci399-s1-2022/wip-gone-phishing/blob/main/temp.html) into it. 
* Refresh the browser page. 

## **Demo Video** 
https://drive.google.com/file/d/1_Ye1XaI0GrMmgnJkPvPVsEXrbeeQbQmH/view?usp=sharing 

## **URL of the deployed game website** 
https://uoa-compsci399-s1-2022.github.io/wip-gone-phishing/

## **Future Plan** 
* Adding more complexity to the game by adding more varieties of emails, allowing the user to open URLs for more information, and a more robust way of responding to emails. 
* Changing the technology stack to using MERN stack instead as it will be easier for testing, more customisable, and higher performance quality. 
* Further refining game depth to better engage players: Add a story element, Refine art style, Add reward and punishment feedback through things like sound effects, Add ability to scroll up and down email inbox and emails.
* Usage testing with actual employees from real-life organisations to collect feedback and improve our software product. 
* Implementing an admin portal that automates user's data collection, analysis, and visualisation so that organisation's admin can use this for cybersecurity threat reports. 

## **Acknowledgements** 
* Nalin Arachchliage (Our Supervisor) 
* [FirebaseWebGL](https://github.com/rotolonico/FirebaseWebGL) 
* [Adding Firebase SDK In Unity WebGL builds Tutorial](https://www.youtube.com/watch?v=fg_aiGVeKc4)
* [Unity Tutorial: How to seamlessly play music between multiple scenes](https://www.youtube.com/watch?v=Xtfe5S9n4SI)

