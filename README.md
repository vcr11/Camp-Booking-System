
##How To Setup CampBooking Management Application Guide 
 
1. Extract the zip file.
2. Download and Install Node. Download the LTS version.
3. Download and Install VSCode and Visual Studio.


##In Visual Studio(Back End)
Open the Camp Booking.sln from the Extracted File 
After that follow the below steps :
• Open Packet Manager Console from Tools Tab > Nuget Package 
Manager>Packet Manager Console.
• Run the following command on console - Update-Package -reinstall that will 
installed all the dependencies require to run solution.
• Now run the IIS Express.
• Note Your Local host port number
After this your backend will start to work.

##In VSCode (Front-End)
Open UI folder from Extracted File In VS Code
After that follow, the below mentioned commands
i. Open terminal and try following command
ii. node -v //should print the node version
iii. npm -v //should print the npm version
iv. npm install -g @angular/cli
v. npm install
vi. now go to config.ts by following path src >app>config.ts.
vii. There exists a port Number variable with value “60628” replace it by your 
Backend port number.
viii. Now run npm start on terminal.
• After this your UI will be started on http://localhost:4200/home

