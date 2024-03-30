# Lavender Notes App

To run the project locally, follow the steps below:

- **Clone this repository:**
  ```sh
  git clone https://github.com/KabirCampwala/lavender-notes-app
  ```

- **Setup a MongoDB Database:**
  - Either set it up locally or use a cluster.
  - The local URI will be `localhost:27017`.

- **Setup Local Environment:**
  - Create a `.env` file at the root directory.
    ```
    MONGO_URI='<YOUR_MONGO_URI>'
    PORT=<YOUR_SERVER_PORT>
    ```

- **Install all the dependencies:**
  ```sh
  npm i
  ```

- **Start the Server:**
  ```sh
  npm start
  ```
