# Resume Builder

This is a simple app that allows you to create a resume using a form. The app is built using the T3 stack.

## How templates work

This app uses the mustache templating engine to complete the resume with the resume items. Then, it uses the `Latex.js` binary to convert the Latex template to HTML. Finally, the app uses the `html-pdf` package to convert the HTML resume to a PDF file.

## How create a resume

To create a new resume, you need to login using your LinkedIn account. Then, you should click the create new resume button. This will bring a popup form where you can select the items of your LinkedIn profile that you want included in that resume based on the template you choose.

## DISCLAIMER:

* This app is only a work in progress and is not ready for production, but use at your own risk, as it might not work or upload your own templates. For now.

* This app is not affiliated with LinkedIn, and it is not endorsed by LinkedIn.

* I don't save your LinkedIn data, I only use it to create the resume. This might change in the future in order to implement better features.
    - [ ] Save the created resume to be modified later.
    - [ ] Save the resume template to be modified later.
    - [ ] Save the LinkedIn data to be used in the future.

