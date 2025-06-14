# Invite Central

## Idea - Visitor Management
### Invite and track guests for any birthday, meeting, party, rally, reunion, meeting, seminar, discourse, lecture, marriage, kitty, or just a visit.

## Caters to
### Organizer - Who wants people to get together and allows them to join. Also sets the Guards who will be at the entry. Any user can be an organizer.
### Co-organizer - Same as organizers but a smaller subset of rights
### Visitors - Invitees who are invited to join an event. Can invite if event permits (tracking of those is available if event permits)
### Guards - Security to identify and track visitors (never have any access of vistors).
### Payment Gateway - Accept ticket cost or Billcost Share
### Printers - Lanyard, ID Cards, Bands, Broshures etc design and printing

## Good to have 
### Create Visitor's subgroup 
### Update Group/Sub Group as Visitor arrive.
### Picture Share to Group/Sub Group

## Tech - fully serverless
### Frontend - React / ShadCN UI fully client end deployable on Github actions
### Backend - FastAPI (Models/Routers/Schemas/CRUD etc) fully deployed on Lambda AWS using serverless framework.
### DB - Dynamo DB single Table Design taking all efforts to keep the costs as low as possible (Priority 1) deployed using serverless framework
### Queue - SQS with Worker Lambda to handle async tasks deployed using serverless framework
### External API Gateway - Fast API servers for internal consumption which interact with payment gateway, printers, etc. 

1. Clarity of Idea - What is to be done
2. Personas
3. UI Design on what we need this to look like
4. UI Functionality for how the UI functions and what they see/share
5. Sample Data for UI and how it should look
6. Schema(Query Pattern) for the UI
7. Model (Relational Model) for understanding data
8. DB design DynamoDB or PostGres
9. API linking Schema to DB and defining functionalities if any for backend.


