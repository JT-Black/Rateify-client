# Rateify

## Project Overview
   _Rateify_ is a full stack MERN application (MongoDB, Express, React and Node). The site allows users to discover and rate music, post their own reviews about a release, and upload a release for others to comment on. The app also allows users to listen to samples of the posted music by listening to the release's associated Spotify playlist.  _Rateify_ was a week-long group project in which I worked with [Calum MacEachen](https://github.com/calum-m708) and [Omar Al-Sanea](https://github.com/omaralsanea) to create our finished site.

## The Brief
- Build a full-stack application by making a back-end and a front-end.
- Use an Express API to serve your data from a Mongo database.
- Consume your API with a separate front-end built with React. 
- Be a complete product with multiple relationships and CRUD functionality.
- Implement wireframes that show the user journey and functionality of the application.
- Be deployed online so it’s publicly accessible.

## Concept
   Our first discussions centred around the fact that we wanted to build something that would be useful to people and that was different to other applications that we had built before. We focused on music as it was an area that we were all interested in and decided to create a site that blended musical content with user interaction for music fans looking to share their favourite releases and opinions about the music and artists who created it.

## Application Walkthrough
### Home  Page
<p align="center">
  <img src="./src/img/home.png" width="96%"  />
</p>

### Artist Index
<p align="center">
	<img src="./src/img/artists.png" width="96%"  />
</p>

### Release Index
<p align="center">
	<img src="./src/img/releases.png" width="96%"  />
</p>

### Artist Page
<p align="center">
	<img src="./src/img/artist.png" width="96%"  />
</p>

### Release Page
<p align="center">
	<img src="./src/img/release.png" width="96%"  />
</p>

### Register
<p align="center">
	<img src="./src/img/register.png" width="96%"  />
</p>

### Login
<p align="center">
	<img src="./src/img/login.png" width="96%"  />
</p>

### About
<p align="center">
	<img src="./src/img/about.png" width="96%"  />
</p>


## Tech Stack
### Front End
- React Framework (Single Page Application)
- API Handling: Axios
- Pure CSS with Sass
- React-Router-Dom

### Back End
- Server: Node.js & Express
- Database: MongoDB & Mongoose
- Safeguarding from injection attacks: Express Mongo Sanitize
- Password Encryption: Bcrypt
- Authentication: JSON Web Token (JWT)

### Development
- Npm
- Git, GitHub
- Postman for API testing
- Excalidraw for wireframing
- Trello for setting tasks and tracking
- Zoom and VS Code Live Share for coding collaboration
- Deployment:
  - Front End: Netlify
  - Back End: Heroku & Mongo Atlas

We started by breaking the tasks down and putting them on a Trello board. While building, we spent most of the daytime lab hours taking turns 'driving' on VS Code with live share and mob-coding while on Zoom. In the evenings we tackled small tasks like collating links for pre-seeding our database, and styling components.

## Architecture:
### Front End: 
  - React Components using Hooks for state management and handling side effects
  - Bulma CSS framework for styling
  - Single Page Application (`react-router-dom`) using `Link`, `useNavigate`, `useLocation` and `useParams`
### Back End:
  - All security checks done in the back end:
    - Email validation
    - Password validation
  - Secure routing middleware
  - Error handling middleware
  - Interlinked schema models in MongoDB

## Featured Code Snippets
### Front End




### Back End



## Challenges and Wins
Adding releases currently requires using a spotify link. An unsolved issue we had was a better way to add releases that would validate in the back end, unfortunately, we ran out of time. We wanted to add an average star rating and reviews section as well, however the time constraint limited what we were able to add with our deadline. We were able to add carousels on the homepage for a win.

## Bugs
There is a bug that popped up after deployment. Registration stopped working. We hopefully will get it fixed.



