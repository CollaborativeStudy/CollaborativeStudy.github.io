<html>
  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="chrome=1">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <link href='https://fonts.googleapis.com/css?family=Architects+Daughter' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" type="text/css" href="stylesheets/stylesheet.css" media="screen">
    <link rel="stylesheet" type="text/css" href="stylesheets/github-light.css" media="screen">
    <link rel="stylesheet" type="text/css" href="stylesheets/print.css" media="print">

    <!--[if lt IE 9]>
    <script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->

    <title>Collaborative Study by CollaborativeStudy</title>
  </head>

  <body>
    <header>
      <div class="inner">
        <h1>Collaborative Study</h1>
        <h2>Don&#39;t fail together</h2>
        <a href="https://github.com/CollaborativeStudy" class="button"><small>Follow me on</small> GitHub</a>
      </div>
    </header>

    <div id="content-wrapper">
      <div class="inner clearfix">
        <section id="main-content">
          <p><img src="/screenshots/CSLogo.png"></p>

<h2>
<a id="cs" class="anchor" href="#cs" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>CS</h2>

<p>Collaborative Study (CS) is a scheduling app designed for UH ICS students to plan study sessions together. CS aims for ICS majors to form connections and better one another as students.
Users of this app will be able to:</p>

<ul>
<li>Maintain a public profile page</li>
<li>Find, rate, and form groups with other students</li>
<li>Join and create study sessions through a public calender</li>
</ul>

<!-- <p>Check out our app at <a href="http://cs.meteorapp.com/">http://cs.meteorapp.com/</a></p> -->

<h2>
<a id="guided-tour" class="anchor" href="#guided-tour" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Guided Tour</h2>

<h4>
<a id="public-landing-page" class="anchor" href="#public-landing-page" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Public Landing Page</h4>

<p><img src="/screenshots/publicLandingPage.png">
The first page users see before logging in is an informational page about Collaborative Study. Users will log in under the the "Account" dropdown using their UH username and password.</p>

<h4>
<a id="profile-page" class="anchor" href="#profile-page" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Profile Page</h4>

<p><img src="/screenshots/profilePage.png">
Each user receives an editable profile page so others may learn more about them.</p>

<p>On this page, users can create a listing of courses under two categories, "Pros" or "Studs". Pros (short for "Professors") are classes students are competent in, while Studs (short for "Students") are classes they might need help in. Courses are color coded to reflect the individual's confidence of understanding of the subject matter; green: well understood, yellow: some gaps in understanding, red: limited knowledge.</p>

<h4>
<a id="review-page" class="anchor" href="#review-page" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Review Page</h4>

<p><img src="/screenshots/reviewPage.png">
Accessed from the "Reviews" button on a profile, the reviews page is a listing of ratings and reviews left by other users about the profile's owner. Any user is welcome to submit reviews for another user, though they are regulated by an administrator after submission.</p>

<h4>
<a id="my-calendar-page" class="anchor" href="#my-calendar-page" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>My Calendar Page</h4>

<p><img src="/screenshots/myCalendar.png">
The Calendar page is a visual display of all upcoming public study sessions you have joined. Users may click on a day to create a study session for that day, or may click existing study sessions for more details.</p>

<h4>
<a id="groups-page" class="anchor" href="#groups-page" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Groups Page</h4>

<p><img src="/screenshots/groupsPage.png">
When users become comfortable working with specific students, they can form a study "Group" to quicken the process of making study sessions with them. Users may create new groups or join existing ones through the groups page.</p>

<h4>
<a id="study-session-page" class="anchor" href="#study-session-page" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Study Session Page</h4>

<p><img src="/screenshots/studySessionsPage.png">
A listing of all the upcoming study session created by users on CS. Study sessions may be searched for by course using the search bar at the top.</p>

<h4>
<a id="study-session-details-page" class="anchor" href="#study-session-details-page" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Study Session Details Page</h4>

