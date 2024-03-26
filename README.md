## Group Members

Wasath  -> DevOps, Backend, Frontend, UI, Research
Sanuda -> Research, Frontend, 
Yasith ->  DevOps, Backend, Frontend, UI, Research
Dilantha -> Frontend, UI, Research
Trishan -> DevOps, Backend, Frontend, UI, Research
Lithara -> UI, Frontend, Research

---

## Key Points

### Planning
- Why we choose?
- How we gathered data? 
	- Google Forms
	- Observe some dispensaries  
- *Dompe* divisional hospital is the first fully digitalized hospital system in the south asia region. 

| Pros                                                            | Cons                                                                                                              |
| --------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| Communication with doctors of the inside hospital is available. | Intercommunication other hospitals is not in this system                                                          |
| Digitalize every medical record.                                | Patient's contribution to add the medical record is poor.                                                         |
| Reduce the data loss of a patient by their own responsibility.  | When some new patient comes to get observed by a doctor, the old medical records are not in the current database. |
> We developed our system with the help of old system's Cons.


## Analysis

- Centralize database to store Patient's & Doctors information.
- Patient can give access to the doctors very easily can more securely.
- Not only the clinical doctors who working with gov or pvt hospitals but also this system will help to track the records of family doctors as well
- Before this new system, patients didn't have any medical report system freely.

## Design

### Solution Design
- e-prescription platform
- Share details with doctors securely
- Medical reports service
- Doctor channeling & appointments 
- Health Progress tracker 
- 24/7 seamless connection with doctors 
- Dashboard with most important details

### User Experience Design
- Bright white colors to the background for 
- No distraction colors
- End to end user journey
-  Discuss user stories
### User Interface Design
- Figma is the main software that we designed our UI
- Web standards and mobile responsive
- Clean style guide
- Re usable design components
- World recognized web and mobile grid system.
### Architectural Design
- Microservice architecture
- 2 Backends, 3 frontends, 1 databse
- High security with infrastructure network rules
- High availability backend and frontend services
- High Consistency & High Partition tolerance(CP) database.
- 2 token based authorization & authentication.
- User & Doctor  independent identification in database layer.
- Can be deployed in Kubernetes architecture as well.
- Hosted on a cloud platform - Azure Cloud
### Future Implementation Design
- Direct messaging feature
- Subscription to maintain the service
- SLMC API integration
- Mobile App (Cross Platform)

## DevOps
- Mainly we are following DevOps practices to keep the reliability of the code and developer consistency.
### Development

| Backend | Frontend  | Database               | Deployment           | Hosting              |
| ------- | --------- | ---------------------- | -------------------- | -------------------- |
| NodeJS  | NextJS 14 | Azure Cosmos - MongoDB | Docker<br>Kubernetes | Azure Cloud Platform |
| NestJS  |           |                        |                      |                      |

### CI/CD
- Every single deployment is automated with github actions.
- There is the specific repository to manage the deployments handles by a GitHub action bot created by our team.
- Cron job is running every 6 hours.

### Testing
- Manual e2e, unite testing done.
