# Proposal

Max 6 pages / 3,000 words including diagrams/charts

This should include intended benefits/impact of the work, a schedule and structure for the work, risk assessment and a commitment to engaging with users and stakeholders

--------------

## Benefits & Impact

* Enhances existing platform for open content. WordPress increasingly popular in HE sector. BuddyPress offers basis for an easy-to-use, identity management tool.
* Documented research into use of specific third-party APIs for integration into institutional sites.
* Documented implementation of BuddyPress as institutional social network.
* Documented implementation of BuddyPress as a staff profile management tool.
* Ties in with WordPress as a platform for the hosting, publication and dissemination of OERs (builds on ChemistryFM). 
* Raises overall awareness/use of social media among staff i.e. improves digital literacy
* Development of local BuddyPress/WordPress skills among technical staff. Enhanced capacity.
* Documented research and development of OAuth as used in university context. BuddyPress as a consumer and producer application of open content via Nucleus (MongoDB) datastore.
* User testing and alignment with CUNY 'Academic Commons in a Box' project.
* Supports the Lincoln/HEA institutional change project 'embedding OER': Dissemination and integration of third-party web services into a portfolio of work.
* Extends the use of Nucleus as an institutional datastore for people data.

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
* Month 6: Close project. Finish up documentation, release plugin(s) on wordpress.org repository.

## Risk assessment

* Involves recently appointed staff, who need to learn several different technologies (WordPress/BuddyPress/MongoDB/OAuth). They have some prior experience of this and will be mentored by more experienced staff.
* Need to investigate licensing issues around storage and re-publishing of third-party data. May need to 'cache' rather than warehouse.
* 

## Engagement and dissemination

* Project blog and Twitter
* Collaboration with and testing by CUNY Academic Commons in a Box project
* Support and user testing with Lincoln/HEA 'Embedding OER' institutional change project and sub-projects.
* Promotion of new features to all staff at Lincoln.
* Open source code on Github ('social coding')
* Plugin published/distributed from wordpress.org repository

-------------- 

# REMINDER OF EVALUATION CRITERIA (and weighting):

* Extent to which bid meets the scope of the Call (Strong / Weak / Out of Scope)
* Value for money (10%)
* Robust project plan (30%)
* Clear and compelling use case (20%)
* Potential benefits/impact (20%)
* Engagement with users and stakeholders (10%)
* Risk assessment (10%)