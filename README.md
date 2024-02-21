## Overview

- Realtime Stock Tracker is a web application for users to track stock details in real-time.
  
## Features

- WebSockets Integration: Realtime stock data is received and displayed on the client-side using JavaScript, enabling live updates for users.
- Dynamic Stock Addition: Users can dynamically add stocks in the arguments field of Celery Beat periodic tasks, allowing for flexible task scheduling based on user preferences.
- Data Filtering: User-specific stock details are filtered and sent to clients, ensuring that users only receive data relevant to their selected stocks.
- Automatic Stock Removal: Stocks selected by users are automatically removed as soon as the user disconnects or closes the web application, preventing unnecessary 3rd Party API Calls and reducing overhead.
- Dark Mode Support: Dark mode is implemented, providing users with a visually appealing and customizable interface.
  
## Technologies

- Frontend: HTML, CSS, JavaScript
- Backend: Python (Django framework)
- WebSockets: Django Channels
- Task Scheduling: Celery Beat
- Database: Redis

## Screenshots
<img width="1507" alt="Screenshot 2024-02-21 at 16 53 39" src="https://github.com/aliciachoi/RealtimeStockTracker/assets/125190356/0ac52749-a7d1-4bc9-ab46-1630206889ef">
<img width="1508" alt="Screenshot 2024-02-21 at 16 56 29" src="https://github.com/aliciachoi/RealtimeStockTracker/assets/125190356/e5876967-5acf-49e1-b742-52f2ad37a059">
<img width="1499" alt="Screenshot 2024-02-21 at 16 56 17" src="https://github.com/aliciachoi/RealtimeStockTracker/assets/125190356/f523d6a9-7d54-4bda-b082-71f709b60d4a">





