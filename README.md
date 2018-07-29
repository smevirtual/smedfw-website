## SME DFW Chapter Website

This repository contains the source code for the official homepage of the SME
DFW (Dallas-Fort Worth) Chapter found at [smedfw.com](https://www.smedfw.com).

We are an all-volunteer, member-based group which seeks to serve all
engineering/manufacturing students and professionals in the Dallas-Fort Worth
area with value-added events such as factory tours, training events and
collaborative opportunities.

The SME DFW Chapter is a local chapter of SME (formerly the Society of
Manufacturing Engineers). Read more about SME at [sme.org](http://www.sme.org/).

### Development Prerequisites

There are several prerequisites need to be installed on your development
machine prior to working with this codebase.

**Developers should use macOS or Linux to work with this codebase. Issues
encountered using Windows are not considered bugs at this time.**

1.  Install Node.js version 8.0 or greater.

    See [this page](https://nodejs.org/en/download/).

    For macOS development machines, installing Node.js with [Homebrew](https://brew.sh/)
    is recommended.

2.  Install Yarn.

    See [this page](https://yarnpkg.com/en/docs/install).

### Development Quick Start

Once all of the above prerequisites are installed, the following commands are
now available:

| Command                   | Description                                                                                                                                                                        |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `yarn run build:dev`      | Build project in development mode. Development mode artifacts that are generated are suitable for easier debugging.                                                                |
| `yarn run build:prod`     | Build project in production mode. Production mode artifacts that are generated are suitable for deployment to Firebase Hosting (or any CDN).                                       |
| `yarn run clean`          | Delete the `/dist` folder which holds the generated artifacts from the build process.                                                                                              |
| `yarn run deploy`         | Build project artifacts in production mode and deploy to Firebase Hosting.                                                                                                         |
| `yarn run serve:dev`      | Build project artifacts in development mode and run a development browser that will automatically refresh when source files are changed and saved.                                 |
| `yarn run serve:firebase` | Build project artifacts in production mode and launch a local Firebase Hosting environment to verify how the project will look when deployed to a public Firebase Hosting project. |
| `yarn run serve:prod`     | Build project artifacts in production mode and launch a basic, local HTTP server without automatic reloading.                                                                      |

### Hosting Environment

This project is set up to deploy to a [Firebase Hosting](https://firebase.google.com/docs/hosting/)
environment. However, there is no reason that this project cannot be deployed to
another hosting service of your choosing. If you choose another hosting service,
delete the `.firebaserc` and `firebase.json` files in the root of the
repository as they are only needed by Firebase.

If you choose to use Firebase Hosting, then you must change the `smedfw-proj`
key in `.firebaserc` to your Firebase project.

### Community Participation Guidelines

The SME DFW Chapter is committed to providing a friendly, safe and welcoming
environment for all. Please take a moment to read our
<a href="https://github.com/smedfw/community-guidelines/blob/master/README.md">Community Participation Guidelines</a>.

### Contributing

See the [Contributing Guidelines](.github/CONTRIBUTING.md) document.

### License

All of the code in this repository is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
A copy of this license is included in the root of this repository.

### SME Logos and Branding

While this project is permissively licensed, the [SME](http://www.sme.org/) logos
and brands which are part of this codebase are not. SME logo and brand usage
is only allowed by the SME and authorized parties connected to the SME (e.g.
like regional chapters).

If you fork this project for use by your own website or web application, you
must not use SME logos or brands inappropriately. Please see the
[SME Branding Guidelines](http://www.sme.org/sme-logo/) for when a SME logo
can be used and what conditions are attached to SME logos and brands.
