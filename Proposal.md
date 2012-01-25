# Proposal

Max 6 pages / 3,000 words including diagrams/charts

This should include intended benefits/impact of the work, a schedule and structure for the work, risk assessment and a commitment to engaging with users and stakeholders

--------------

## Benefits & Impact

* Enhances an existing platform for open content. WordPress is increasingly popular in the HE sector. BuddyPress offers the basis for an easy-to-use, identity management tool for staff.
* We will undertake documented research into use of specific third-party APIs for integration into institutional sites.
* Documented implementation of BuddyPress as institutional social network.
* Documented implementation of BuddyPress as a staff profile management tool.
* Ties in with WordPress as a platform for the hosting, publication and dissemination of OERs (builds on ChemistryFM). 
* Raises overall awareness/use of social media among staff i.e. improves digital literacy
* Development of local BuddyPress/WordPress skills among technical staff. Enhanced capacity.
* Documented research and development of OAuth as used in university context. BuddyPress as a consumer and producer of open content via Nucleus (MongoDB) datastore.
* User testing and alignment with CUNY 'Academic Commons in a Box' project.
* Supports the Lincoln/HEA institutional change project 'embedding OER': Dissemination and integration of third-party web services into a portfolio of work.
* Extends the use of Nucleus as an institutional datastore for people data. This data will be available to all applications/websites that use Nucleus, such as Orbital and the corporate website.
* BuddyPress as institutional staff profile tool. Some preliminary work done in this area on the staff directory, which pulls from blogs and repository via Nucleus APIs.

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
* Build it and they will/won't come!? This is a rapid innovation project, which are characteristically experimental and exploratory. We have a clear Use Case, with potential for institution-wide impact. The concurrent 'Embedding OER project' and our VCs role as Chair of HEFCE OER Committee, make us well placed to promote OER across the institution and the use of the project outputs.

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