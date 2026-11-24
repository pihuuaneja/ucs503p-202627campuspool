# CampusPool

CampusPool is a UCS503P Software Engineering project at TIET Patiala. The website helps the campus community coordinate shared rides and find company for activities. Sign-in uses a one-time code sent to a Thapar email address.

- **Rides** — Publish and discover trips, request seats and receive organiser decisions.
- **Activities** — Find company for study, sports, meals and other campus plans.
- **Settlement** — Split the actual ride fare and track rider acknowledgement and organiser confirmation.
- **Communication** — Coordinate through chat and notifications.

## Team

| Member | Roll number |
|---|---|
| Pihu | 1024031014 |
| Jayant Kaushik | 1024031016 |
| Aashna | 1024031018 |

## Deliverables

- [Project proposal](project-proposal/main.pdf) and [LaTeX source](project-proposal/main.tex)
- [Prototype report](project-report-prototype-stage/main.pdf) and [LaTeX source](project-report-prototype-stage/main.tex)
- [Final report](project-report-final/main.pdf), [LaTeX source](project-report-final/main.tex) and [diagrams](project-report-final/figures/)
- [Final presentation](presentation/CampusPool_Final_Presentation.pptx)
- [Pihu's journal](journals/1024031014-pihu/index.md)
- [Jayant's journal](journals/1024031016-jayant/index.md)
- [Aashna's journal](journals/1024031018-aashna/index.md)

## Setup and deployment

The frontend uses Next.js and TypeScript. The backend uses FastAPI, SQLAlchemy and PostgreSQL.

- [Application setup and usage](code/README.md)
- [Render deployment guide](code/DEPLOY_FREE.md)
- [Project documentation](https://pihuuaneja.github.io/ucs503p-202627campuspool/)
- [Course guidelines](https://tiet-ucs503.github.io/semester-project/)

Compile each report by running pdflatex main.tex twice from its folder. Keep the final report's figures directory beside its source.
