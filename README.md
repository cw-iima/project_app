![image](https://github.com/user-attachments/assets/74af3beb-139e-4cac-9fc8-b7dd163b17a4)# **Vehicle Routing with Time Window Constraints**
## About the Problem
The Vehicle Routing Problem with Simultaneous Pickup and Delivery with Time Windows (VRPSPD-TW) is an optimization problem that arises in logistics and transportation, where a fleet of vehicles must serve a set of customers with both delivery and pickup demands. Each vehicle has limited capacity, and customers have specific time windows during which they must be served. Additionally, the vehicles must optimize routes to minimize the total distance traveled while ensuring that deliveries and pickups are completed simultaneously without exceeding capacity limits.
## What is the use of the Application
Using the application, users can find and visualize the routes for their own data set in `.json` format or utilize the random data generator to create a random data set and study the optimized routes.
## Live Application URL
The application will be deployed in this URL - [https://**user_name**.github.io/**repo_name**]
## Prerequisites
### Install Node JS
Refer to  [https://nodejs.org/en/](https://nodejs.org/en/)  to install nodejs.
## Cloning and Running the Application in local
Clone the project
```bash
git clone https://github.com/[user_name]/[repo_name].git
```
Go to the project directory
```bash
cd [repo_name]
```
Install dependencies
```bash
npm install
```
Start the server
```bash
npm run start
```
The Application Runs on **localhost:3000**
## Setting Up GitHub Pages
Open GitHub - `https://github.com/[user_name]/[repo_name]/`
 1.	Create a new branch named as `gh_pages`
 2.	Go to settings page - `https://github.com/[user_name]/[repo_name]/settings/`
 3.	Go to the **Pages** tab
 4.	Ensure that the branch `gh_pages` is set as the default branch to be deployed

## Deploy the application in Github Pages
```
npm run predeploy
npm run deploy
```
## Application design
In the repository, the files involved in development of the application is in the `src` folder.
The structure of the `src` folder is as follows:

 1. `assets` folder contains all the static elements such as images and data sets.
 2. `component` and `container` folders contains the React components and containers.
 3. `utils` folder contains the helper function and the modified Clarke-Wirght Algorithm file.
## Component Tree
```
📦index.js
┣ 📂AppHeader
┃ ┗ 📂Header
┗ 📂MasterContainer
┃ ┣ 📂Home
┃ ┃ ┣ 📂UploadData
┃ ┃ ┣ 📂InputForm
┃ ┃ ┣ 📂InputPreview
┃ ┃ ┃ ┗ 📂Plot
┃ ┃ ┗ 📂Output
┃ ┃ ┃ ┣ 📂Plot
┃ ┃ ┃ ┣ 📂RouteNav
┃ ┃ ┃ ┗ 📂RouteDetail
┃ ┣ 📂GetStarted
┃ ┗ 📂About
```
## Component Folder Structure
Each component folder will have at most three files - JS File, Proptype file, CSS file.
```
📂Header  
┣ 📜Header.css  
┣ 📜Header.js  
┗ 📜Header.propTypes.js
```
