# Datepicker Test Application

This application exists to display the behaviour of the Datepicker-Control, when embedded in a vertical scrollable page.

Steps for reproduction:

- Install npm packages -> run "npm i" in your terminal while being in the project folder
- Run the "UI5 Version 1.93.7"-Version of the application for reproduction of the working scenario -> run "npm run start:1.93.7"
- Run the "UI5 Version 1.94.0"-Version of the application for reproduction of the non-working scenario -> run "npm run start:1.94.0"
- Scroll down (!!!) to the Datepicker and try to open and close it repeatedly. Its important to scroll to the page bottom here.

In the non-working scenario your browser should jump to the page-top while leaving the controls popover empty.

