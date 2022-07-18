# bearer-auth

## Project Description

Assignment Buster is a Slack App that helps students stay up-to-date with their coursework. Students are able to quickly access their Canvas assignments from the Assignment Buster App.

## Deployments

[Production](https://gudt-bearer-auth.herokuapp.com)

## Author

- Dylan Ullrich

### Setup

#### .env Requirements

- `PORT=3001`
- `SECRET=TEST_SECRET`

#### Run

- Use `nodemon`

#### Features and Routes

- POST - `/signup`
- POST - `/signin`
- GET - `/users`
- GET - `/secret`

## Tests

- Jest Tests implemented.
- To test: Run `npm test`
