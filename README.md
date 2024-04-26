# webapp_base4all
This repository was used as the starting for all web application that develop by psuwan. Developed using PHP language based on MVC (none-OOP) framework
```
webapp_base4all's structure
├── README.md
├── public
    ├── index.php
    ├── ajaxfunc_4all.php
    └── bootstrap@5.3.3
        ├── css
        ├── js
└── apps
    ├── config
        ├── config.php (defined path of working)
    ├── data
    ├── model
    ├── lib
        ├── functions_4all.php
    └── view
```

```
functions_4all.php
contain all of basic functions must use with most of all projects.

function db_connected()
use to connect to MySQL data base using global constants and will return result if connected success then return error if connected failed.
```