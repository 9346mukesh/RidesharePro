# RidesharePro

RidesharePro is a GPS-based fleet tracking and monitoring system focused on:

- Real-time vehicle location tracking
- Driver behavior monitoring for safety improvements
- Admin visibility across all active drivers
- Better taxi dispatch and route optimization
- Attendance tracking to support payroll workflows

## Roles

### Driver
- Logs in with user ID and password
- Shares live GPS location to the backend

### Admin
- Logs in with admin ID and password
- Views live locations of all drivers
- Identifies which driver is at which location
- Uses location visibility for taxi allocation and operational decisions
- Maintains driver attendance records for salary calculation

## Core Requirements

1. Track vehicle/driver location in real time using GPS.
2. Send location updates from driver app to backend services.
3. Provide an admin dashboard to monitor all drivers and their locations.
4. Support safety and anti-cheating oversight through continuous tracking.
5. Improve logistics productivity for businesses operating multiple vehicles.

## Tech Stack

- **Admin dashboard:** React.js
- **Driver/Customer app:** React Native (customer features planned)
- **Backend:** Python (FastAPI), WebSockets
- **Database:** MongoDB Atlas
- **Maps/Geo:** OpenStreetMap
