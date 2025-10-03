# CodeCraftHub

- Install Dependencies
<pre>
npm install
</pre>

- Start the Node.js Server
<pre>
node src/app.js
</pre>

- Curl to register a user
<pre>
curl -X POST -H "Content-Type: application/json" -d '{"username": "john_smith", "email": "johnsmith@example.com", "password": "password123!"}' http://localhost:5000/users/register
</pre>

- Curl for user login
<pre>
curl -X POST -H "Content-Type: application/json" -d '{"email": "johnsmith@example.com", "password": "Password123!"}' http://localhost:5000/users/login
</pre>

- Build the Docker Images
<pre>
docker-compose build
</pre>

- Run the Docker Containers
<pre>
docker-compose up
</pre>

- Access the Application
<pre>
http://localhost:5000
</pre>

- Stop the Docker Containers
<pre>
docker-compose down
</pre>
