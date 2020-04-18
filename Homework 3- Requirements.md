# Homework 3: Requirements
**Purple Recovery**

## Each Page View
*  On the top left of each page, The dashboard header will contain “Purple Recovery” as a title header, and “COVID-19 Information for UW Students” as a subheader. These will be fixed/sticky elements, and will always be visible regardless of the user’s current scrolling position.

### Submit a Resource, Feedback, or Note Form
* On the bottom right of each page, there will be a fixed square section, containing, “Anything missing?” and a button that contains the text “Drop a Note”. Clicking the “Drop a Note” button will overlay a modal card form on top of the user’s current page position. 
* The form then contains a card title, description, input fields, and a “Submit” button. By default, "Resource?" and "Feedback?" checkboxes will be unselected, rendering their specific sub-input fields to be less opaque than the rest of the form. See figure 1. 

![form screen](img/form.png)
*Figure 1*

* When either "Resource?" or "Feedback?" checkfields are selected, the specific sub-input fields become fully opaque. See figure 2.

![form screen selected](img/form_options_selected.png)
*Figure 2*

* For a form to be submittable, it has to have three required pieces of information: a full name, a valid email, and either a completed “Resource?” portion or “Feedback?” portion, as well as a passed CAPTCHA test. 
* Selecting “Resource?” will additionally require the user to:
	* have selected a “Type of Resource” in a dropdown menu consisting of the following options: Resources, Responses, Community, Trackers and Dashboards, and Other/I’m Not Sure
	* have provided a valid link to the resource. 
There is also a “Notes” input that is optional.
* Selecting “Feedback?” will additionally require the user to provide text response in the “Feedback” input field.
* Clicking the “Submit” button will prompt the user to complete a CAPTCHA test. Upon passing, their form submission will be sent to Purple Recovery for review. 

## Main Dashboard View

### Top Right of Page
* In the top right corner of  the home page, there will be a banner displaying the most recently added UW Message (which includes every and all messages posted in the UW COVID-19 Page under the “Messages & Updates”). 
* This will update whenever there is a new message added by Purple Recovery admin, or whenever a submitted UW Message to us (via the “submit resources” form) is verified. 

### Main Layout

![main dashboard screen](img/v1_UI_main_dashboard.png)
*Figure 3*

* The main dashboard will have four main sections: Resources, Responses, Community, and Tracking and Dashboards. See figure 3.
* Each main section will have either a card button with just text, or a card button with text and an image. Either one of these will redirect the user to the corresponding link address.
* Each main section will have a button at the bottom right of it, with the appropriate text detailed above (Resources - “See All”, Responses - “Find Articles”, Community - “Stay Connected”, and Trackers and Dashboards - “View Stats”). Clicking into any of these will lead the user into the respective main section’s individual section view page. 
* Resources will be divided into two subsections as columns. 
* The first subsection under Resources is “UW FAQs”, which will contain 5 card buttons with just text. The 5 reflects the five main navigation items from the UW COVID-19 FAQ: “Health, Wellness, and Prevention”, “Staff and Student Workers”, “Classes, Academics & Commencement”, “University Operations”, and “Travel and Study Abroad”. Clicking into any one of the 5 card buttons will redirect the user to the corresponding section on the UW FAQ Page. 
* The second subsection under Resources is “Quick Links”, which consolidates all of the hyperlinks found on the UW COVID-19 FAQ page as a list of text hyperlinks. Clicking into any one of them will redirect the user into the corresponding link address. 
* The Responses section will contain links to UW-community published articles. These will be displayed as card buttons with the article title and the page cover image in the article (if available). The section will display 3 of the most recently added articles to Purple Recovery. 
* The Community section will contain links to Purple Recovery team-curated community resources that help the UW Community socialize and feel more connected to the overall campus. These will be displayed as card buttons with the Community resource title and a related icon. 
* The Trackers and Dashboards section will contain links to data visualization dashboards regarding COVID-19 statistics. These will be displayed as card buttons with the Tracker or Dashboard name. 

## TODO: Individual Section View 
