Workshop Repository
==============================

Directory structure
-------------------

workshops

- The actual workshops. 
- Do not create copies of workshops in this repo.
- Clone the git repository, do your work, merge back any updates to 
  the master workshop.

themes

- Sphinx themes, referenced in conf.py:

  - html_theme_path should relatively reference this directory
  - html_theme selects which theme to use

Resources
---------

A workshop may depend on external data and/or software:

- SOFTWARE

  - Your workshop should note the versions required
  - Your workshop should include a URL to download the software
  - Don't check software into the repository

- DATA

  - Your workshop should include a URL to download a zip file of the data
  - Workshop data should be stored and linked to.
  - You should name your zip file with a date or version number to allow 
    old versions of the workshop to have a longer lifespan
