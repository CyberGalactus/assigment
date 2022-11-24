Hi Edu!

Great work and nice design, it looks very professional.

As you will see below, you have nearly done everything that was required - congratulations!

At this stage you easily have a Godkänt grade, but because the email form was a required part of the assessment until that is fixed I unfortunately can't give you a VG grade.

I've added a link below that shows what needs to be done - adding an action to the form and adding some value for the names of the inputs.

So it's your choice - if you are happy with Godkänt you dont need to do anything, but if you want that Välgodkänt grade please fix the from, push the changes to github and let me know so I can have another look. 

*************************************

CRITERIA FOR GRADING

*************************************

GODKÄNT:
-------------------------------------

3 separate pages: ✅

A header with a page title on every page: ✅
  No one knows extactly how google's search algorithim works, but the best practise is to have only one h1 on each page, and it should have unique content. You've used an h1 with your name in the header on all pages, and on "Portfolio" an "About me" yout hav another h1 for the page title.

A navigational menu every page with links to the other pages: ✅

Contact form:
    Email: ✅
    Message: ✅
    Required: ✅
    Mail to: ❌
    When clicking the submit button, the form should fire an "action" that opens up an email client and adds the fields to the email body. This link should help: https://www.w3schools.com/html/tryit.asp?filename=tryhtml_form_mail

RWD:
    Desktop: ✅
    Mobile: ✅

External CSS: ✅

-------------------------------------

VÄLGODKÄNT:
-------------------------------------

Current page indication in the menu: ✅
  Check "Contact" in the mobile menu on the "Contact" page!

Responsive Image: ✅

RWD:
  Media Query: ✅
  Flex/Grid: ✅

Separate CSS: ✅
  There is a bit of duplicated css - for example you have the header, nav bar and footer syling in all 3 css files.
  The best approach is to make separate header and footer css files and include them in all html pages, then only have the page specific css in the individual page css files.
  In coding you only want to write everything once!
  Semantic: ✅

Semantic Element naming: ✅

Code Style:
  HTML: ✅
  Really nice and easy to read!
  CSS: ✅
  Mostly good, a few places the style is a bit off. With css you should have a space befre the opening { and a new line after each code block. EG:

  .header{
    padding: 0px 30px;
    background: url(../images/20210915_163154_master.jpeg);
    background-size: cover;
  }
  nav ul{
    ...

 Should be like this

 .header {
    padding: 0px 30px;
    background: url(../images/20210915_163154_master.jpeg);
    background-size: cover;
  }

  nav ul {
   ...