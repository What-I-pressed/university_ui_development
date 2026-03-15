# ticketline static layout (lab 1)

this repository contains static html pages styled with scss for the ticketline booking service.

## pages

- `index.html` login
- `logout.html` logout confirmation
- `pages/users.html` users listing
- `pages/user-create.html` create user dialog
- `pages/user-details.html` selected user details
- `pages/user-edit.html` edit user
- `pages/user-delete.html` delete user
- `pages/errors.html` error notifications and validation errors
- `pages/events.html` events listing
- `pages/event-details.html` event details and seat map
- `pages/my-tickets.html` purchases, reservations, and cancel booking

## scss build

scss is compiled into `css/main.css`.

```bash
npm install
npm run build:css
```

for live updates:

```bash
npm run watch:css
```

## github pages

set the repository pages source to the `development` branch and the root folder. the site will be available at `username.github.io/repository` after the first push.
