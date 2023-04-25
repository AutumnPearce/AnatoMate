# AnatoMate

AnatoMate is an interactive anatomy learning website that includes a learning mode and a quiz mode to help users learn about human anatomy. The website consists of three main pages: the title screen (<code>index.html</code>), learning mode (<code>learning_mode.html</code>), and quiz mode (<code>quiz_mode1.html</code>).

The tasks addressed in this learning tool are:
1. Turning on/off labels to encourage better memorization
2. Self-assessment of knowledge through a quiz to encourage active learning

# How to Use

For web server demo:
To set up the website, download the source files and open the <code>index.html</code> file in a web browser. Users can navigate between pages by clicking on the appropriate text or banners.

You may follow the instructions below to demo the website:

For Kinect demo:
Zip the project folder and upload it to the kinect server. Follow the instructions on screen to navigate between pages through gestures.

# Dependencies

There are no dependenices, only a web browser is required. The project can run by opening <code>index.html</code> in a browser.

# Constraints

- If there are more than one person within detection range, there is no current way to indicate which person should control the display.
- standing too close etc.

---

# Collaboration record

- Serena Ulammandakh (tu54): Changed the .css files to make the images, titles, and headers centered-ish and changed aesthetic styling of all the relevant .html pages. Added initial page connection between the html pages and implemented click event listeners to be modified later for display functionality. Compiled all the html quiz and results pages into one .html page that displays quiz questions (using javascript) and the corrosponding correct answers after each selection. Quiz mode shows the quiz results at the end. Wrote out README.md file.  
- Aviv Melamud (am3795): Wrote javascript code to read data from the kinect and interpret hand gestures by calculating the angles between joints (i.e. determine if hand is raised by calculating angle between hand, shoulder, and pelvis) and by comparing relative positions (check if hand is higher then head). Made screens react to hand gesturs (switching images and screens when appropriate).
- Autumn Pearce (agp32): Created the png images for each screen. Standardized the text/image locations for any screen size. Tested our design on the display. Coded in the images that show an example of user hand motions.
- Nikhil Ismail (ni58): coded out quiz and results pages (js, html, css), coded user feedback for quiz (incorrect/correct message)



