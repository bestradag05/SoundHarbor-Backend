# SoundHarbor-Backend

Welcome to the SoundHarbor backend repository! Here you'll find the necessary steps to install and run the project in your local environment.

## Installation Steps

1. **Clone the project:**

   ```bash
   git clone https://github.com/bestradag05/SoundHarbor-Backend

2. **Enter the project folder:**

   ```bash
   cd SoundHarbor-Backend

3. **Install dependencies:**

   ```bash
   npm install

4. **Optional: Install nodemon to make it easier to run the server:**

   ```bash
   npm install -g nodemon
   ```
   you can run using nodemos or using node.

5. **Create .env file:**

     Database variables:  
            DB_HOST= # db host   
            DB_USER= # db user   
            DB_PASSWORD= # db password   
            DB_DATABASE= # database name   

      Mailtrap Settings:  
            EMAIL_USER= # mailtrap user  
            EMAIL_PASS= # mailtrap password   
            EMAIL_HOST= # mailtrap host   
            EMAIL_PORT= # mailtrap port   

      Frontend URL:  
            FRONTEND_URL= # frontend url

6. **Import the database:**
      You must import the database

7. **Run the server in development mode:**

```bash
npm run dev
```
Ready! Now your SoundHarbor server is up and running in your local environment. If you have any questions or problems, feel free to open an issue in the repository. Enjoy developing with SoundHarbor!
