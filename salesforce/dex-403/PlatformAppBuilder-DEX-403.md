# [Platform App Builder](https://trailhead.salesforce.com/en/credentials/platformappbuilder) - notes

I will start with the suggested trailmix trail:
- Prepare for Your Salesforce Platform App Builder Credential [trailmix](https://trailhead.salesforce.com/users/strailhead/trailmixes/prepare-for-your-salesforce-platform-app-builder-credential) ~ 52 hr 25 min
- Study for the Platform App Builder Exam trail - https://trailhead.salesforce.com/content/learn/trails/platform-app-builder-certification-prep ~ 50 min

Signed up for Declarative Development for Platform App Builders in Lightning Experience ( [DEX403](https://trailheadacademy.salesforce.com/classes/dex403-declarative-development-for-platform-app-builders-in-lightning-experience) ) training:
- 5 full days
  - **Oct 30 through Nov 3, 2023**, from **8:30 AM to 5:00 PM EDT** ∙ Delivered by Salesforce

Next (optional), sign up for Prepare for your Platform App Builder Certification Exam ( [CRT403](https://trailheadacademy.salesforce.com/classes/crt403-prepare-for-your-platform-app-builder-certification-exam) )

This is one day only. Available dates, after November
- Nov 14 through Nov 14, 2023, from 8:30 AM to 5:00 PM PST (from 11:30 AM to 8:00 PM EST) ∙ Delivered by Salesforce
- Dec 19 through Dec 19, 2023, from 8:30 AM to 5:00 PM PST
- Dec 28 through Dec 28, 2023, from 8:30 AM to 5:00 PM CST (from 9:30 AM to 6:00 PM EST) ∙ Delivered by Salesforce 

Once done, I'll ask Mihir and/or Olga about how to sign up for exam.

Additional resources via TPL card:
https://learning-oreilly-com.ezproxy.torontopubliclibrary.ca/videos/salesforce-platform-app/9781804611197/

# Study for the Platform App Builder Exam - [trail](https://trailhead.salesforce.com/content/learn/trails/platform-app-builder-certification-prep)

## Cert Prep: Platform App Builder: Fundamentals and User Interface - module

This module has 3 units. PDF containing all 3 units can be downloaded, and I saved it in my git repo as PAB_Mod_1_Printable.pdf.


### Unit 1: Get Started with Platform App Builder Certification Prep
- Salesforce Fundamentals: 23%
- User Interface: 17%
- Data Modeling and Management: 22%
- Business Logic and Process Automation: 28%
- App Deployment: 10%

60 multiple-choice/multiple-select questions and 5 non-scored questions
passing score: 63%
time: 105 minutes

### Unit 2: Study Salesforce Fundamentals

Has few practice questions and 7 flashcards:


|Card | Front | Back |
| ---|---|---|
| 1 | How many assignment rules can be active on Case? | For each rule type, only one rule can be in effect at any tim |
| 2 | What is the maximum number of components a dashboard can have? | Up to 20 components |
| 3 | What are the two sharing rule types? | Owner Based and Criteria Based |
| 4 | Finance wants the salary field to only be visible to select employees. How can this be achieved? | Set the field-level security |
| 5 | What two permissions are needed to create custom reports that all users can view? | Manage Public Reports and Create and Customize Reports |
| 6 | Managers need to edit cases for subordinates, not cases for groups and view all cases. | Create standard role hierarchies and set organization-wide sharing defaults to public read/only | 
| 7 | Which two ways can an App Builder grant object-level access to users? | Profiles and Permission Sets |


Links to several related modules and superbadges


### Unit 3: Learn About the User Interface

Has few practice questions and 3 flashcards:

|Card | Front | Back |
| ---|---|---|
| 1 | What are the two types of Quick Actions? | - Object-specific and Global |
| 2 | What are the three types of pages you can build with Lightning App Builder? | Record, Home, App |
| 3 | What picklist fields are used in the lead process are not available for record types? | Case status, Lead status |

## Cert Prep: Platform App Builder: Data Modeling and App Deployment - [module](https://trailhead.salesforce.com/content/learn/modules/platform-app-builder-pt2?trail_id=platform-app-builder-certification-prep)

This module has 3 units.

### Unit 1: [Study Up on Data Modeling and Management](https://trailhead.salesforce.com/content/learn/modules/platform-app-builder-pt2/platform-app-builder-data-modeling-and-management?trail_id=platform-app-builder-certification-prep)


Data Modeling and Management section of the exam - 22%

Has few practice questions and 3 flashcards:

|Card | Front | Back |
| ---|---|---|
| 1 | Maximum number of records that an App Builder can import at a time with Data Import Wizard | 50,000|
| 2 | What are the types of lookup relationships available for external objects? | Lookup Relationships, External Lookup Relationship, Indirect Lookup Relationship |
| 3 | What can an App Builder create with Schema Builder? | Custom Objectes, Lookkup Relationships, Master-detail relationships, All Custom Fields except Geolocation| 
| 4 | What are two capabilities of Schema Builder? | Modify custom field help text on standard objects, Create lookup or master-detail object relationships |
| 5 | What happens to a junction object record when either associated master record is deleted? | The record is deleted and placed in the recycle bin. |

Links to several related modules and projects.

### Unit2: [Refresh on Business Logic and Process Automation](https://trailhead.salesforce.com/content/learn/modules/platform-app-builder-pt2/platform-app-builder-automation?trail_id=platform-app-builder-certification-prep)

Business Logic and Process Automation section exam - 28% 

Key topics:
- record types
- formula fields
- roll-up summary fields
- validation rules
- approval process
- workflow, Flow and Process Builder
- avoid errors in automation

Has few practice questions and 5 flashcards:

|Card | Front | Back |
| ---|---|---|
| 1 | How can the record type for a converted lead be set based on the user that is converting the lead? | Set the default record types for each Profile for Account, Contact, and pportunity to the desired record type for converted records |
| 2 | What is the correct order of execution validation rules are processed? | Validation rules, Assignment rules, Auto-response rules, Workflow rules (with immediate actions), Escalation rules.|
| 3 | What function should an App Builder use to return “today’s” date in a formula field? |TODAY() |
| 4 | What fields are available when MIN or MAX rollup type is selected? | Number, Currency, Percent, Date, Date/Time |
| 5 | Which action is not executed after a reevaluated workflow? | Time-dependent actions aren’t executed for a reevaluated workflow rule. |

Links to several related trails, modules and projects.

### Unit 3: [Learn About App Deployment](https://trailhead.salesforce.com/content/learn/modules/platform-app-builder-pt2/platform-app-builder-deployment?trail_id=platform-app-builder-certification-prep) 

Key topics:
- Application lifecycle management
- sandboxes
- changesets
- packaging: unmanaged and managed
- deployment plan

"Partial copy sandbox has 5GB limit
 
Has few practice questions and 5 flashcards:

|Card | Front | Back |
| ---|---|---|
| 1 | What is one component that is unavailable in a change set? | Account Teams |
| 2 | What is a managed package? | A managed package is a collection of components that are made available to other organizations through the AppExchange. |
| 3 | What is the refresh interval of a Partial Copy Sandbox? | 5 days |
| 4 | For new app development, what deployment plan is best practice for the App Builder to follow? | Develop, test, build the release, stage, release |

Just one links to related trail.





Continuing on the exam preparation [trailmix](https://trailhead.salesforce.com/users/strailhead/trailmixes/prepare-for-your-salesforce-platform-app-builder-credential), 

Started module  [Service Cloud for Lightning Experience](https://trailhead.salesforce.com/content/learn/modules/service_lex?trailmix_creator_id=strailhead&trailmix_slug=prepare-for-your-salesforce-platform-app-builder-credential)





