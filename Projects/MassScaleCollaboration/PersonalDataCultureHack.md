# Personal Data  Bi-Lingual Culture Hack

**Rough Design Concept**

Hackers and artists develop view of people from Spanish and English language vantage points using personal data from [social media platforms] to [natural language processing and/or immersion type stuff that dazza will add here] to visualize something.

# App Authorization 

Approach to permission-based personal data analytics:

* user authorized PROJECT app to access Instagram data a, b, and c
* app does network detection process and displays the top up to 5 communities of user
* user labels communities (eg family, bowling league)
* user labels each key facet of themselves (professional self, political self, family self, etc) 
* app analyzes the text patterns and images and associations/role/hierarchy overlay community by community to provide a psycho-demographic profile of "how the person shows up" in each community.

# OPEN HACKING CULTURE

* Invite creative people with tech skills (at least some of whom are familiar with data and analytics) to a fun night out at a hack space.  
* Setup a Github repo for the night with open source license.  Idea is to have fun and make things together in open source, sharable and re-usable manner. 
* To participate, people make pull requests with their contributions to the PROJECT GITHUB REPO which is covered by open source software license.

## Develop High Level Use Cases

What is a use case?  A use case is a way to use simple diagrams for describing how people do things using systems.  Use cases are a great way to identify and hone key functions, actions, sequences and experiences as a guide before building. For more info, see: https://en.wikipedia.org/wiki/Use_case

Before the hack night, develop key use cases describing what specific actions and interactions people would be able to do with the app and the main functions the app would be able to perform.  Screen by screen sketches (mock-ups, vapor-ware, etc) are another way to identify these types of high level design goals and project objectives.  

Circulate and refine the use cases over time with artist, technical and design people who will come to the hack night so they are stable drafts to share with people when they arrive.  The pre-hack use cases or mock-ups should not be too detailed or prescriptive regarding exactly how the app will work.  Have the use cases serve to convey the idea for ways language and personal data can show surprising insights about people in social contexts rather than as detailed technical or user interface requirements.  At the hack night, people can brainstorm ways to get access, analyze and display the data based on what they can do together in the time allotted. 

**Example 1: ATM Machine**

Overall purpose and scenario: Do most teller based transaction at a 24-hour publicly accessible machine.

* Actor/Action-Based Use Cases: Account holder uses ATM to conduct transactions:
— check balance
— make deposit
— make transfer
— make withdrawal 

## Success Metric:

* User can see how they showed up for others and note differences with each identity account used with the app. 

# TOOLS AND TECHNOLOGY

* Community detection algorithms 
* OAuth 2 for permission management
* D3 for Visualization
