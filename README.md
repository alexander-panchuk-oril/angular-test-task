# ✅ [Angular Test Task] To-Do App 

Dear Candidate, 

We've prepared a simple test task for you where you can show all your knowledge and skills in the Angular area. Feel free to improvise and don't be afraid of challenges 👀. We all believe that you are full of 📚 knowledge and 💪 motivation.

Respectfully, ORIL team.

P.S. If you have any questions 🤔 or just want to chat 💬, please email me at [alexander.panchuk@oril.co](alexander.panchuk@oril.co).

P.S.S. I bet that you could do it with your eyes shut and there is literally nothing that could stop you.

## 📃 Task

Your goal for the task is to show us as much as you know about Angular and Front-End development. The app should be not overcomplicated and you have to remember it's not 🚀 rocket science, so do not overcomplicate everything.

Our (ORIL) goal for the task is to see how deeply you understand the technology and figure out how you find solutions in different situations.

For the test task, you have to create your own GitHub repository.

**DEADLINE: 3 days**

### 💫 Designs
For the task, we've prepared UI designs for all pages and elements that must be implemented. You can check all designs at the link below.

**[UI Designs in Figma](https://www.figma.com/file/2aW9zuuiZwqRoLRT0OH8Yz/ORIL-Test-Task?node-id=7%3A338)**

### 👀 Technical specification
1. Create a user sign-up form using reactive forms with email and phone validation.

**Sign Up model:**
``` JSON
  name: "",
  username: "",
  email: "",
  phone: "",
  address: {
      street: "",
      suite: "",
      city: "",
      zipcode: ""
  }
```
API endpoint: **[POST]** `https://jsonplaceholder.typicode.com/users`. 

2. After the user was created, redirect to the todos page.

3. To-do List (get all, add, update, remove). 

**To-Do model:**
```JSON
  userId: 0
  title: ""
  completed: ""
```
#### 🔧 ToDo API endpoints:

ToDo-s List API endpoint: **[GET]** `https://jsonplaceholder.typicode.com/todos`. 

Add a ToDo API endpoint: **[POST]** `https://jsonplaceholder.typicode.com/todos`.

> NOTE: After adding new todo via API it wont be added to the ToDo-s list, your goal is to handle API response and push the ToDo locally into your ToDo-s list

Update a ToDo API endpoint: **[PUT]** `https://jsonplaceholder.typicode.com/todos/${id}`

Remove a ToDo API endpoint: **[DELETE]** `https://jsonplaceholder.typicode.com/todos/${id}`.

> NOTE: Take notice that after updating or removing a newly create ToDo, server API would throw an error. Please handle that error and make changes locally

4. New todo should appear at the top of the list.

5. User must confirm removing.

## 🏁 Finishing the task

After everything is done, please commit and send a link to your GitHub repository to HR.

## 📑 Contributing
If you notice any mistake or have an idea of improving the test task, please feel free to contact [alexander.panchuk@oril.co](alexander.panchuk@oril.co) for an immediate response 🙌.