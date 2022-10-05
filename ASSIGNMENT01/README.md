# ASSIGNMENT #01: Heuristic Evaluation

## Accessible and Sustainable Transportation in Jakarta, Indonesia

*by Brian Roysar | DH 110: User Experience Design*

### About The Project

This project will focus on the 11th Sustainable Development Goal (SDG), Sustainable Cities and Communities, established by the United Nations (UN) as a way to achieve a "shared blueprint for peace and prosperity for people and the planet" by 2030. The project will be focusing on a small subset of this overarching goal which is the creation of more accessible and sustainable transportation in Jakarta, Indonesia.

Having lived in Jakarta my entire life, I've experienced first-hand how inefficient transportation and commuting can be. A lack of structured roads and public transportation only being in its early stages of development, the lack of accessible and efficient transportation has frustrated many Indonesians as commute times and congestion are exponentially high. In addition, with Indonesia being in the top 20 most polluted countries in the world, there should be a larger emphasis on improving the sustainability of many of our transportation methods to maintain a good quality of life in the long term.  

Thus, I want to use this UX project to create a website or mobile app that will encourage fellow Indonesians to learn more about and use existing public transportation systems in order to reduce both congestion and pollution from private vehicles such as cars and motorcycles.

### About This Assignment

In this assignment, I will be conducting a heursitic evaluation through examining the _10 Usability Heuristics of User Interface Designs_ and _Severity Ratings for Usability Problems_ of two websites that are similar to the project idea I chose. 

