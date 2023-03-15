# OpenAI API Summarize Your Text

This is an example of an application that receives a text and summarizes it, the example available in the OpenAI API [quick start tutorial](https://platform.openai.com/docs/quickstart) was used as a basis. It uses the framework [Next.js](https://nextjs.org/) with [React](https://reactjs.org/). Check out the tutorial or follow the instructions below to get set up.


## Setup

1. If you don’t have Node.js installed, [install it from here](https://nodejs.org/en/) (Node.js version >= 14.6.0 required)

2. Clone this repository

3. Navigate into the project directory

   ```bash
   $ cd openai-summarize-your-text
   ```

4. Install the requirements

   ```bash
   $ npm install
   ```

5. Make a copy of the example environment variables file

   On Linux systems: 
   ```bash
   $ cp .env.example .env
   ```
   On Windows:
   ```powershell
   $ copy .env.example .env
   ```
6. Add your [API key](https://platform.openai.com/account/api-keys) to the newly created `.env` file

7. Run the app

   ```bash
   $ npm run dev
   ```

You should now be able to access the app at [http://localhost:3000](http://localhost:3000)! For the full context behind this example app, check out the [tutorial](https://platform.openai.com/docs/quickstart).
