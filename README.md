# Crowdfunding Back End
{{ your name here }}

## Planning:
### Concept/Name
{{ Include a short description of your website concept here. }}

### Intended Audience/User Stories
{{ Who are your intended audience? How will they use the website? }}

### Front End Pages/Functionality
- Home Page
    - Featured kickstarters
- Search Page
  - Search specific fundraiser
- Create New Fundraiser Page
    - Form with fundraiser details
    - Ability to submit
    - Nice error page for validation
- Display Fundraiser
    - Shows all information about fundraiser
    - Show all pledges made so far

### API Spec
{{ Fill out the table below to define your endpoints. An example of what this might look like is shown at the bottom of the page. 

It might look messy here in the PDF, but once it's rendered it looks very neat! 

It can be helpful to keep the markdown preview open in VS Code so that you can see what you're typing more easily. }}

| URL              | HTTP Method                        | Purpose | Request Body | Success Response Code | Authentication/Authorisation |
| ---------------- | ---------------------------------- | ------- | ------------ | --------------------- | ---------------------------- |
| /fundraisers/    | Fetch all the fundraisers          | GET     |  N/A         | 200                   | None                         |
| /fundraisers/    |                                    | POST    | JSON Payload | 201                   | Any logged in user           |
| /fundraisers/1/  |                                  |         |              |                       |                              |
| /pledges/        | Fetch all the pledges                | GET     |              | 200                   |                              |
| /pledges/        | Create a new pledge for a fundraiser | POST    | JSON Payload | 201                   | Any logged in user           |

### DB Schema
![]( {{ ./relative/path/to/your/schema/image.png }} )