# REAL-TIME-CHAT-APPLICATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ABHINAV SINGH

*INTERN ID*: CT06DK524

*DOMAIN*: Frontend Web Development

*DURATION*: 6 weeks

*MENTOR*: Neela Santhosh Kumar

*DESCRIPTION OF THIS TASK*: In this project, I built a real-time chat application where users can send and receive messages instantly, just like in apps such as WhatsApp or Messenger. The main goal was to create a system where messages appear in real-time without refreshing the page. To achieve this, I used React for the frontend, which is responsible for displaying the chat interface, and Node.js with Socket.IO for the backend, which handles sending and receiving messages between users. On the frontend, I created a simple chat interface that includes a text input field for typing messages, a button to send them, and a chat box that displays all messages. I used React’s useState to manage the current message and the list of all chat messages, and useEffect to listen for new incoming messages from the server. I used the Socket.IO client library to open a WebSocket connection to the backend server running on localhost:5000. When a user types a message and clicks send, the app sends that message to the server using socket.emit. On the backend, I created a server using Node.js and Express, and added Socket.IO to handle real-time communication. When the server receives a message from a client, it uses io.emit to broadcast that message to all connected clients, including the one who sent it. This means everyone in the chat sees the new message instantly. I also made sure the server handles multiple users connecting and disconnecting, although this version keeps things simple without usernames or chat rooms. For styling, I used basic CSS to make the chat box neat and readable, with scrolling enabled so that users can view past messages. One of the important things I learned during this project was how WebSockets enable live communication over the internet, unlike traditional methods where you have to refresh the page or keep checking for updates. By using Socket.IO, I didn’t have to deal with the complexities of raw WebSocket code — it handled most of the hard work behind the scenes. This project helped me understand how frontend and backend systems can work together to create a smooth, interactive experience. Overall, I successfully built a functional real-time chat app that shows how messages can be sent and received instantly, making it a great example of full-stack development and the power of modern web technologies.

*OUTPUT*: 
