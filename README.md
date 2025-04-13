# JULIUS BÄR
# Onboard Quest - Improve Client Onboarding Efficiency in Private Banking using Machine Learning and Gamification

## Introduction:

#### What is the current problem?
In private banking, the onboarding process requires verifying client information against a set of regulatory rules to ensure compliance. This manual process is often time-consuming and error-prone, leading to delays and a poor customer experience. Inconsistencies in documentation represent another major challenge. Onboarding can involve analysing 200-300 pages of information and contracts, where discrepancies are not only common but also significantly impact efficiency. Document and data analysis may seem mundane, but the pain today is substantial. 

#### What is the expected final product?
The expectation is to develop an automated solution that can support Relationship Managers and compliance functions to ensure all onboarding rules are duly met during client onboarding.

#### Who are the users of this solution?
* Relationship Managers
* Compliance functions (1st line of defense) 

#### Use Case: 
* There is a lot of back and forth between RM and clients and risk employees, so we want to improve the efficiency of the client onboarding via an automated solution. 

## Expected Outcome:

The expectation is to develop an automated solution that can support Relationship Managers and compliance functions to ensure all onboarding rules are duly met during client onboarding, enhanced with gamification elements so the journey is efficient and more entertaining. 

## JB Slides:

Insert Pitchdeck here

Insert Deep Dive Slides here:

## Further Information:
### API Key Distribution
Each participating team will receive a unique API key.

### Initial Request
Teams will use the API key to send an initial request to the designated endpoint, which will respond with a set of four documents:  
- Passport (png)  
- Client Profile (docx)  
- Account Opening Form (pdf)  
- Client Description (txt)

### Document Analysis
Teams must analyze the contents of these documents to determine if they are consistent with each other. Consistency will be evaluated based on predefined criteria (e.g., matching names, addresses, dates of birth, etc.).

### Response Submission
After analyzing the documents, teams must submit a response indicating whether the documents are consistent ("Accept") or not ("Reject").

### Game Progression
If the submitted response is correct, the team will receive a new set of documents for analysis. If the response is incorrect, the game will restart from the beginning.

### Scorekeeping
For each API key, the system will track the longest sequence of correct responses (i.e., the "session"). The team with the longest session at the end of the challenge will be considered the winner.

## Resources:
Frontend - register your team with given API key at following URL: https://hackathon-frontend.mlo.sehlat.io/  
Backend - check specification of endpoints at following URL: https://hackathon-api.mlo.sehlat.io/docs

Additional data:  
- client_001 - client_500 - proper set of documents  
- client_501 - client_1000 - improper set of documents, very easy deficiencies  
- client_1001 - client_1500 - proper set of documents  
- client_1501 - client_2000 - improper set of documents, easy deficiencies
- clients_2001 - client_2500 - proper set of documents
- client_2501 - client_3000 - improper set of documents, medium deficiencies  

#### Important Technologies: 


## Judging Criteria:
* Presentation of the sales pitch
* Efficiency gain: Solution improves the efficiency, simplifies the process and adds some value to the step when it comes to documentation of the onboarding process
* Longest session: Team that will have the longest session in the game receive extra credits

## Voluntary evaluation
* In folder evaluation you will find 1000 clients, you can use to evaluate your solution
* Submit file with answers in the same shape as eval_solution_example.csv, named: <your_team_name>.csv via Discord to Arek Gasecki

## Point of Contact:

*	Claudine / Senad will be present and in Jury
*	The sponsor: Compliance: Tech: also, during the wknd 
*	front risk employees will be involved
*	HR reps for the booth during the wknd


## Price - the winning team members will each receive:

Inviation to Julius Bär premises to present their solution in front of senior management and potential stakeholders.
