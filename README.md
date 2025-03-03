# Document Review System

## Description
This system allows users to submit documents for review, track versions, and interact with admins for approval or rejection. Admins can review changes and approve or reject documents. Notifications are sent in real-time via WebSockets.

## Features
- Document submission and review workflow
- Version history tracking
- Admin approval/rejection
- Real-time notifications via WebSockets
- JWT-based authentication
- Flexible content storage (PostgreSQL, file system, cloud)

## Technologies
- Backend: NestJS, PostgreSQL
- Frontend: React, Tailwind CSS
- Authentication: JWT
- Notifications: WebSockets
- Content Storage: Abstract service layer with interchangeable storage methods

## License
MIT
