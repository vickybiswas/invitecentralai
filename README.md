# Invite Central

## Idea - Visitor Management
### Invite and track guests for any birthday, meeting, party, rally, re-union, meeting, seminar, discourse, lecture, marriage, kitty, or just a visit.

## Tech - fully serverless
### Frotend - React / ShadCN UI fully client end deployable on github actions
### Backend - FastAPI (Models/Routers/Schemas/CRUD etc) fully deployed on Lambda AWS using serverless framework.
### DB - Dynamo DB single Table Design taking all efforts to keep the costs as low as possible (Priority 1) deployed using serverless framework
### Queue - SQS with Worker Lambda to handle async tasks deployed using serverless framework
