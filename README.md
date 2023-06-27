# UTrim-ScissorApp


### Overview

The application is a URL shortener web application built using Flask, a Python web framework. It allows users to create shortened URLs and track the number of visits to those URLs. Users can register an account, log in, and access their personalized dashboard to manage their shortened URLs. The application also provides analytics for each shortened URL, displaying the visit locations(currently restricted to Oregon, US. because of current hosting) and devices used.

## Key Features:

1. URL Shortening: Users can input lengthy URLs and generate shortened versions that are easier to share and remember.

2. Customizable URLs: Users have the option to customize the shortened URLs to reflect their brand or preferred keywords, making them more recognizable and memorable.

3. Link Analytics: The application will track and provide insightful analytics on the usage and performance of the shortened URLs, including click-through rates, geographic data, and referral sources.

4. QR Code Generation: The system will generate QR codes for each shortened URL, allowing users to easily share them in printed materials or mobile devices.

5. Link History: Users will have access to a comprehensive history of their shortened URLs, including creation dates, original URLs, and usage statistics.

6. Secure and Scalable: The application will prioritize data security, implement proper authentication mechanisms, and ensure scalability to handle a large volume of requests.

7. User Management: The system will provide user registration and authentication functionalities, allowing users to manage their shortened URLs and access personalized features.

## Built with:
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

![Jinja][jinja]
![HTML5][html5]
![CSS3][css3]

## Get a copy
It is believed that you have python installed already. Open CMD or terminal
1. Clone this repo

2. Open the directory
```sh
cd UTrim
```
3. Create Virtual Environment
```sh
python -m venv <your-venv-name>
```
4. Activate virtual environment on CMD or Powershell
```sh
<your-venv-name>\Scripts\activate
```
On gitbash terminal
```sh
source <your-venv-name>/Scripts/activate.csh
```
5. Install project packages
```sh
pip install -r requirements.txt
```
6. Set environment variable
```sh
set FLASK_APP=scissor/
```
On gitbash terminal
```sh
export FLASK_APP=scissor
```
7. Create database
```sh
flask shell
```
```sh
db.create_all()
quit()
```
8. Run program
```sh
flask run
```
<hr>

<!-- Getting Started -->
## Usage

This tool can be accessed via the deployed site or a local copy of the project.

### Live Link

Deployed site: (https://[https://utrim.onrender.com]) - hosted via [render]

## Lessons Learned

Creating this tool helped to learn and practice:
* Responsive Web Design
* URL Shortening
* QR Code Generation
* Debugging
* Routing
* Database Management
* Internet Security
* User Authentication
* User Authorization
* Message Flashing
* Documentation

<p align="right"><a href="#readme-top">back to top</a></p>


<!-- Contact -->
## Contact

Dr Austin Wopara - [@Ze_Austin](https://twitter.com/gbreigns) - pascalreigns7070@gmail.com

Project Link:(https://github.com/gbreigns/UTrim-ScissorApp)

Live Link: (https://utrim.onrender.com)

<p align="right"><a href="#readme-top">back to top</a></p>





