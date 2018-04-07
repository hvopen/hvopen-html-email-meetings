# hvopen-html-email-meetings
The html email template used to deliver meeting announcements via mailchimp.

### Getting started
1. clone this repo:
```
git clone https://github.com/hvopen/hvopen-html-email-meetings.git
```

2. Install the dependancies:
```
npm install
```

3. Run the project
```
npm run build
```

At this point, if everything went well, many things have happened:
- all of the email html in the `./src/pages` directory are built with all css inlined and [foundation inky components](https://foundation.zurb.com/emails/docs/inky.html) built into the proper table format for emailing
- a browser opened to localhost:3000 so you can preview the build emails
- a watch task is running in the terminal to react to changes to html and scss files
- a browsersync task is running in the same terminal that will auto reload the browsers open to the localhost:3000 to show you the changes you made on every save.

### How to build the template
- run `npm build`
- look in the .`/dist` directory and find the `./dist/monthly-meeting.html`

### How to upload the built template:
- todo


## Notes and Resources

### Example mailchimp html with editable and hideable tags
- [https://dague.net//testing/ccl-mailchimp.html](https://dague.net//testing/ccl-mailchimp.html)

### HV Open Branding
- [https://hvopen.org/brand](https://hvopen.org/brand)

### Foundation for Emails
- [https://foundation.zurb.com/emails/getting-started.html](https://foundation.zurb.com/emails/getting-started.html)

### Metadata example on hvopen site
- [https://github.com/hvopen/hvopen-website/blob/master/_events/2018/2018-04-04-unity3d.md](https://github.com/hvopen/hvopen-website/blob/master/_events/2018/2018-04-04-unity3d.md)

### Mailchimp documentation for Template Language
- [https://templates.mailchimp.com/getting-started/template-language/](https://templates.mailchimp.com/getting-started/template-language/)
