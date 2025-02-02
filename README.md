**Project Title: WebSocket Chat App using AWS Lambda**

**Project Description:**

**System Design:**

Built a WebSocket chat application leveraging AWS API Gateway to enable real-time messaging between users.
Configured WebSocket routes for handling connections ($connect), disconnections ($disconnect), and message delivery ($default).
Backend Development:
Developed and deployed AWS Lambda functions to manage WebSocket events:
connect.js: Handles new user connections and logs them.
disconnect.js: Manages disconnections and removes users from the active session list.
message.js: Processes incoming messages and broadcasts them to connected clients.
Frontend Development:
Created a simple, clean chat interface using HTML, CSS, and JavaScript.
Integrated WebSocket in the frontend to send and receive real-time messages to and from the backend.

**Testing and Validation:**

Verified the complete flow by connecting multiple clients and testing real-time communication.
Ensured that the Lambda functions worked as intended, handling connections, disconnections, and message broadcasting seamlessly.

**Skills Gained:**
Hands-on experience in setting up AWS API Gateway for WebSocket communication.
Practical knowledge in AWS Lambda for serverless backend logic.
Strengthened skills in real-time web communication and frontend integration.
Gained a deeper understanding of serverless architecture and how it enables scalable, event-driven applications.
