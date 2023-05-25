# Installing Postgres from the command line on windows

The action for this repository demonstrates how to download the windows version of the Postgres installer from the command line:

```
curl https://get.enterprisedb.com/postgresql/postgresql-15.3-1-windows-x64.exe -o postgres.exe
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed

  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
 22  320M   22 72.8M    0     0   155M      0  0:00:02 --:--:--  0:00:02  155M
100  320M  100  320M    0     0   261M      0  0:00:01  0:00:01 --:--:--  261M

    Directory: D:\a\postgresInstaller\postgresInstaller

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---           5/24/2023 11:44 PM      336432992 postgres.exe

PostgreSQL 15
Usage:

 --help                                      Display the list of valid options

 --version                                   Display product information

 --unattendedmodeui <unattendedmodeui>       Unattended Mode UI
                                             Default: minimal
                                             Allowed: none minimal minimalWithDialogs

 --optionfile <optionfile>                   Installation option file
                                             Default: 

 --debuglevel <debuglevel>                   Debug information level of verbosity
                                             Default: 2
                                             Allowed: 0 1 2 3 4

 --mode <mode>                               Installation mode
                                             Default: qt
                                             Allowed: qt win32 unattended

 --debugtrace <debugtrace>                   Debug filename
                                             Default: 

 --enable-components <enable-components>     Comma-separated list of components
                                             Default: server,pgAdmin,stackbuilder,commandlinetools
                                             Allowed: server pgAdmin stackbuilder commandlinetools

 --disable-components <disable-components>   Comma-separated list of components
                                             Default: 
                                             Allowed: server pgAdmin stackbuilder commandlinetools

 --installer-language <installer-language>   Language selection
                                             Default: en
                                             Allowed: en es fr

 --extract-only <extract-only>               
                                             Default: 0

 --superaccount <superaccount>               Sets the user name of the database superuser. Defaults to 'postgres'.
                                             Default: postgres

 --servicename <servicename>                 Sets the name of the database service.
                                             Default: 

 --serviceaccount <serviceaccount>           Sets the operating system user account that owns the server process. Defaults to 'postgres'.
                                             Default: 

 --servicepassword <servicepassword>         Sets the password for the operating system user account that owns server process. Defaults to superuser password.
                                             Default: 

 --install_runtimes <install_runtimes>       Specifies whether or not install the Microsoft Visual C++ runtimes before the installation proceeds.
                                             Default: 1

 --enable_acledit <enable_acledit>           Check and give the read permissions on the complete data directory path for the service account.
                                             Default: 0

 --create_shortcuts <create_shortcuts>       Specifies whether or not menu shortcuts should be created.
                                             Default: 1

 --prefix <prefix>                           Installation Directory
                                             Default: C:\Program Files\PostgreSQL\15

 --datadir <datadir>                         Data Directory
                                             Default: C:\Program Files\PostgreSQL\15\data

 --superpassword <superpassword>             Password
                                             Default: 

 --serverport <serverport>                   Port
                                             Default: 5432

 --locale <locale>                           Locale
                                             Default:
```
