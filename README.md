# Open-Emission-Factors-DB
Welcome to the Open Emission Factors Database (OEFDB) on github. This is the home of an open access database of emission factors, designed to be constantly updated by contributors across the spectrum of sustainability researchers and professionals. It is freely available to all (see sharealike license in this repository), and maintained and validated by the team at https://climatiq.io.

Our ambition is for this to be the world's most granular, accurate and up-to-date emission factor database, for all to use in their efforts to drive action on the climate crisis.

Along with the database, Climatiq also provides a free REST API to allow anyone to query the data as needed. It will update weekly to reflect the contents of the OEFDB and is cached globally to provide extremely low latency and processing time (not to mention emissions!)

For more detail on the API see here: https://docs.climatiq.io/ (also currently the best place to get more detail about the OEFDB).
 
We will be providing some best practice guidelines to using GitHub for data management in the near future - in the meantime if you have any questions, please get in touch on github and we will gladly help!

## How to contribute

Thank you for thinking about contributing to the Open Emission Factors Database! To contribute by creating or updating factors in the database, follow these steps:

### 1. Edit the file
1. Download a copy of this repository.
2. Open `OpenEmissionFactorsDB.csv` file with a CSV editor. You can work with any editor like Microsoft Office or Apple Numbers but keep an eye on the characters encoding and make sure that they are all displayed well.

![Download button](./img/download.png)

3. Make the changes to the file. Try to keep them as short as possible and do not try to addnew factors along with other factors updates. Try to do both in separate requests.
4. Save or export the file as a `.csv` file separated by commas.
5. Open the `csv` file with a text editor (Right-click on the file > Open With... > TextEdit in Mac or Notepad in Windows).
6. Copy the content of the file.
7. Back to GitHub, click on `OpenEmissionFactorsDB.csv` file and then in the edit icon.
8. Paste the content in the text area.

![Edit icon](./img/edit.png)

### 2. Create a Pull Request

Now that you have edit your changes, you need to create a Pull Request so the changes can be reviewed before going live:

1. Commit the changes by completing the form. Give it a proper title and specify if you are adding or updating an existing factor and the category it belongs to. Additionally, insert a description with any extra data to speed up the revision process and give the branch a name that can be identified easily
   
![Commiting changes](./img/commit.png)

2. Immediately after, you will be redirected to another screen to create a new Pull Request. If the title and descriptions are fine for you, click on `Create Pull Request` and wait for approval or changes requests.

![Pull Request creation](./img/pull-request.png)

