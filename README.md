<p align="center"><a href="https://mozillavit.in/" target="_blank"><img src="https://avatars.githubusercontent.com/u/74644419?s=280&v=4" width=160 title="MozillaFirefox-VIT" alt="MozillaFirefox-VIT"></a>
</p>
<br />

# Scavanger Of The Year Backend '24

The official Backend API for Scavanger Of The Year'24 Event Portal

## Event Details

"Scavanger Of The Year" (SOTY), a treasure hunt event website where participants engage through the site.

## Tech Stack

- Node.js
- Express.js
- MongoDB

## Features

- User Authentication
- Single user Login
- Users gets Question from each category of difficulty level(Easy, Medium, Hard)
- Users cannot move to next question until currect question is answered
- Scan correct qr to get points and next question
- Two consecutive incorrect answers blocks the user for the next 2 mins from scanning qrs and answering
- Seeders for seeding questions to the DB( All users will get question present in seederQuestion.js)
- Admins can directly change teams scores
- Admins can Ban users for next 15 mins
- Admins can UnBan user immediately

## Steps To Run

1.  Clone the Repository:

    `git clone https://github.com/MFC-VIT/SOTY-Backend-24.git`

2.  Install all the dependencies:

    `npm i`

3.  Update the .env file with our configs.
4.  Update the questions.json file with the questions, answers, points, difficultyLevel, answered as pending.
5.  Update the seederQuestions.json file with the questions, points, difficultyLevel, answered as false.
6.  To Start the server:

    `npm start`

7.  To seed questions to DB:

    `cd seeders` && `node seedQuestions.js`

8.  Use postman and test the api at the endpoints

# Authors

<table>
<tr align="center">
<td style="border: 2px solid grey; width: 170px; height: 170px">
<a href="https://github.com/HarshitPG"><p align="center">
<img src="https://avatars.githubusercontent.com/u/129543831?v=4" width="160" height="160" alt="Harsit"
style="border: 2px solid grey; width: 180px; height: 180px" />
</p>
<p style="font-size: 16px; font-weight: 600">Harshit P G</p>
<p align="center">
<a href="https://github.com/HarshitPG"><img
src="https://www.iconninja.com/files/930/277/269/github-icon.png"
width="32" height="32" alt="GitHub" /></a>
<a href="https://www.linkedin.com/in/harshit-p-g-a87623272">
<img src="https://www.iconninja.com/files/533/13/122/linkedin-icon.png"
width="32" height="32" alt="LinkedIn" />
</a>
</p></a>
</td>
</tr>
</table>

# License

Copyright © 2024, [MozillaFirefox-VIT](https://github.com/MFC-VIT), [Harshit P G](https://github.com/HarshitPG) and all other contributors. Released under the [MIT License](LICENSE).

<p align="center">
Made with ❤️ by <a href="https://mozillavit.in/" target="_blank">MFC-VIT</a>
</p>
