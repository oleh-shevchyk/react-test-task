# ⚛️ React.js test task

Dear Candidate,

We've prepared a simple test task for you where you can show all your knowledge and skills in the React.js area. Feel free to improvise and don't be afraid of challenges 👀. We all believe that you are full of 📚 knowledge and 💪 motivation.

Respectfully, ORIL team.

## 📃 Task

Your goal for the task is to show us as much as you know about JavaScript React.js and Front-End development. The app should be not overcomplicated, and you have to remember it's not 🚀 rocket science, so do not overcomplicate everything.

Our (ORIL) goal for the task is to see how deeply you understand the technology and figure out how you find solutions in different situations.

The task will be to create a web application that provides Revenue analysis.

The application contains two pages:

### List page

Tasks:

1. Create a table with a list of items. It must contain such columns:
    * *name*
    * *date*
    * *state*
2. Provide the ability to sort by *date* and *state*
3. Provide search by *name*
4. On click on certain item redirect User to the **Item page** with chart

### Item page

Tasks:

1. Show chart that contains all data from the received object
    * *x-axis*: date
    * *y-axis*: revenue amount
2. Show chart for the week (current, last 7 days)
3. Show chart for the month (current, last 30 days)
4. Show chart for the year (current, 2021)

*P.S.* Data in the object is not sorted. You need to sort them so that the full срфке displays data from the oldest date to the farthest

*P.P.S* You can use any convenient library to build charts


🕒 **DEADLINE: 3-5 days**


## 🪧 Design

For the task, we've prepared UI designs for all pages and elements that must be implemented. You can check all designs at the link below.

[UI Designs in Figma](https://www.figma.com/file/unTbdQqa6n6LVfkCzaNORu/Untitled?node-id=0%3A1)

## 🛠️ API for retrieving data

You can get all needed data by sending requests to this link https://oril-coins-test.herokuapp.com

Available requests:

`GET/ https://oril-coins-test.herokuapp.com/list` -- returns JSON with all *list* records

`GET/ https://oril-coins-test.herokuapp.com/item/{item_id}` -- returns JSON with data for certain item

## 🏁 Finishing the task

After everything is done, please commit and send a link to your GitHub repository to HR.

## 📑 Contributing
If you notice any mistake, or you have some problems with accessing the design or API link, please feel free to contact oleh.shevchyk@oril.co for an immediate response 🙌.
