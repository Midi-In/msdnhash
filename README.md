msdnhash
=============
In June 2017, the MSDN subscriber portal was "taken offline", with the new Visual Studio portal only being open to subscribers.
While it worked for a few months after showing/hiding some DOM elements, it was finally completely removed in October 2017.  
This project aims to preserve MSDN's catalog of files for reference purposes.

### Instructions
It's mostly your typical Django project.
Copy `settings_private.example.py` to `settings_private.py` and put your configuration in there.
#### Data import
For a one-time import of the MSDN data, run `grab.py` in the util directory to retrieve the data, then `manage.py import` to load into the database.
Upsert support coming soon.
