# PKUOS Spring 2022 website
This repo contains the source code of the website for the Spring 2022 Operating Systems Course Honor track at Peking University. The repo for the main page is [here](https://github.com/PKU-OS/PKU-OS.github.io).

## TODO
### Instructor
- syllabus.md : introduction, policy, grading.
- add slides into *assets/slides* folder.

### TA
- Resources page.
- Gradescope registry.
- Project gitbook.
- Project warmup notes/ppt.
- Practise homework/exam.

## Structure
**files marked as TODO are to be changed as course goes**
### Contents
- _modules/ : the weekly schedule, ppt link and homework release (TODO)
- _announcement/ : the weekly announcement, e.g. exam date (TODO)
- _schedules/ : the weekly calendar, e.g. office hours (TODO)
- _staffers/ : teacher and TA info
### Navigation components
- courseinfo.md (TODO)
- calendar.md (TODO)
- index.md (TODO)
- announcements.md
- staff.md
- schedule.md
### Support files
- _config.yml : configuration file for the website
- _includes/ : reused components
- _layouts/ : html templates
- _sass/ : css template
- assets/ : static files, e.g. ppt, pdf, images (TODO)
    - images
    - notes
- _site/ : generated static website
- Gemfile : dependency packages list
- CNAME : domain name file
- LICENSE : MIT license

## Portability
It is easy to create websites for further semesters:

- Add one entry point in the [main page](https://pkuos.systems). See [here](https://github.com/PKU-OS/PKU-OS.github.io) for details.

- Copy this repo into a new repository.

- Change the *baseurl* attribute in [_config.yml](./_config.yml) and turn on the Github Pages. Then you can have access to your website at ***https://pkuos.systems/baseurl***.

- Now update the staffers, calendar, announcements and schedules as needed.

## Acknowledgement
This website is supported by [Just the Docs](https://pmarsceill.github.io/just-the-docs/), a documentation theme for Jekyll.
