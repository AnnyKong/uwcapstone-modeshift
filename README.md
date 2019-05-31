# Seattle Area Incident Avoidance

##  Final Clickable Demo 
[Demo Webpage](https://annykong.github.io/uwcapstone-modeshift/)  |
[Demo GitHub Repo](https://github.com/AnnyKong/uwcapstone-modeshift)

### Instructions
- Please use mobile for clickable demo, the Desktop version is only for demonstration of the Desktop design.
- If you want to view the Mobile version on Desktop, please follow instructions below:
    - Make sure you are using **Chrome** browser
    - **Right click** on page and select **inspect**
        - ![insruction-1](images/instruction-1.png =400x)
    - On top right of the page, click "Toggle device toolbar" to switch to the mobile version
        - ![insruction-2](images/instruction-2.png =400x)
    - On top left of the page, click on the red the area below, you may select any phone type you want
        - ![insruction-2](images/instruction-3.png =400x)
    - You are now ready to test the mobile version!
p.s. To go back to the Desktop version, just click on the "Toggle device toolbar" again
        - ![insruction-2](images/instruction-2.png =400x)

## Team website
[Team Webpage](https://annykong.github.io/ModeShift-App/)  |
[Team GitHub Repo](https://github.com/AnnyKong/ModeShift-App)  
Our Clikcable Demo can be found under the "PROTOTYPE & DEMO" section.

## Folder Structure
```
.                       // GitHub Repository contains all files for demo
├── css/                    // containing all css files for website styles.
│   ├── uwcapstone.webflow.css  // customized style file for this project
│   ├── normalize.css           // library style file 
│   └── webflow.css             // library style file made in webflow
│
├── images/                 // containning all logos and images used for this website.
│   └── ...
│
├── js/                     // containing all JavaScript files for dynamically updates the website.
│   ├── modeshift_live_traffic.js   // dynamically fetch and display live traffic data with GoogleMaps JavaScript API
│   ├── modeshift_map.js            // dynamically fetch and display routing recommendation with GoogleMaps ApIs
│   ├── modeshift_update.js         // dynamically mockup scenarios and button/tabs/search... funcationalities
│   ├── webflow.js                  // library js file made in webflow
│   └── vendor/                     // library files
│       ├── bootstrap.js
│       ├── modernizr-2.8.3-respond-1.4.2.min.js
│       ├── npm.js
│       └── jquery-1.11.2.min.js
│
├── index.html                  // main file including basic structure of our web
├── modeshift_live_traffic.html // map with incident demonstration and live traffic for "map section" ("map" tab)
├── modeshift_map.html          // map with routing recommendation for "routing section" (subpage under "plan your route" tab)
├── README.md                   // basic description of the project
└── .gitignore                  // files to ignore when commiting to this repository
```
	
### Instructions to use your GoogleMap API key
- Get your own key [here (Get Google API Key)](https://developers.google.com/maps/documentation/javascript/get-api-key).
- And then, in `test-map/docs/index.html`, substitute `replacekey` in the code below with the API key you got from the previous step.
  ```
  <script  id="google" async defer
           src="https://maps.googleapis.com/maps/api/js?key=replacekey&callback=initMap"
  async defer></script>
  ```

## Tests
[Map Test](https://annykong.github.io/test-map/) |
[Map Test Repo](https://github.com/AnnyKong/test-map)|
[1st Iteration](https://annykong.wixsite.com/modeshift-19sp) |
[2nd iteration Code (no server)](https://github.com/AnnyKong/ModeShift-App/commits/master) |
[2nd iteration Code (with server)](https://github.com/AnnyKong/ModeShift-App/commits/gh-pages)
[3rd iteration (Web Design)](https://uwcapstone.webflow.io/)

	
## Background - What is this?
This project is sponsored by Challenge Seattle, WSDOT, and King County Metro amongst many other companies and 
organizations in the public and private sector.

When traffic incidents occur in the Greater Seattle area, our sponsors relay important information through social 
media, traditional media, electronic roadway signs, and low-power radio stations along with some rare usage of 
mobile alert systems such as AMBER Alert. While these methods reach a broad group of road users, they fail to 
reach every road user and do not provide adequate solutions in the form of real-time transit recommendations and 
updates. They are also not able to reach every consumer with specific information about incidents and the best 
course of action to take. Our sponsors are seeking recommendations for innovative solutions for wide-reaching 
notification of traffic incidents and solutions for transportation mode-shifting, departure time recommendations, 
and route shifts during and shortly after traffic incidents.

high-level explanation
	- team
	- project purpose
	- website purpose
folder structure
name the starting point

### Problem Statement 
How might we innovate forms of transit incident reporting to the general public and provide accessible, 
mobile solutions for their needs in a timely manner?

###Goals
Our goal is to create an innovative solution that can help the general public navigate or avoid major incidents 
and related congestion. When a major incident or multiple major incidents occur, our solution will provide a 
platform where users can be informed of congestion information, departure time shifts, routing recommendations, 
and support for transportation mode shifting. It is developed with assumptions of the ongoing development of a 
Traffic Incident Management - Congestion Management "Virtual Command Center"

We identified two areas of importance that we focus on for this project: 
1. How user groups can better access or take advantage of current ticketing apps through marketing, 
partnerships, incentives, etc?
2. Recommend design guidelines Metro should consider requiring for future mobile ticketing apps.
    - Promptly informing the general population of incidents which impact their commute
    - Behavior change and modeshift behavior reinforcement

## Our team
![Team members](/images/Team-members.png =500x)
- **Pari Gabriel (HCDE): Project Manager**  
  Pari is an organized and detail-oriented student who will be taking lead of the capstone. He will be in charge of   coordinating internal team meetings, submitting reports, and keeping track of the team’s progress throughout the duration of the project.

- **Chris Angkico (Communications): Marketing Lead**  
  Chris is an experienced researcher and marketing plan writer that will be assigned the role of marketing lead. He will be in charge of evaluating expert and focus group interview information, as well as any pre-existing research information the group collects, to develop a comprehensive strategy to market and advertise our transit incident reporting solution, making sure it gets out to as many different road users as possible. 

- **Yuki Asakura (HCDE): Data Lead**  
  Yuki, an HCDE student familiar with conducting research and survey studies, will be the team’s Data Lead. He will be responsible of collecting data across all tasks to draw insights on the problem space and provide recommendations for our solution.

- **Steven Tuttle (CEE): External Coordinator**  
  Steven is a student in Civil and Environmental Engineering and is familiar conducting research and managing communications for interviews and surveys. He will be responsible for managing external communications between the team and other transit agencies and project mentors.

- **Catherine Wang (CEE): Implementation Lead**  
  Catherine is a civil engineering student with cross-functional experience in technical work with users in mind. She will be in charge of deliverable of technical analysis. 

- **Anny Kong (CSE): Modeling Lead**  
  Anny is a Computer Science student skilled in mathematical modeling and software programming. She will take the lead for overall model development, demo implementation and analysis across all tasks.

