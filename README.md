# expense-tracking
### (WIP!)

#### Design
* This web app will be used to capture expense data entered manually to send to a Google Sheet.
* The web app requests authentication.
* Data sent to the Google sheet must be sent securely and without exposing any API secret key

#### Languages / Skills applied:
* HTML
* JS
* Python / Flask
Expenses can be of 2 different types: Standard or Extraordinary
Standard expenses require a Category, otherwise, the input is rejected
Extraordinary expenses don't require a Category. In fact, when an expense is marked "Extraordinary", the Category selection
dropdown is hidden. For Extraordinary expenses, the value entered into "Description" is written into the Google Sheet in the
same column to which Standard expenses Category is saved.

* MYSQL
The app combines the usage of an SQLite database to securely store user authentication credentials and category names,
while writing data to a Google Sheet via API.
* OAuth
Using Google Sheets fulfils the need for an easily accessible database, but also requires the use of oAuth to make changes to the sheet.
* Google Cloud App Engine
The service is hosted in Google Cloud App Engine



#### Description:



