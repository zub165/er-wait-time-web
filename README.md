# ER Wait Time

A modern web application that shows emergency room wait times and allows patient registration. Built with HTML, CSS, and JavaScript using the Google Maps API.

## Features
- Search for nearby emergency rooms
- View estimated wait times
- Patient registration system
- Distance calculation
- Responsive design
- Secure data storage

## Setup
1. Clone the repository
2. Create a `config.js` file:
   ```javascript
   const config = {
       GITHUB_TOKEN: '', // Add your GitHub token
       REPO_OWNER: 'zub165',
       REPO_NAME: 'er-wait-time'
   };
   ```
3. Get a GitHub token with repo scope
4. Get a Google Maps API key
5. Update the tokens in your files
6. Open index.html

## Security
- Keep tokens private
- Never commit config.js
- Use HTTPS
- Regular token rotation

## Login
- Username: admin
- Password: ertime911

## Data Storage

The application stores data in `data.json` using GitHub's API. The file contains:
- Patient registration records
- Hospital wait times
- System configuration

## Security Note

The application uses GitHub for data storage. Make sure to:
- Keep the GitHub token secure
- Never commit the token to the repository
- Regularly rotate the token
- Monitor repository access

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Google Maps API
- Google Places API

## API Usage

The application uses:
- GitHub API for data storage
- Google Maps API for location services
- Places API for hospital data 