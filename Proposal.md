# Proposal

Max 6 pages / 3,000 words including diagrams/charts

This should include intended benefits/impact of the work, a schedule and structure for the work, risk assessment and a commitment to engaging with users and stakeholders

--------------

## Benefits & Impact

This project addresses a number of the intended benefits and impacts as outlined in the funding call, in particular work on academic identities. 

We propose to enhance an existing platform that is in widespread use in the Higher Education sector and Public Services. Over 70m websites run on WordPress, around 16% of websites worldwide. BuddyPress is now a relatively mature sub-project of WordPress and suited to both institution-wide use, as in the case of Lincoln, and departmental or project-based websites. As can be seen by Lincoln's use BuddyPress, and indeed more so by the CUNY Academic Commons, BuddyPress is an appealing and sustainable technology that supports a range of uses in a research, teaching and learning environment.

This project proposes that BuddyPress be used as a tool to manage academic staff profiles and work is already underway at Lincoln to use BuddyPress in this way. However, our planned work does not extend to the development of BuddyPress as a tool to aggregate OER content from third-party web services, which is what this project seeks to address.

This project will undertake documented research and development into the use of specific third-party APIs for integration into institutional sites (e.g. Slideshare, YouTube, Jorum). It will provide the HE sector with an overall Case Study of how BuddyPress has been implemented as an institutional social network and, more specifically, its benefits as a staff profile management tool. 

In our work on the JISC-funded ChemistryFM project, we investigated the affordances of Wordpress as a platform for the hosting and dissemination of OERs, and we understand this proposed project as building on that work, extending WordPress as a technology platform to work around academic identity and professional networking.

Through the principle use of BuddyPress to manage an academic's personal profile, we anticipate that the overall acceptance and engagement with the social web will increase across institutions that adopt this approach, offering opportunities to develop the digital literacy of staff, who are otherwise reluctant to use technology in this way. Through engaging with BuddyPress, we feel there are opportunities then to engage academic staff with the affordances of WordPress as a tool to publish their work and, in turn, promote the use of open technologies and openness in general.

Aside from the project's impact on academic staff, we are seeking support for this project so as to further develop technical staff skills and thereby enhance our capacity to innovate with WordPress. Our work on OAuth and API-based development, provides us with significant experience relevant to the use and integration of third-party web services. Our work will provide further evidence to the sector of the benefits of this approach and offer a case study of how our open source OAuth library might be re-used by other institutions. 

The project also extends our use of Nucleus as an institutional datastore for people data. Some preliminary work has been done in this area to develop a new staff directory and we will investigate how open content hosted on third-party profiles can be consumed by Nucleus and then re-published via Nucleus APIs and re-purposed on other websites.

A further impact of this project at Lincoln will be the role it plays in supporting the JISC/HEA-funded institutional change project 'Embedding OER'. This provides us with a number of users and specific use-cases, as each team on the 'Embedding OER project' is investigating the role of open content in their discipline and addressing how OER can lead to institutional change. 

## Schedule and structure

[Include diagram of proposed architecture]
														  
Third-party APIs < Consumer < BP profile > Nucleus APIs > Producer > lincoln.ac.uk	 and elsewhere...

* Agile methods (iterative, user focused, Constant Integration).
* Open development (Github, Pivotal Tracker)
* Quality assurance (unit testing, code peer-review, user testing, collaboration with CUNY)
* Month 1: Initiate project. Set up website and development environment. Investigate existing BuddyPress/WordPress APIs and plugins.
* Month 2: Investigate a number of (at least three) third-party APIs for consuming/integration into BuddyPress profiles, including licensing and API T&C.
* Month 3-4: Integration of data from third-party APIs into BuddyPress profiles as consumer application. Enriching staff profiles with open content and rich metadata.
* Month 5-6: Integration of BuddyPress profiles with Nucleus datastore, enabling 're-publishing' of staff profiles with open content via APIs over OAuth. e.g. corporate website.
* Month 6: Close project. Finish up documentation, release plugin(s) on wordpress.org repository. Roll out new features to staff profiles.

## Risk assessment

* Involves recently appointed staff, who need to learn several different technologies (WordPress/BuddyPress/MongoDB/OAuth). They have some prior experience of this and will be mentored by more experienced staff.
* We need to investigate licensing issues around storage and re-publishing of third-party data. It may be that we need to 'cache' third-party data rather than warehouse it.
* The BuddyPress plugin we produce may only provide limited functionality. Our use of Nucleus as an aggregated datastore of staff profile data (e.g. HR database, LDAP, BuddyPress) is the bigger project. Therefore, design documents will be a significant output to show how it can be extended for broader use. Nevertheless, the BuddyPress plugin will be self-contained and functional.
* Build it and they will/won't come!? This is a rapid innovation project, which are characteristically experimental and exploratory. We have a clear Use Case, with potential for institution-wide impact. The concurrent 'Embedding OER project' and our VC's role as Chair of HEFCE OER Committee, make us well placed to promote OER across the institution and the use of the project outputs.

## Engagement and dissemination

* Project blog and Twitter
* Collaboration with and testing by CUNY Academic Commons in a Box project
* Support and user testing with Lincoln/HEA 'Embedding OER' institutional change project.
* Promotion of new features to all staff at Lincoln.
* Open source code on Github ('social coding')
* Plugin published/distributed from wordpress.org repository
* Engagement with other developers on BuddyPress forums.
* Discussion on JISCMail WordPress list.

-------------- 

# REMINDER OF EVALUATION CRITERIA (and weighting):

* Extent to which bid meets the scope of the Call (Strong / Weak / Out of Scope)
* Value for money (10%)
* Robust project plan (30%)
* Clear and compelling use case (20%)
* Potential benefits/impact (20%)
* Engagement with users and stakeholders (10%)
* Risk assessment (10%)