# Event Driven Architecture

## Discuss 2 possible project ideas that could be completed by you and a partner in the alloted time

## **Event Notification System:**

* **Description:** Build a system for sending event notifications to subscribers. Clients can subscribe to specific events, and the hub server delivers event updates in real time.
* **Features:** Event subscription, real-time notifications, event categories, user preferences.
* **Optional:** Use an external API for event data and employ a queue system for reliable message delivery.

## **Real-Time Task Management Application:**

* **Description:** Create a real-time task management application where clients can perform actions such as creating, updating, and deleting tasks. The central hub server manages task data and broadcasts updates to all connected clients, ensuring that everyone is in sync.
* **Features:** Task creation, modification, and deletion by clients. Real-time updates of task lists for all connected clients.
Collaborative task management with multiple users.
* **Optional:** Employ an external API that uses a database for storing and retrieving task information. Implement a message queue to ensure reliable event delivery. Use a FIFO queue to maintain the ordered delivery of specific events.
