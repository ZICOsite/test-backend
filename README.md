## Features

- **Simulated Delay**: Backend request processing includes a 5-second delay.
- **Error Handling**: Returns a message if no users match the search criteria.

## Tech Stack

- **Backend**: Nest.js (TypeScript mandatory)

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd test-backend
   ```

2. **Install**

   ```bash
   cd test-backend
   npm install
   ```

3. **Run the backend server**

   ```bash
   npm run start
   ```

4. **Backend Endpoints**

   ```bash
   GET /search: Search for users by email and optionally by number.
     Query Parameters:
       email (string, required)
       number (string, optional)
   ```

5. **Example Request**

   ```bash
   curl 'http://localhost:3000/search?email=jim@gmail.com&number=221122'
   ```
