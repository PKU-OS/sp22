# PKUOS Spring 2022 website
This repo contains the source code of the website for the Spring 2022 Operating Systems Course Honor track at Peking University. The repo for the main page is [here](https://github.com/PKU-OS/PKU-OS.github.io).

## Usage
It is easy to create websites for further semesters:

- Add one entry point in the [main page](https://pku-os.github.io/). See [here](https://github.com/PKU-OS/PKU-OS.github.io) for details.

- Copy this repo into a new repository.

- Change the *baseurl* attribute in [_config.yml](./_config.yml) and turn on the Github Pages. Then you can have access to your website at ***https://pku-os.github.io/***.

- Now update the staffers, calendar, announcements and schedules as needed.

## Content
- _modules/ : the weekly schedule, ppt link and homework release
- _announcement/ : the weekly announcement, e.g. exam date
- _schedules/ : the weekly calendar, e.g. office hours
- _staffers/ : teacher and TA info
- assets/ : static files, e.g. ppt, pdf
    - images
    - notes

## Other Files
- _config.yml : configuration file for the website
- _includes/ : reused components
- _layouts/ : html templates
- _sass/ : css template
- _site/ : generated static website
- Gemfile : dependency packages list
- LICENSE : MIT license


## Acknowledgement
This website is supported by [Just the Docs](https://pmarsceill.github.io/just-the-docs/), a documentation theme for Jekyll.
