# Setup Instructions

1. Clone the repository:
   ```sh
   git clone https://github.com/Iam-Tech02/graphql-mongo.git
   cd graphql-mongo
   ```
2. Install dependencies:
   ```sh
   npm install  # or use yarn
   ```
3. Set up environment variables in a `.env` file:
   ```sh
   MONGO_URI=mongodb://localhost:27017/your_database
   PORT=4000
   ```
   **Note:** Use MongoDB on localhost and not Atlas, as certain functions require a top-tier Atlas plan.
4. Seed the database:
   - A CSV file is provided in the test task and can also be found in the `seed` folder.
   - Use MongoDB Compass to import the CSV file and seed the data into the database.
5. Start the server:
   ```sh
   npm run dev  # or use yarn dev
   ```
6. Access GraphQL Playground at:
   ```
   http://localhost:4000/graphql
   ```

