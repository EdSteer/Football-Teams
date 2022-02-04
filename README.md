# SEI-Project-2

![Football_Teams](https://user-images.githubusercontent.com/91135210/152515108-d7e24b10-4a32-44e1-9044-1c223a1b3123.png)

A pair coded React app 

Deployed here - [footballteams.netlify.app](https://footballteams.netlify.app/)

Project 2: Football Teams

This is the second project from my SEI course. It’s a 48 hour pair coded app where my partner [Lee Wiseman](https://github.com/leewiseman94) and I created a site where users can view all teams from the Premier League down to the 7th tier of the English football “pyramid”.

Utilising React and an external API (www.thesportsdb.com), the app allows users to search by team name and league as well as showing recent fixture results, kits, club badge, stadium and fan created content.

**Requirements**

- Create an app using a 3rd party API.
- Must have multiple components, a router and several pages.
- 48 hours to complete.
- Should use JavaScript, React and HTML/CSS.
 
**Technologies Used**
 
- React.js
- Axios
- Bulma
- CSS
- HTML
- JavaScript
- React Router Dom
- Insomnia
- Netlify
 
**Planning**

As this project had a 48 hour deadline, Lee and I knew that we would have to get the planning stage done as quickly as possible to give ourselves enough time to implement the requirements of the brief. We wanted to find something that interested us both and would be of interest to others. We went with football and immediately started searching for an API. 

We found www.thesportsdb.com. The API had a lot of data so we spent some time deciding exactly what we’d like to see on the app. We then set about wireframing the app and from there decided on what components we would need.

**Process**

Once we’d decided on what data we wanted to show and how we’d like to present that data, we began pair coding to build the site, taking it in turns to code.  

Firstly, we needed to ensure we could see the teams and leagues that we wanted to show on our teams page. We used GET requests in Insomnia to do this. Then we were able to start creating the various component files for the app.

Aside from a little animation to drop the “kick off” button onto the page, we kept our homepage very simple. Once the user enters the site, they arrive at the teams page.

![Screenshot 2022-02-04 at 11 07 14](https://user-images.githubusercontent.com/91135210/152518899-68617148-48ea-4a2a-b7ef-7675f4bb9392.png)
 
The teams page shows all of the teams within the English football pyramid arranged in “cards” that we created using Bulma. 

Using a GET request in Axios we pulled the data we wanted to show on each card and mapped this data. Each card then links to an individual team page where we add extra data.

![Screenshot 2022-02-04 at 11 11 23](https://user-images.githubusercontent.com/91135210/152519423-ab85569d-4cc7-434c-95ba-565de543d513.png)

![Screenshot 2022-02-04 at 11 09 06](https://user-images.githubusercontent.com/91135210/152519169-6935ce07-719a-4645-86a8-8ec459f1cf4c.png)

![Screenshot 2022-02-04 at 11 13 44](https://user-images.githubusercontent.com/91135210/152519722-672683ee-7c24-403f-979b-0efda66ea0ea.png)

We also included a search bar and dropdown filter menu as well as some error handling.

![Screenshot 2022-02-04 at 11 15 21](https://user-images.githubusercontent.com/91135210/152519895-f3c70c79-88fa-4950-a20d-5fdbd5b7eded.png)

The individual team page shows further team details including team shirt upcoming and recent fixtures and “fan created content”. Again, we used Axios to pull that data from the API.

![Screenshot 2022-02-04 at 11 18 19](https://user-images.githubusercontent.com/91135210/152520309-07925447-c89a-42e2-a790-6d3485b05185.png)

![Screenshot 2022-02-04 at 11 19 04](https://user-images.githubusercontent.com/91135210/152520393-f23f6309-e3e6-4318-b42a-3d4211a9b24f.png)

It was also important to add some error handling to allow users to view error messages.

![Screenshot 2022-02-04 at 11 21 28](https://user-images.githubusercontent.com/91135210/152520693-45fec9e6-29bd-4256-9de6-3f0479131ddb.png)
 
**Wins and Challenges**

I Think the main challenges with this project were the time limitation and finding an API that could give us the data we wanted for free. Once we’d got that we were able to use Bulma as our CSS Framework and that too was tricky in so far that it was new to us. 

Like project one, it was a steep learning curve! I think overall, the app functions really well and looks great. My main win would be working collaboratively. I felt it was good coding as a pair and it was great to see the stuff we’d learnt in class coming to life in a practical setting.

**Key Learnings**

- Working as a pair and learning best practice for pair coding.

- Bulma. This was my introduction to using frameworks and Bulma worked well in this case. We kept pretty much within the confines of the framework for   this app. 

- Insomnia. This app build was a great intro to Insomnia and APIs and how to utilise that plethora of data available.

- React. Gaining an understanding of how React works and how React sites/apps are created has proved essential.
