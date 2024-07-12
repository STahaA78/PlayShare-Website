# _PlayShare-Website_
* _A website offering 4 different sports(Basketball, Football, Cricket, Tennis) which allows multiple teams to interact with each other while registering matches and tournaments respective to their sports._
# _Set Up_
* _This Project is made on vscode in which the frontend is mainly CSS and HTML however the extension of files is ejs which refers to embedded Javascript, where as the information of clients is stored in a database which is made in mysql while the backend connecting both of these ends is made using node js._
* _First Your system must have node js and mySql software along with workbench installed which could be installed from chrome._
* Second you must copy the sql files upload and run them so that your database is up and running._
* _After installing node js you must install express,body-parser,mysql2,sessionstorage-for-nodejs using the terminal in vscode where you run the command "npm install x" where x are the listed items._
*  _After this Just copy the files in a folder and open it in vscode and run the command "node connection.js" in the terminal and then go to chrome and write "http://localhost:3000/lg" and this will lead you to the login Page._
# _Details_
* _This Website allows a user to create his own profile in in the signup page after which he moves onto the team selection page where he has an oprtion to select a team or create a team._
* _If the player create a team he is automatically apointed the captain while he would also be shown a dropdown of all the team of the same sport he has selected if he wishes to join the team._
* _After this he is goes to the home page where he would be shown Tournament Details in which all tournament of the respective players sports are shown along with an option of selection a tournment and going to its information page which leads the player to choose whether he whishes to register or not if he does register then he is lead to the payment page where he can register his team only if he is the captain of the team._
* _Match detail option in the home page shows the player personal upcoming matches while match history shows all the previous matches and tournaments._
* _Side Bar Options:_
    * _Torney match: If the Player has registered a tournament he can set a matches for that tournament._
    * _Search: Functionality to allow searching of Player or team having account on the website where on selecting leads to show there respective information._
    *_ Register: Option to register tournament if the player is a captain which is then shown to other teams._
    * _Set Matches: The option to set a match by telling your availabilty and then it is booked as pending match shown to other teams. Then the teams available at that time and place can select the match and then the match is booked._
    * _News Feed: Contains the information of the current updates in the sports world._
    * _Calender/home Page: has 3 options Match details,Match History and tournament Deatails._
    * _Rewards: Rewards are awarded based on the number of matches played from our website ._
    * _Pending: Tab showing pending matches in which one team is decided but team 2 has to be decided so that the captain could decide whether to play that match or not._
* _Profile: Shows the players profile along with the previous matches played by the Player._
* _Logout: Leads to the rating page where our website is rated and then to the login page._
