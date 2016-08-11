# online-resume
Project #2 for the Udacity Front-End Web Developer Nanodegree

<h2>Project overview</h2>

In this project you will write the JavaScript that powers your own online resume.

This project is meant to be completed while taking the JavaScript Basics course. Throughout the course you'll build your resume by writing a JS script that will combine your personal information with pre-written HTML and CSS templates to generate your resume.

1.  In this project you will store your resume data in four javaScript objects according to the schema given below. As is often the case when leveraging an API, the objects must follow the schema exactly. All properties must be present and have real or fake values. The names must match those in the schema (note that object and property names are case-sensitive). All property values should be of the data-type given for the property in the schema. For example if the data-type is given as an array, it is not acceptable to use a string as a value for that property.

2.  Once you've created your javaScript objects, you will write the code needed to dynamically display all of the resume data contained within these objects in your resume. Your resume should be capable of displaying any resume that provides the data according to the given schema. Note that 'forEach' or 'for' (rather than 'for in') loops must be used to display the skills, jobs, projects, project images, schools and onlineCourses arrays. Your solution should work for any number of items in those arrays.
3.  All of the HTML code needed to build the resume is stored in js/helper.js variables. The variable names indicate their function. You will replace substrings in these variable string values such as %data% and # with the data in your javaScript objects, and append or prepend the formatted result to your resume in the appropriate location.

4.  If you are prompted to do so, you may want to get a Google Maps API key, and include it as the value of the key parameter when loading the Google Maps API in index.html: <script src="http://maps.googleapis.com/maps/api/js?libraries=places&key=[YOUR_API_KEY]"></script> You may have some initial concerns with placing your API key directly within your JavaScript source files, but rest assured this is perfectly safe. All client-side code must be downloaded by the client; therefore, the client must download this API key - it is not intended to be secret. Google has security measures in place to ensure your key is not abused. It is not technically possible to make anything secret on the client-side.
5.  Check your work against the Project Rubric.

6.  When you are satisfied with your project, submit it according to the Submission Instructions on the next page.
