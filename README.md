# Employee-Management
Hi,
For this to work user need to set up virtual environment(just to make sure that actual python variables and settings is not messed up).
Second, Up and running MySQL server where it can save your database.
Third, Python(3.4.x)+ preferred. 
I think thats all.

ERRORS : 
Some problems which i faced:
1. Make sure that everything is of same configuration what i mean is if you are insatlling x64 version of python make sure that mysql is of same version.
2. Second to download extensions follow this link : http://www.lfd.uci.edu/~gohlke/pythonlibs/#mysql-python 
3. User can even download dependencies/extensions from command prompt/bash directly but in case you need different versions(x32/x64) of them refer to above link.
4. During execution if you get error to set environment variables:
      for windows: set environment_variable='Value'
                    MAKE SURE THAT THERE IS NO SPACE BETWEEN ENVIRONMENT_VARIABLE AND = !!!!
      for linux: use export instead of set.
5. Database creation one might get error to update mysqldb. That error has nothing to do with MySQL. In that case uninstall your 'MySQL_CLlient' dependency and download the required one, don't uninstall MySQL or its extension.
6. Beaware of CIRCULAR REFERENCES/DEPENDENCIES !
