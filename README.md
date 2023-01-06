# 🖳 Programming Challenge >>

Please create a basic vue-powered project that uses the [Rick and Morty API](https://rickandmortyapi.com/) for backend to create 3 pages and add a side bar for navigation between them

1. **A page that fetches a list of characters** from Rick and Morty API
   - display the data as a table with the following columns: `name`, `species`, `status`, `gender`, `origin.name`
   - add pagination to the table of 20 records per page. (it's the built-in default page size for the API)
   - on mouseover of a row, the character's name and picture appear in a popup.
   - add a filter to the table by `status` (`alive`, `dead` or `unknown`) and by `gender` (`female`, `male`, `genderless` or `unknown`). Please use 2 dropdowns to implement these filters.
   - add a search by character's name
   - both of the filters and the name search should work together. (ie, we want to be able to both search for something and then filter by status, or use both flters simultaneously, etc)

2. **A page that fetches a list of locations** from the API
   - sort the list by location title
   - location titles are clickable and open a modal popup
     - the popup contains the location's `name`, `type`, `dimension` at the top
     - a table of characters from this location that behaves exactly like the List of Characters from #1
   - location list can be filtered (searched) using a text input by `type`

3. **A page that fetches a list of episodes** from the API. This page should function similarly to the list of locations page:
   - sort the list by episode number (default sorting)
   - Episode names are clickable and open a modal popup
     - the popup contains the episode's `name`, and `air_date` at the top
     - a table of characters from this episode that behaves exactly like the List of Characters from #1

Commit the project to a github repo and share with us. Thanks!

### ★★ Extra Credit Challenge ★★
Compile and deploy the project to a [github pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) site 👍

You are free to approach the challenge in any way you like and use any stack/dependencies you like or are familiar with, such as
* bootstrap
* vue-router
* vuetify
* webpack
* nuxt
* axios
* fontawesome
* materialdesign
