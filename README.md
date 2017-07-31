# Walr.us - A Resource Wall for People like us

<p align="center"><img src="https://user-images.githubusercontent.com/25350697/28794152-5615599c-7603-11e7-8c47-1b273ea212c0.gif"/></p>

## Getting Started
1. Clone this repo
2. Create the `.env` file by using `.env.example` as a reference: `cp .env.example .env`
3. Update the .env file with your correct local information
4. Install dependencies: `npm i`
5. Fix to binaries for sass: `npm rebuild node-sass`
6. Run migrations: `npm run knex migrate:latest`
  - Check the migrations folder to see what gets created in the DB
7. Run the seed: `npm run knex seed:run`
  - Check the seeds file to see what gets seeded in the DB
8. Run the server: `npm run local`
9. Visit `http://localhost:8080/`
