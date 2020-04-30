# django_boilerplate

A basic django boilerplate project to make it easier to get started with a new project setup.

### Changes made from the normal django setup

   * 1. Included setup for the **django-debug-toolbar** to be used as additional refrence to aid in development
   * 2. Setting up a new base app named **core**
   * 3. Setting up the basic **Template, Static and Media** directories in the main settings file
   * 4. Splitting the usual settings.py file into a directory called **settings** with the genereal base settings in **base.py** a **development.py** file containing development related settings like debug toolbar and a **production.py** containnig production related settings
   * 5. Adding package **python-decouple** for use with the **.env** file to hide crucial information when pushing your code to a public repository
   * 6. Added a renaming command in **core/management/commands** for use in renaming the base project from **demo** to whatever name you prefer
   * 7. Use **base.html and index.html** as your main html files
   * 8. Included is a default python .gitignore template to untrack most python related sensitive files

### STEPS TO USE THIS BOILERPLATE PROJECT

   * [ ] 📝 1. Download the code
   * [ ] 🔎 2. Create a new or activate an existing virtual env depending on your usecase
   * [ ] ➡️ 3. cd into the project directory
   * [ ] ⌨️ 4. Install the dependencies listed in the requirements.txt file with the following command
      **\$ pip install -r requirements.txt**
      _(you can of course bump the versions of any package you'd like in the requirements.txt file manually)_
   * [ ] ✨ 5. Rename project from demo to your prefered name with the following command
      **\$ python manage.py rename <name_of_your_project>**
   * [ ] 🗃 6. Run **\$ python manage.py migrate** to initialize your development db.slite3 database
   * [ ] 🙈 7. Creare your own .env file in the project folder and add sensitive info like secret key and database config
   * [ ] 🚀 8. Use core as your base app and get started **Happy Coding**



