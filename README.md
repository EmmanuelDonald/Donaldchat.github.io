# Video Chat Application
* Deployed at https://https://dev-94420434.okta.com/
* Only two persons can join in one room
## Running the app on development server
* `npm install`
* `node index.js`
* open `localhost:8000`

## Obtaining TURN/STUN credentials using okta
* Do not use the credentials provided
* Go to https://https://dev-94420434.okta.com/
* Sign Up 
* Log in to your account
* Click on `+` beside `Donaldchat`
* Click on `login TURN Credentials` Button located below `Sign in`.
* Accept the warning by click on `+` that appears just after you clicked on `login TURN Credentials`.
* Copy the text(begins with `iceservers`) that appears below `static TURN Credentials`  and paste in `config.js` as shown in `config.js`.