# CampusPool

CampusPool helps members of the Thapar community coordinate shared rides and find company for campus activities. This is a UCS503 Software Engineering project at TIET.

## How it works

1. Sign in with a one-time code sent to a Thapar email address.
2. Post a ride or activity, or request to join an existing one.
3. Once connected, use chat to coordinate. For completed rides, the app records each rider's share of the actual fare and lets the ride creator confirm payment.

## Implementation

The Next.js frontend calls a FastAPI backend backed by PostgreSQL. WebSockets deliver live updates, and the browser encrypts one-to-one chat messages before sending them.

- [Source code and local setup](https://github.com/pihuuaneja/ucs503p-202627campuspool/tree/master/code)
- [Render deployment guide](https://github.com/pihuuaneja/ucs503p-202627campuspool/blob/master/code/DEPLOY_FREE.md)
- [Project repository and course deliverables](https://github.com/pihuuaneja/ucs503p-202627campuspool)