### Website #1: MRT Jakarta
![MRT Jakarta's Home Page](./images/mrt_jakarta_home.png)
[Website Link](https://jakartamrt.co.id/en)

#### Information About The Website
jakartamrt.co.id is the official website for the Jakarta MRT system that was recently opened in the past decade. The website serves the purpose of highlighting the mission/vision of the project, the recent developments of the project, and most importantly, provides travelers with information about routes given a source, destination and time. 

#### Overall Evaluation of The Website
Although the website is clean and relatively simple to use, it does not efficiently captivate citizens to use the website. This is because the design is very bland and feels outdated to an extent. The presentation of data (whether this is route information, times that the MRT leaves and arrives, and payment methods) is not appealing, which not only makes information difficult to digest, but also less memorable to the user. 


<table>
  <tr>
   <td>Heuristic + Explanation
   </td>
   <td>Detailed Analysis
   </td>
   <td>Recommendation
   </td>
   <td>Severity Rating
   </td>
  </tr>
  <tr>
   <td><strong>#1: Visibility of system status</strong>
<p>
Interface should be able to inform user about what state the system is in
   </td>
   <td><strong>Positive: </strong>When a user is in a subpage, the website underlines the current subpage the user is on, and the sub-sub page is shown in the header
<p>
<strong>Positive: </strong>It shows what current language the website is in (Indonesian or English) on the upper right corner
<p>
<strong>Negative: </strong>To establish a new route or a new time, we have to refresh/click a button, and this takes a long time 
   </td>
   <td>For refreshing the route information, any change on the destination/source or the time should update the displayed route information in real time, without the extra effort from the user
   </td>
   <td>2
   </td>
  </tr>
  <tr>
   <td><strong>#2: Match between system and the real world</strong>
<p>
System should replicate the user’s real life experiences and understanding of the world into the user’s experience
   </td>
   <td><strong>Positive: </strong>The website uses simple words and icons to allow users to understand functions easier, and tie in what they know about the world into their experience (i.e. clock symbol indicates schedule)
<p>
<strong>Positive: </strong>The <em>from </em>field comes before the <em>destination </em>field, which replicates a user’s geographical understanding of the two locations
<p>
<strong>Negative: </strong>One of the headers/subpages is named “e-procurement” which might be an unfamiliar term to some.
   </td>
   <td>Find a simpler term for the header with words that people use more often
   </td>
   <td>1
   </td>
  </tr>
  <tr>
   <td><strong>#3: User control and freedom</strong>
<p>
Allows users to backtrack on unwanted actions
   </td>
   <td><strong>Positive: </strong>User can press the MRT Jakarta logo in the top left corner to go back to the home screen
<p>
<strong>Negative: </strong>When a user navigates to the e-procurement subpage, it seems to have not a way back to the home page
   </td>
   <td>Add a button that allows user to navigate to the home page
   </td>
   <td>2
   </td>
  </tr>
  <tr>
   <td><strong>#4: Consistency and standards</strong>
<p>
Website should follow industry conventions, standards and jargon and be consistent throughout the website
   </td>
   <td><strong>Positive: </strong>Uses terms such as <em>route </em>and <em>schedule </em>consistently throughout the website and also is a standard in other transportation systems
<p>
<strong>Negative: </strong>The UI (from the font to the elements) differ between the e-procurement subpage and the rest of the website
   </td>
   <td>To improve on this, standardize the fonts, buttons, elements used between the two
   </td>
   <td>2
   </td>
  </tr>
  <tr>
   <td><strong>#5: Error prevention</strong>
<p>
System should minimize the chance a user encountering errors
   </td>
   <td><strong>Positive: </strong>The system does not allow us to search up invalid routes (e.g. routes with the same start and end, or routes that do not fall under operational hours) 
<p>
<strong>Negative: </strong>Allows user to look up routes for dates before today - this might confuse users and mislead them if they accidentally inputted the wrong time/date
   </td>
   <td>The website should restrict and not show information about routes that have occurred (whether it is an error message or prompt). 
   </td>
   <td>2
   </td>
  </tr>
  <tr>
   <td><strong>#6: Recognition rather than recall</strong>
<p>
Reducing cognitive effort from users by making elements and actions visible and memorable
   </td>
   <td><strong>Positive</strong>: Uses standardize and familiar icons so users remember the functionality of certain tasks better 
<p>
<strong>Negative: </strong>The website has many sub sub pages within the sub pages, and for navigation, this might make it harder for the user to keep track of where things are
   </td>
   <td>Remove redundant pages, and join pages that can be categorized into one topic 
   </td>
   <td>2
   </td>
  </tr>
  <tr>
   <td><strong>#7: Flexibility and efficiency of use</strong>
<p>
Provide shortcuts and ease of navigation for users of all different skill/experience levels
   </td>
   <td><strong>Negative: </strong>Does not allow the user to search up routes only using a keyboard efficiently (dependent on mouse)
   </td>
   <td>Allow compatibility with <strong>tabs, arrow keys and shift </strong>for a user to search what they need with ease and less dependent on the mouse
   </td>
   <td>1
   </td>
  </tr>
  <tr>
   <td><strong>#8: Aesthetic and minimalist design</strong>
<p>
Website contains only necessary information and minimize information bloating
   </td>
   <td><strong>Positive: </strong>The home page gets straight to the point and has the route finding input box front and center
<p>
<strong>Negative: </strong>The informational aspect of the website has paragraphs on paragraphs of text which makes information unappealing and indigestible
   </td>
   <td>Utilize illustrations and icons to convey the same message, without needing too much text
   </td>
   <td>2
   </td>
  </tr>
  <tr>
   <td><strong>#9: Help users recognize, diagnose, and recover from errors</strong>
<p>
Ability to prompt users with correct error messages and possible solutions to fix or navigate the error
   </td>
   <td><strong>Positive: </strong>Whenever a user inputs an invalid route, the system prompts the user of the error and how to fix it
   </td>
   <td>N/A
   </td>
   <td>1
   </td>
  </tr>
  <tr>
   <td><strong>#10: Help and documentation</strong>
<p>
Provide instructions or a manual for a user on how to navigate and complete tasks on the website
   </td>
   <td><strong>Negative: </strong>The website does not have instructions on how to use the route finding functionality
   </td>
   <td>To educate users, provide a document or video that illustrates, step-by-step, on how to use it
   </td>
   <td>2
   </td>
  </tr>
</table>

