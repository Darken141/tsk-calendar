# Front-end assignment (calendar)

## Assignment

The client is a layer for whom we are developing a web solution to handle online bookings. Our colleagues prepared back-end server and front-end apps. Your task is to create a user interface where these bookings can be displayed. Imagine Google calendar but with a few more adjustments.

The Skeleton of our calendar is in the `calendar.json ` file. We want to split our calendar into individual weeks.

```json
{
    ...
	"startTimes": ["08/00", "08/00", "08/00", "08/00", "08/00", "X", "X"],
	"endTimes": ["18/00", "18/00", "20/30", "20/30", "20/00", "X", "X"]
    ...
}
```

Each day has a different start time and end time, which means we need to hide or any other way disable blocks we do not need.

```json
{
    ...
	"interval": 15
    ...
}
```

Interval is the number of minutes for each block. In this scenario, we can book an appointment on `xx:00, xx:15, xx:30, xx:45` that creates `96 blocks` in each day column

## Tasks

- Clone this repository
- Create calendar UI
- Display JSON data in the UI

## Bonus tasks

- Implement a basic login form for authentication so only logged users can see the calendar
- implement another CRUD functionality
- disable blocks depend on calendar lunch and break time
- use GitHub pages to make your app live
- Mobile responsiveness

## Recommended tools

- React - front-end framework
- moment.js - npm package for better working with date objects in javascript
- styled-components - npm package for styling react components
- framer-motion - npm package for animations
