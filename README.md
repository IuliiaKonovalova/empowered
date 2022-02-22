# Empowered

Empowered was developed as part of the January 2022 Hackathon: Accelerating the future of workforce well-being and mindfulness, presented by Code Institute and Soda Social.

![Empower Website](static/images/empowerwebsite.png)

[Click Here to view the deployed site.](https://empowere.herokuapp.com/)

![GitHub last commit](https://img.shields.io/github/last-commit/AwsSG/empowered?color=red)
![GitHub contributors](https://img.shields.io/github/contributors/AwsSG/empowered?color=orange)
![GitHub language count](https://img.shields.io/github/languages/count/AwsSG/empowered?color=yellow)
![GitHub top language](https://img.shields.io/github/languages/top/AwsSG/empowered?color=green)
![GitHub forks](https://img.shields.io/github/forks/AwsSG/empowered?style=social)
![W3C Validator](https://img.shields.io/w3c-validation/html?targetUrl=https%3A%2F%2Fempowere.herokuapp.com%2F)


## CONTENTS

* [User Experience (UX)](#User-Experience-(UX))
  * [Initial Discussion](#Initial-Discussion)
  * [User Stories](#User-Stories)

* [Design](#Design)
  * [Colour Scheme](#Colour-Scheme)
  * [Typography](#Typography)
  * [Imagery](#Imagery)
  * [Wireframes](#Wireframes)
  * [Features](#Features)
  * [Accessibility](#Accessibility)

* [Technologies Used](#Technologies-Used)
  * [Languages Used](#Languages-Used)
  * [Frameworks, Libraries & Programs Used](#Frameworks,-Libraries-&-Programs-Used)

* [Deployment & Local Development](#Deployment-&-Local-Development)
* [Testing](#Testing)  
* [Credits](#Credits)
* [Collaborators](#Collaborators)
* [Acknowledgments](#Acknowledgments)

- - -

## User Experience (UX)

### Initial Discussion

The theme brief for the January 2022 Hackathon was to rethink solutions to help build an iniative to improve different aspects of mental health and well-being in 2022.

The judging criteria:

* Provides a clear and substantial value to the user. 
* Uses an original or innovative idea, design or implementation.
* Has well structured and completed documentation (README and wireframes).
* Is well planned and executed using GitHub projects.
* Focus is realistic and has an overall sense of completeness. 

#### Key information for the site

We discussed several ideas for our project and decided to create a site that would allow the user to record their emotional state daily by choosing the emoji that best depicts how they are feeling. The user would also be able to add a journal entry to expand on their choice of emoji and to note anything they feel is having an effect on their mental health. 

Users would then be able to view their previous emojis on a calendar which would allow them to track their well-being. It would also be a useful tool to be able to show to professionals should the user decide to seek further help. When the user selects an emoji logged in the calendar they would then be shown their journal entry for that day. 

As this would be quite personal information it was important that the user be able to make a profile to keep this information private. By registering a profile the user would then be able to utilise the calendar feature.

When a user selects their emoji we will then provide a personalised recommendation for them based off of the selection they have made. So for example if a user is feeling sad they may be recommended a funny video clip or a positive affirmation, if they are feeling stressed they may receive a video on breathing techniques used to relax or a fun game to play to allow them to destress. 

### User Stories
#### First Time Visitor Goals:

1. As a **First Time Visitor**, I want to **easily understand the main purpose of the website**, so I can **learn more about this website**.

1. As a **First Time Visitor**, I want to **be able to easily navigate through the website**, so I can **find the content**.

1. As a **First Time Visitor**, I want to be able to **register my account**, so I can **learn benefits of the website as a user**.

1. As a **First Time Visitor**, I want to **find the website useful**, so I can **use it according to my needs**.


2. As a user I want to ensure that my personal information (login details and feelings log) will be kept secure and private.
3. As a user I want to be able to choose an appropriate emoticon to select as my emotional status for that day.
4. As a user I would like to be able to add additional notes to my emoticon to allow me to express my state of mind.
5. As a user I want to be able to view my previous emoticons and notes over a selected time frame to get an overview of my mental health.

- - -

## Design

### Colour Scheme

![Colour Scheme for the Website](documentation/colourscheme.png)

We researched colour theory and colour psychology to find what colour palettes may be beneficial to someone who may be struggling with their mental health. We discovered that light blues are associated with peace, sincerity and gentleness. Darker blues are representative of power, strength and dependability. Greens are associated with growth and have a calming presence.  

We feel that this colour palette has a nice balance between the blues and greens to promote calm and peacefulness on the site. The choice of green also ties in with the use of the colour green in the mental health awareness ribbon.

[Psychology of Color Explained](https://www.masterclass.com/articles/psychology-of-color-explained#4-examples-of-color-psychology)
 | [Colour Psychology - Green](https://www.verywellmind.com/color-psychology-green-2795817) | [Colour Psychology - Blue](https://www.verywellmind.com/the-color-psychology-of-blue-2795815)

### Typography

We have used sans-serif as our font.

### Imagery

### Wireframes

Wireframes were created for mobile, tablet and desktop.

![Home Page Wireframe](documentation/wireframes/homewireframe.png)
![Log in Page Wireframe](documentation/wireframes/loginwireframe.png)
![Register Page Wireframe](documentation/wireframes/registerwireframe.png)
![Calendar Page Wireframe](documentation/wireframes/calendarwireframe.png)
![Profile Page Wireframe](documentation/wireframes/profilewireframe.png)

### Features

The website is comprised of a home page, a log in page, a registration page, a profile page and a calendar page. Each page of the site has been designed to be fully responsive on a range of devices.

* All Pages on the website have:
  * A navigation bar which allows the user to navigate to the home page from every page on the website, and other navigational links.
  ![Navbar image](documentation/navbar.png)
  * A footer which contains the hackathon team name and images of the team which link to their GitHub accounts.
  ![Footer image](documentation/footer.png)

* Future Implementations.
  * In future implementations we would like to provide the option for a user to be able to change their password or choose to delete their account completely. Due to the time constraints of the Hackathon, this was not a feature required to reach a minimum viable project.

### Accessibility

We have been mindful during coding to ensure that the website is as accessible friendly as possible. This has been have achieved by:

* Using semantic HTML.
* Using descriptive alt attributes on images on the site.
* Ensuring that there is a sufficient colour contrast throughout the site.

- - -

## Technologies Used

### Languages Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - was used as markdown language.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/css) - was used to add the styles and layout of the site.
- [Python 3.8.5](https://www.python.org/downloads/release/python-385/) - used to manipulate the data.


### Frameworks, Libraries & Programs Used, etc

- [Flask](https://flask.palletsprojects.com/en/2.0.x/) was used as the foundation of the site.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - was used to arrange items simmetrically on the pages.
- [CSS roots](https://developer.mozilla.org/en-US/docs/Web/CSS/:root) - was used to declaring global CSS variables and apply them throughout the project. 
- [Balsamiq](https://balsamiq.com/) - was used to make wireframes for the website.
- [VSCode](https://code.visualstudio.com/) - was used as the main tool to write and edit code.
- [Git](https://git-scm.com/) - was used for the version control of the website.
- [GitHub](https://github.com/) - was used to host the code of the website.
- [GIMP](https://www.gimp.org/) - was used to make and resize images for the README file.
* [Cal-heatmap](https://cal-heatmap.com/) for providing resources for our application;

Mongo DB 

Google Dev Tools - To troubleshoot and test features, solve issues with responsiveness and styling.

[Tiny PNG](https://tinypng.com/) To compress images.

[Favicon.io](https://favicon.io/) To create favicon.

[Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.

[Shields.io](https://shields.io/) To add badges to the README.

[Canva](https://www.canva.com/) To edit images.

- - -

## Deployment & Local Development

---
## Deployment

- The program was deployed to [Heroku](https://dashboard.heroku.com).
- The program can be reached by the [link](https://empowere.herokuapp.com/)
### To deploy the project as an application that can be **run locally**:

*Note:*
  1. This project requires you to have Python installed on your local PC:
  - `sudo apt install python3`

  1. You will also need pip installed to allow the installation of modules the application uses.
  - `sudo apt install python3-pip`

Create a local copy of the GitHub repository by following one of the two processes below:

- Download ZIP file:
  1. Go to the [GitHub Repository page](https://github.com/AwsSG/empowered).
  1. Click the Code button and download the ZIP file containing the project.
  1. Extract the ZIP file to a location on your PC.

- Clone the repository:
  1. Open a folder on your computer with the terminal.
  1. Run the following command
  - `git clone https://github.com/AwsSG/empowered.git`

- Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

  [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/AwsSG/empowered)

  1. Install Python module dependencies:
     
      1. Navigate to the folder madlib_with_python by executing the command:
      - `cd madlib_with_python`
      1. Run the command pip install -r requirements.txt
        - `pip3 install -r requirements.txt`
     
      
### To deploy the project to Heroku so it can be run as a remote web application:
- Clone the repository:
  1. Open a folder on your computer with the terminal.
  1. Run the following command
  - `git clone https://github.com/AwsSG/empowered.git`

  1. Create your own GitHub repository to host the code.
  1. Run the command `git remote set-url origin <Your GitHub Repo Path>` to set the remote repository location to your repository.

  1. Push the files to your repository with the following command:
  `git push`
  1. Create a Heroku account if you don't already have one here [Heroku](https://dashboard.heroku.com).
  1. Create a new Heroku application on the following page here [New Heroku App](https://dashboard.heroku.com/apps):

      - ![New Heroku App](documentation/deployment/new_heroku_app.png)

  1. Go to the Deploy tab:

      - ![Deploy Tab](documentation/deployment/deploy_tab.png)

      - ![Deployment Method](documentation/deployment/deployment_method.png)

  1. Link your GitHub account and connect the application to the repository you created.

      - ![Link GitHub account](documentation/deployment/link_to_github.png)

  1. Go to the Settings tab:
  
      - ![Settings Tab](documentation/deployment/settings_tab.png)

  1. Click "Add buildpack":

      - ![Add Buildpack](documentation/deployment/add_buildpack.png)

  1. Add the Python and Node.js buildpacks in the following order:

      - ![Add Python and Node.js](documentation/deployment/add_python_and_node_js.png)

  1. Click "Reveal Config Vars."

      - ![Reveal Config Vars](documentation/deployment/reveal_config_vars.png)

  1. Add 1 new Config Vars:
      - Key: PORT Value: 8000
      - *This Config was provided by [CODE INSTITUTE](https://codeinstitute.net/)*.

  1. Go back to the Deploy tab:

      - ![Deploy Tab](documentation/deployment/deploy_tab.png)

  1. Click "Deploy Branch":

      - ![Deploy Branch](documentation/deployment/deploy_branch.png)

      - Wait for the completion of the deployment.

      - ![Deploying Branch](documentation/deployment/deploying_branch.png)

  1. Click "Open app" to launch the application inside a web page.

      - ![View Button](documentation/deployment/view_app.png)

---
## Testing

[Click Here](TESTING.md) to view the full testing steps that were completed on every device and browser.

---

## Bugs
### Solved Bugs

1. The cal-heatmap did not displayed data from mongoDB.

    *Solution:* Add additional code to calendar.html as the extension of calendar.js to transform the data to required format:

    ```javascript

        let data222 = {};
        let date0;
        let emoji_number;

        {% for emoji in emoji_tracker %}

        date0 = {{ emoji.datetime }}
        emoji_number = {{ emoji.emoji }}
        data222[`${date0}`] = emoji_number
        console.log(data222)

        {% endfor %}

        console.log(dataArray)
    ```

1. The didn't represent the data of notes when clicking  on the day:

    *Solution:* Add code to calendar.html and calendar.js in order to connect data

      ```javascript
      let date0;
      let dataArray = []
      let emoji_number;
      let tempDate;


      {% for emoji in emoji_tracker %}
      tempDate = new Date({{ emoji.datetime }} * 1000)
      dataArray.push({
        date: tempDate.toLocaleDateString("en-US"),
        emoji: {{ emoji.emoji }},
        note: "{{ emoji.note }}"
      })
      {% endfor %}

      console.log(dataArray)
      ```

### Known Bugs

1. The cal-heatmap calendar is not responsive. There for the user can find it a bit messy, but to reduce misleading for the user, the navigation buttons were implemented

1. The user can only use select - options to pick an emoji as flask can retrieve data of value only from input, select when options are implemented.

---
## Credits

* [ColorSpace](https://mycolor.space/?hex=%230494EC&sub=1) for providing a myriad of color scheme to choose from as we did;
* [Hero image for home page](https://www.rawpixel.com/image/2303032/free-illustration-vector-mental-health-self-love-meditation)
* [emojis on the hero image](https://www.canva.com/)
* [Logo image](https://www.rawpixel.com/image/3282346/free-photo-image-mental-health-woman-tiredness) All team images used in footer belong to the respective team member.

---
### Collaborators

Team Inside Out members of the January Hackathon 2022:

* [Iuliia Konovalova](https://github.com/IuliiaKonovalova)
* [Aws Sabah Gheni](https://github.com/AwsSG)
* [Theo Wright](https://github.com/theopmw)
* [Kera Cudmore](https://github.com/kera-cudmore)
* [Anna](https://github.com/ANNAhabANNA)

---
### Acknowledgments

We would like to acknowledge the following people who helped us along the way in completing this project:

* [Dave Bowers](https://github.com/dnlbowers), our hackathon facilitator.
* Our families - for their patience and support while we disappeared for another long weekend of coding.
