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

## Team

Pihu — 1024031014, Jayant Kaushik — 1024031016, Aashna — 1024031018.

## Reports and presentation

- [Project proposal](https://github.com/pihuuaneja/ucs503p-202627campuspool/blob/master/project-proposal/main.pdf)
- [Prototype report](https://github.com/pihuuaneja/ucs503p-202627campuspool/blob/master/project-report-prototype-stage/main.pdf)
- [Final report](https://github.com/pihuuaneja/ucs503p-202627campuspool/blob/master/project-report-final/main.pdf)
- [Final presentation](https://github.com/pihuuaneja/ucs503p-202627campuspool/blob/master/presentation/CampusPool_Final_Presentation.pptx)

## Weekly journals

- [Pihu](journals/1024031014-pihu/index.md)
- [Jayant](journals/1024031016-jayant/index.md)
- [Aashna](journals/1024031018-aashna/index.md)
