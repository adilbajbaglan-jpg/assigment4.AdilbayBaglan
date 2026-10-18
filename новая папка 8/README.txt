Assignment 4 - Forms and Validation
Student: Baglan Adilbay
Group: IT-2512

Open task1.html, task2.html and task3.html in a current browser.
Bootstrap CSS and Montserrat fonts are local, so no internet is needed.
The source contains HTML and CSS only, with no JavaScript, pattern or novalidate.

Submission steps:
1. Create your GitHub repository and upload task1.html, task2.html, task3.html,
   styles.css and the complete assets folder.
2. Add the real repository URL to the report before submission.
3. Submit Assignment4_Baglan_Adilbay.pdf (not this ZIP) to the course platform.
4. Attend the practice defense and be ready to explain and modify the code.

These are frontend demonstrations, not a live booking or registration service.
Task 2 uses POST so that a password is not put in a query string; there is no
server endpoint in this HTML/CSS assignment. Do not enter a real password.
Task 1 and Task 3 submit GET data back to the same page for demonstration.
Clear resets Task 1 to empty defaults. The reference screenshot's selected
values must be entered by the user because prefilled HTML defaults would be
restored by a reset button, instead of being cleared.

Defense notes:
- id connects a control to its label; name determines its submitted key.
- Radios with the same name allow one choice; checkboxes are independent.
- required rejects empty fields and unchecked required checkboxes.
- min/max define numeric or date/time limits; step defines valid increments.
- Time step is measured in seconds: 1800 seconds = 30 minutes.
- minlength/maxlength constrain user-entered text.
- type=email and type=url provide native format validation.
- :user-invalid displays feedback after user interaction or attempted submit.
- Bootstrap col-12 stacks fields; col-md-6 makes two desktop columns.
- flex-column-reverse changes visual button order on mobile; HTML order stays.
- fieldset and legend give related radio buttons a meaningful group name.
- Browser validation improves usability but a real backend must revalidate.