<p><img src="/screenshots/studySessionDetailsPage.png">
A more detailed explanation of a study session can be brought up, either through clicking the "More Info" button on the Study Session Page or clicking a study session on the calendar.
From here, users may join the study session as a Pro (tutor) or Stud (tutee). Students that join as Pros are welcome to add and remove topics that will be taught at that session.</p>

<h4>
<a id="create-study-session-form" class="anchor" href="#create-study-session-form" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Create Study Session Form</h4>

<p><img src="/screenshots/createStudySessionPage.png">
Clicking on a day in the calendar results in a modal to create a study session on that day. Users will specify the session title, course, topic, start time and end time for their session.</p>

<h4>
<a id="public-calendar-page" class="anchor" href="#public-calendar-page" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Public Calendar Page</h4>

<p><img src="/screenshots/calendarPage.png">
The public Calendar page is a visual display of all upcoming public study sessions, including sessions that the user has not signed up for. Users may click on a day to create a study session for that day, or may click existing study sessions for more details.</p>

<h4>
<a id="chat-room-page" class="anchor" href="#chat-room-page" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Chat Room Page</h4>

<p><img src="/screenshots/messagesPage.png">
A chat room for all online users is also available under the "Chat Room" tab.</p>

<h2>
<a id="developer-guide" class="anchor" href="#developer-guide" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Developer Guide</h2>

<p>If you would like to make modifications to this app, download Meteor (<a href="https://www.meteor.com/">here</a>) and any IDE of your choice. Personally, our team enjoyed using <a href="https://www.jetbrains.com/idea/">IntelliJ IDEA</a>. Please note that you should be comfortable with HTML, Javascript, CSS, and Jquery before working on our code. The tutorials provided on the Meteor website should also help you get used to the platform.</p>

<p>After downloading Meteor, clone <a href="https://github.com/CollaborativeStudy/CS">our repo</a> from GitHub and get working on it. You may run the app locally through the command line by changing to the "app" directory and running "meteor --settings ../config/settings.development.json".</p>

<p>When you are finished making changes, send us a pull request and we'll check it out!</p>

<h2>
<a id="who-are-we" class="anchor" href="#who-are-we" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Who are we?</h2>

<p>We are CollaborativeStudy, a group of Information and Computer Science (ICS) majors at the University of Hawaii at Manoa. As ICS majors, we know best: the life of a computer science student can be a difficult and lonely one. It isn't unusual to be a lone wolf, studying by yourself. </p>

<p>Our organization came together to end that. Together, we are developing a student app that allows ICS majors to connect and study with other students. Doing this will create a fun and safe environment for students who want to make friends but are too shy or intimidated to do so. I hope you will support us throughout this development!</p>

<h2>
<a id="our-journey" class="anchor" href="#our-journey" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Our Journey</h2>

<p> We have work on this project for months and we are proud of how far it has come. It started as our group assignment and turned into a side community project. Our goal is to make this web application relevant to the ICS department. Hopefully we will reach that goal but as of right now it is still a work in progress. <p>
<p> To view the progress we're making on the app, see our project milestones at <a href="http://github.com/CollaborativeStudy/CS/projects">http://github.com/CollaborativeStudy/CS/projects</a></p>

<h2>
<a id="initial-user-study" class="anchor" href="#initial-user-study" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Initial User Study</h2>

<p>The test subjects were different majors. We wanted to see how other people would react to this app. We had one ICS major, and the rest were engineer majors, a communications major, an accounting major and a dental hygiene major. We separate these people into three group studies. We had them go to our website and use it without too much instruction. As they dive into our app, they provided all the feedback they could offered. </p>

<p>The majority agreed that overall the main features seemed to work okay however there were a few bugs. Sometimes tutorial blocks will not exit and some actions did not do anything. They even offered many suggestions for improvement. However, for a first test try we believe that we showed great features and a lot potential to our first users!</p>

<h2>
<a id="usability-test-4-11" class="anchor" href="#usability-test-4-11" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Usability Test 4/11/17</h2>

<p>CS held it's second usability test on April 11th, 2017 with a group of three UH Manoa students of varying majors. Along with some bugs, we found two significant areas that need attention:</p>

