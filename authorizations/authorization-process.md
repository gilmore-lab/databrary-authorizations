# AUTHORIZATION DOCUMENTATION

ACCESS:
* Open Project - Project: community/outreach/progress tracking
* Email Alias- authorize@databrary and help@databrary
* Motordocs server- authorization folder/documentation/process.md and template emails
* SU on Databrary site to authorize people and institutions

## Tracking Authorization Request in OpenProject

#### Receive authorization request via email
* Email subjects should be:  
**Databrary authorization request from.....** or  
**Databrary notifications - XXX requested to be authorized through SCHOOL**  
* Check to see if the individual who requested authorization has PI status by looking for their faculty page online
* **Databrary Website** emails have the agreement for the researcher when they register

#### Check Authorization Status

* Confused about their authorization status
	+ Find email on Databrary if email address is not within email body
	+ end email "Unsure of Status" (server/authorizations/template emails/Authorization request emails/unsure of status to see how to move forward with authorization
  		- If PI, follow from **Researcher has PI Status**
  		- If student, ask them to have advisor register and create an account so the student can get access as an affiliate
* Researcher has PI status
  	+ Go to OpenProject
  	+ Create a new ticket in OpenProject within the "Project" called "Community outreach"/"progress tracking"
  	+ Determine Status of Institution
  		- If institution doesn't already exist - Create Institution
  			* select **Work Packages** and **+ New Work Package** from the left side
  			* Mark the **Type** as **institution**
  			* Mark **Subject** as **Institution Name**
  			* Mark the institution's **Status** as **active** because now there is a PI waiting on us
  			* Mark the institution's **Country**
  			* In the Description field add:
				+ OSP information that you google at institutions website
				+ This should be someone who has the ability to sign legally binding agreements. This is typically NOT IRB or department heads.
  					- Grants and Contracts people
  					- Office of sponsored research/projects directors and vice presidents
  					- Authorized Organizational Representitive (AOR)
  					- UK, EU, Canada - finding the official is tricky - look for Chancellor
  				- Director and general email
			* Click the **Create** button
		- If institution does exist go to the institution page

	+ Create User
		- Create a user ticket under parent institution by clicking the "+" key near "Work Package Hierarchy"
		- Mark the new ticket **Type** as **user**
		- Mark the **Subject** as the **PI's name**
		- Description field should include all information from request email
			* PI's email
			* party number (found on agreement)
			* Link the PI's faculty page (found from google)
		- Status = new
		- Click the **Create** button
	+ Create User authorization ticket under the user's ticket
		- Click "+" key by "Work Package hierarchy"
		- Mark the **Type** as **authorization**
  		- Mark **Subject** as **PI Name**
		- Mark the authorization ticket's **Status** as **active** because PI requested authorization and is waiting on us to contact the OSP
		- Mark who is responsible for the authorization
			* Allows for tracking the # of authorizations you are working on

## Submitting Authorization Request
#### Send email
* Choose 1 email:
    - If school is new and authorizing official is unknown
    	**When official is not known to PI** (server/authorizations/Template emails/Templates-PIs/)
    - If school has already approved PI's
    	**When the school is already approved** (server/authorizations/Template emails/Templates-PIs/)

  Include in email:
  	+ Subject: Your Databrary Authorization
  	+ Attach Databrary Access Agreement for specific PI which you should have received via email when the person registered
    	- **If the school has revisions** (marked in the amedment section of the institution ticket in openproject), then create a new version of the agreement with the previously approved revisions (revised agreements are stored in server/authorizations/revisions/access agreements/school)
    	- **If you do not have the agreement in email**, you can generate an agreement from the site: https://nyu.databraryorg/party/admin, search the researcher's name, and select the "agreement" button and then the agreement should be in your email with the date listed as today's date
  	+ CC Karen (kea1@nyu.edu) and authorize@databrary.org on all correspondence so they have copies
  	+ Copy and paste all email interaction with the PI in OpenProject authorization ticket after you send and receive all emails.
  		- Go to Work Packages > Authorization and select the User
  		- When the user is opened, select **Update** at the bottom of the page
  		- copy the emails in the **Notes** section

#### Wait to receive permission to reach out to school on behalf of PI
* If don't hear back from PI within 48 hours, send email to Karen so she can send an email to the PI with a slight nudge.
	+ Send the email: "Draft Emails- Karen/From Karen for PI's who don't respond within 48 hours" (server/authorizations/template emails/Templates-PIs/)
  	+ Follow instructions with the proper subject and email
  	+ Mark all email interaction with the PI in OpenProject
  	+ CC authorize@databary and Karen

* If the PI still doesn't respond after 2-3 emails from you and Karen, mark the **status** of the authorization ticket as **rejected** and you can always reopen the ticket if the researcher responds.

#### After receiving approval to reach out to school, send email "template OSP" email

Who to email: Information in institution openproject ticket- grants and contracts people or someone who has ability to sign legally binding contracts

* Choose 1 email
  	+ "New Institution" if you have never worked with them before
		+ "Previously approved Institution" if they are already approved
  	+ Shortened emails to NYU, PSU, or UMD if it is one of those schools

* Include in email
	+ Email of OSP
	+ CC researcher requesting auth, authorize@databrary.org, Karen
	+ Attach agreement with revisions if necessary or their original agreement
	+ Subject: Databrary Access Agreement for Dr. [Full Name]
	+ Fill in other name spots in the email
	+ Mark status of authorization ticket in OpenProject as "Submitted"

#### Wait to receive the agreement with the OSP's signature
* PI signature not required on our end because their name is already printed but some schools require it on their end
*  Ensure that all necessary pages are signed and initialed
	+ Handwritten signature is required on lines for 'Signature of AOR'
	+ Handwritten initials required
	+ **send back if they missed initials** on page 2 and 3

#### Send email follow up to OSP if the school doesn't respond for 2 weeks
* **Continue doing this until you receive the signed scanned agreement. We do NOT need mailed copy.**
  	+ Find email: (server/authorizations/template emails/Templates-OSPs/"Follow up email when no response from OSP"
  	+ Attach agreement


## Revisions

1. If the OSP submits revision requests to you, review them

2. Check the document "Revision requests" (server/authorizations/revisions/revision requests) to cross check the requests to see if there is documentation of how to handle it already. If Eric Rasmussen (eric.rasmussen@nyu.edu) has previously approved the revision request, you can tell the OSP that we can accept the revision.

2. If it is a new revision request, Tell OSP that requests are not common and that we will have to consult general counsel to see if we can accept the request. Sample email for this language can be found server/auth/template emails.templates-osp/"First email response to revision request." 

3. Forward the chain to Joy. She will work with Eric at NYU's general council to determine the response to the request. 

	- Portray to the OSP why NYU's general counsel will or will not accept the revisions. Do NOT CC Eric on the response back to the instutition.

	- Go back and forth (and keep the PI out of it and not CC'd) until a final version is created.

5. On the institution ticket in Open Project, select that there is an amendment so all other PI's will have amendments to their agreement when you submit new ones.

6. Save a .md and .pdf version of the agreement with revisions in the revisions folder on the server (authorizations/revisions/agreements) so it can be used going forward.

7. When new authorizations are submitted to that school, generate a new agreement using previously approved language and mention it in the email to the OSP.

## Receive approved agreement

#### OpenProject tracking
* Mark institution ticket's **status** as **authorized** in OpenProject
* Mark authorization ticket's **status** to **authorized** in OpenProject
* Upload signed agreement to authorized ticket
	+ if the file is too big (>1MB), open it in Preview mode and export it as reduced file size so you can upload it to Open Project.

#### Send confirmation email
* Get email "Congrats on your authorization" from the server/authorization/template email/template-PI's/congrats on your authorization"

* Include in email
	+ Subject: Received signed Databrary Agreement
	+ CC: researcher, authorize@databrary.org, approving authority email if they sent agreement

#### Create institution on Databrary if it doesn't already exist on Databrary
* make sure you are logged out of the databrary.org website
* SU onto the site by adding ?js=0 to url for superuser
* Select login
* Log in and choose the superuser button
* Go to: https://nyu.databrary.org/party/create
 	+ Prename: "The" if it is part of the name, otherwise keep blank
 	+ Sortname: University of ______
 	+ Submit to create

#### Authorize the school through Databrary

* SU onto the site by adding ?js=0 to url for superuser
* Go to Databrary's affiliate page
	+ Go to: https://nyu.databrary.org/party/0
 	+ Edit button
	+ Affiliates tab
* Type in school you need to authorize
* SELECT:  New authorized institution: Allow access to other's data shared on Databrary: "Admin access: can authorize users on Databrary's behalf"
* SELECT: Grant access to Databrary's group/lab data: "No access: Cannot access....""
* Delete expiration date if there is one

#### Authorize the PI for a new school

* Click on newly created school
* Edit tab
* Affiliates tab
* Search researcher

* Select: Allow access to others' data on databrary: "Authorized Investigator: can access all shared databrary data and can contribute and share"
* Grant access to university ___ 's group/lab data: "No access: canot access university's data"

#### Authorize the PI for Existing School
* Go to Institutions affiliate page
	+ Go to: https://nyu.databrary.org/party/0
 	+ Search Institution
	+ Select Institution
	+ Edit button
	+ Affiliates tab
* Type in researcher you need to authorize

* Select: Allow access to others' data on databrary: "Authorized Investigator: can access all shared databrary data and can contribute and share"
* Grant access to university ___ 's group/lab data: "No access: canot access university's data"

* Delete expiration date if there is one

### Recreate agreement
* SU onto the site by adding ?js=0 to url for superuser
* Go to Datbarary's admin page
	+ Go to: https://nyu.databrary.org/party/admin
	+ Query Researcher name
	+ Click the agreement button next to their name
* The recreated agreement is emailed to authorize@databrary.org


#### DELETE PARTY ON DATABRARY
* SU page
* party/admin page
* Query for name
* Select delete
* Submit (only works if there is no existing linkages or relations. If they are added on volumes or have pending auths)

Delegate Proxy Privileges: To give people access to authorize people on the pi's behalf, only granted if a PI specifically requests to have a lab member be able to do this on their behalf. It is not currently exposed to users on our interface.

Affiliates tab:
Databrary level: Admin
Lab level: Manager


# Forgotten Username/Password

+ Look up the email of the researcher on databrary.
	* SU onto the site by adding ?js=0 to url for superuser
	* Go to: https://nyu.databrary.org/party/0
	* Search researcher

+ Instruct researcher to change password at: https://nyu.databrary.org/user/password

# How to move an investigator to a new institution in Open projects

+ Look up the Institution #XXXX of the new institution
+ Go to the user entry for the investigator
+ Update the user entry and change the 'Parent ID' to the new institution number.
+ The investigator will now be listed under the new institution
