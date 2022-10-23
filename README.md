# Database for AutoDeck

> This database was hosted with the help of a template shared from:
> https://github.com/jesperorb/json-server-heroku

### [Database Link](https://autodeck-database.herokuapp.com/driverDetails)


# How to insert Elements ?

1. Clone the repository using :  `git clone git@github.com:Takashi069/autodeck-database.git`
   
2. Enter into the cloned repository
    1. Now edit `db.json`
        - Make sure you follow the correct format of a JSON file
         ```json
            {
                "driverDetails":[
                  {
                    "id" : 0,
                    "name": "",
                    "phoneNumber" : "+91 0000000000",
                    "Number Plate": "KL __ X ____",
                    "Rate": [],
                    "MaxCap": 4
                  },
                  {
                    "id" : 1,
                    "name": "",
                    "phoneNumber" : "+91 0000000000",
                    "Number Plate": "KL __ X ____",
                    "Rate": [],
                    "MaxCap": 4
                  }
                ]
              }
         ```
    2. After inserting or removing the necessary elements, **commit** your changes using the command : `git commit -am "Commit Message"`
    3. ***[This is optional but recommended]*** Pull the repository ( using the command `git pull origin master` or `git pull` ) so as to ensure that your local repo is up-to-date.
    4. Finally, **push** your changes to the repository using the command `git push origin master` or `git push`

> Remember: You can only push changes if you are a contributor. Else, forking the repo and creating a pull request will be your alternative.

>:warning: **Do not** change the name of the database or any of the name of the fields. Only change the relevant data.

> Whenever a change is pushed into this repo, the database is updated automatically within 5-10 mins. So do not expect your changes to be reflected immediately. 