<ul>
<li>organization and reasoning behind certain elements of the app (most notably, the “proficiency” rating)</li>
<li>providing thorough explanation of usage, so as to ease the user experience</li>
</ul>

<p>Suggested improvements and issues are listed below by the page they were designated for.<p>

<p>My page</p>
<ul>
<li>Course listing should include all possible ICS courses offered at UH Manoa</li>
<li>Pro and stud sets should be disjoint; a user cannot be both a tutor and a tuttee at a subject</li>
<li>Possibly rename “stud”, as it is common slang for being skilled at something</li>
<li>Proficiency is unecessary if the courses are already being separated into pros and studs. It is redundant to have “high” proficiency as a pro and “low” proficiency if you're a stud. Additionally, it doesn't make sense to say one has “high” proficiency as a student.</li>
<li>Include an “add all” option for courses</li>
<li>If proficiency is kept as an aspect to the app, the tutorials should explain the color meanings and explain how to change it</li>
<li>Red (used for low proficiency) is too bright and degrading</li>
</ul>

<p>Reviews</p>
<ul>
<li>Should indicate when a user is not yet rated vs. having zero stars</li>
</ul>

<p>Create Study Session</p>
<ul>
<li>Study session data should be editable</li>
<li>Both pros and studs should be able to add topics, or, an explanation for why only pros can add topics should be included</li>
<li>Buggy clicking to activate the modal from the calendar</li>
</ul>

<p>Chat</p>
<ul>
 <li>Spam filter suggested to limit sending multiple messages in a short time period</li>
 <li>Shift+enter should add a new line instead of sending message</li>
 <li>Automatic scrolling when new messages are sent</li>
 <li> Timestamps</li>
</ul>

<p>Groups</p>
<ul>
<li>Upload image option instead of solely URL</li>
<li>“Member is already in this  group or does not exist” error unclear</li>
<li>Button should say “Edit” instead of a picture, instead of being a picture and changing to “Edit” on hover</li>
<li>Button animation doesn't continue after a click, instead remains as “Edit”</li>
</ul>

<p>Group Sessions</p>
<ul>
<li>Buggy submission with modals unable to close</li>
<li>Form should allow for more time options, along with a “Year” field for the date.</li>
<li>Data validation to prevent “fake dates” (ex: February 30th) or dates significantly into the future from being submitted</li>
<li>Fix padding on modals</li>
</ul>

<p>Study Sessions Page</p>
<ul>
<li>Dates should be listed on cards instead of only in details</li>
</ul>


<p>Tutorial</p>
<ul>
<li>Tutorials should have instructions for first time users with arrows pointing to the topics in question</li>
</ul>

<p>General</p>
<ul>
<li>Options for military time in addition to standard</li>
<li>Back buttons</li>
</ul>

<p>Thank you for the participants in the test. With this criticism, CS can improve to become much fmore useful and user-friendly.</p>


<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Authors and Contributors</h3>

<p>Click our names for our online portolios or check out our githubs!<br></p>

<p><a href="https://mariahgaoiran.github.io/">Mariah Gaoiran</a> (<a href="https://github.com/mariahgaoiran" class="user-mention">@mariahgaoiran</a>) <br>
<a href="https://chadmorita.github.io/">Chad Morita</a> (<a href="https://github.com/chadmorita" class="user-mention">@chadmorita</a>) <br>
<a href="https://marysantabarbara.github.io/">Mary Santabarbara</a> (<a href="https://github.com/marysantabarbara" class="user-mention">@marysantabarbara</a>) <br></p>
        </section>

        <aside id="sidebar">
          <a href="http://cs.meteorapp.com/" class="button">The CS App</a>
          <a href="https://github.com/CollaborativeStudy/CS" class="button">CS Github Repo</a>

          <p>This page was generated by <a href="https://pages.github.com">GitHub Pages</a> using the Architect theme by <a href="https://twitter.com/jasonlong">Jason Long</a>.</p>
        </aside>
      </div>
    </div>

  
  </body>
</html>
Contact GitHub API Training Shop Blog About
© 2017 GitHub, Inc. Terms Privacy Security Status Help
