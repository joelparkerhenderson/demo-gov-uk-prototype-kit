# Demo GOV.UK Prototype Kit

Demonstration of the GOV.UK Prototype Kit, which helps developers quickly make interactive, accessible and realistic prototypes of GOV.UK services.

https://prototype-kit.service.gov.uk/

Run:

```sh
mkdir demo-gov-uk-prototype-kit && cd $_
npx govuk-prototype-kit@latest create
```

## Files and folders in your prototype

The folder `app` is the main folder that includes everything for your prototype. 

Inside is:

* `assets` is where you can find CSS, JavaScript, images and downloadable files
* `data` is for adding data files
* `views` is where you can find all your pages
* `config.json` is where you can change your service name
* `routes.js` is for advanced logic such as how to route users to pages
  
## Run the prototype locally

Run:

```sh
npm run dev
```

You will probably see many warnings such as:

* Deprecation Warning [import]: Sass @import rules are deprecated and will be
  removed in Dart Sass 3.0.0.

* Deprecation Warning [mixed-decls]: Sass's behavior for declarations that
  appear after nested rules will be changing to match the behavior specified by
  CSS in an upcoming version. To keep the existing behavior, move the
  declaration above the nested rule. To opt into the new behavior, wrap the
  declaration in `& {}`.

* Warning: The legacy organisation colour palette has been deprecated and will
  be removed in the next major version. To silence this warning, update
  $govuk-suppressed-warnings with key: "legacy-organisation-colours"

Browse http://localhost:3000 and you should see a demo page.

## Tutorial

The GOV.UK Prototype Kit tutorial shows you how to prototype a fictional 'Apply
for a juggling licence' service that will:

* ask 2 questions

* show the user's answers for them to check

* show a confirmation page

You can read more here:

https://prototype-kit.service.gov.uk/
