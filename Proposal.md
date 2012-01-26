# Proposal

Max 6 pages / 3,000 words including diagrams/charts

This should include intended benefits/impact of the work, a schedule and structure for the work, risk assessment and a commitment to engaging with users and stakeholders

--------------

## Benefits & Impact

This project addresses a number of the intended benefits and impacts as outlined in the funding call, in particular work on academic identities. 

We propose to enhance an existing platform that is in widespread use in the Higher Education sector and Public Services. Over 70m websites run on WordPress, around 16% of websites worldwide. BuddyPress is now a relatively mature sub-project of WordPress and suited to both institution-wide use, as in the case of Lincoln, and departmental or project-based websites. As can be seen by Lincoln's use BuddyPress (http://blogs.lincoln.ac.uk), and indeed more so by the CUNY Academic Commons (http://commons.gc.cuny.edu), BuddyPress is an appealing and sustainable technology that supports a range of uses in a research, teaching and learning environment.

This project proposes that BuddyPress be used as a tool to manage academic staff profiles and work is already underway at Lincoln to use BuddyPress in this way. However, our planned work does not extend to the development of BuddyPress as a tool to aggregate OER content from third-party web services, which is what this project seeks to address.

This project will undertake documented research and development into the use of specific third-party APIs for integration into institutional sites (e.g. Slideshare, YouTube, Jorum). It will provide the HE sector with an overall Case Study of how BuddyPress has been implemented as an institutional social network and, more specifically, its benefits as a staff profile management tool. 

In our work on the JISC-funded ChemistryFM project, we investigated the affordances of Wordpress as a platform for the hosting and dissemination of OERs, and we understand this proposed project as building on that work, extending WordPress as a technology platform to work around academic identity and professional networking.

Through the principle use of BuddyPress to manage an academic's personal profile, we anticipate that the overall acceptance and engagement with the social web will increase across institutions that adopt this approach, offering opportunities to develop the digital literacy of staff, who are otherwise reluctant to use technology in this way. Through engaging with BuddyPress, we feel there are opportunities then to engage academic staff with the affordances of WordPress as a tool to publish their work and, in turn, promote the use of open technologies and openness in general.

Aside from the project's impact on academic staff, we are seeking support for this project so as to further develop technical staff skills and thereby enhance our capacity to innovate with WordPress. Our work on OAuth and API-based development, provides us with significant experience relevant to the use and integration of third-party web services. Our work will provide further evidence to the sector of the benefits of this approach and offer a case study of how our open source OAuth library might be re-used by other institutions. 

The project also extends our use of Nucleus as an institutional datastore for people data. Some preliminary work has been done in this area to develop a new staff directory and we will investigate how open content hosted on third-party profiles can be consumed by Nucleus and then re-published via Nucleus APIs and re-purposed on other websites.

A further impact of this project at Lincoln will be the role it plays in supporting the JISC/HEA-funded institutional change project: 'Embedding OER' (http://oer.blogs.lincoln.ac.uk). This provides us with a number of users and specific use-cases, as each team on the 'Embedding OER project' is investigating the role of open content in their discipline and addressing how OER can lead to institutional change. 

## Schedule and structure

Diagram of proposed architecture http://lncn.eu/gv8 

This is a six-month project, largely undertaken by one full-time Web Developer working in the central ICT Online Services Team. The Principal Investigator on the project will be Joss Winn, Senior Lecturer in the Centre for Educational Research (CERD) and Development and co-ordinator of the LNCD group (http://lncd.lincoln.ac.uk). Joss originally set up and continues to manage the university's BuddyPress platform. The project will be managed day-to-day by David Raines, Online Services Team Resources Manager. 

The project will be run using the 'Crystal Clear' agile methodology, which we use on other development projects. Crystal Clear is characterised by the following:

1. Seat people close together, communicating frequently and with goodwill
2. Get most of the bureaucracy out of their way and let them design
3. Get a real user directly involved
4. Have a good automated regression test suite available
5. Produce shippable functionality early and often

Within this environment, we practice open development, using Github as a source code repository (http://github.com/lncd) and Pivotal Tracker to iteratively manage project tasks (http://pivotaltracker.com). We have recently implemented an automated regression test suite and practice 'Constant integration' using the Jenkins software (http://orbital.blogs.lincoln.ac.uk/2012/01/18/jenkins-build-my-software/).

Such an environment will support the Developer on this project by ensuring that his code is available for peer-review by colleagues and publicly available for scrutiny. Code will be constantly tested for quality assurance and thereby provide working code for regular user testing. 

## Schedule of work

* Month 1: Initiate project. Set up website and development tools. Investigate existing BuddyPress/WordPress APIs and plugins. Agree working practices with principle User and identify other key Users on the project (Embedding OER project and CUNY Academic Commons in a Box project).

* Month 2: With the principle User, investigate at least three third-party APIs for integration into BuddyPress profiles. Review any licensing and Terms and Conditions on the use of this data. Design wire-frames of the academic profile management tool for user acceptance.

* Month 3-4: Working with CUNY, develop BuddyPress plugins, which integrate data from selected third-party APIs into BuddyPress profiles, enriching staff profiles with open content and rich metadata. Iteratively test the plugins with local users and colleagues at CUNY.

* Month 5-6: Working with Web Developers at Lincoln, aggregate data from enriched BuddyPress profiles into the Nucleus (MongoDB) datastore, enabling re-publishing of staff profiles with open content via APIs over OAuth. e.g. corporate website. Iteratively test the APIs with our local Web Team (Marketing).

* Month 6: Finish up documentation, release plugin(s) on wordpress.org repository. Roll out new features to all staff profiles. Close project.

## Risk assessment

As a Rapid Innovation project, we are proposing to undertake work we consider to be of high risk but potentially widespread benefit.

* The project involves recently appointed staff, who need to learn several different technologies (WordPress/BuddyPress/MongoDB/OAuth). 

They have some prior experience of this and will be mentored by more experienced staff.

* There may be licensing issues around storage and re-publishing of third-party data. 

It may be that we need to 'cache' third-party data rather than warehouse it.

* Are staff publishing sufficient open content to make use of our work?

This is a rapid innovation project, which are characteristically experimental and exploratory. We have a clear Use Case, with potential for institution-wide impact. The concurrent 'Embedding OER project' make us well placed to promote OER across the institution and the use of the project outputs.

* How will the work be sustained?

The project outputs are closely aligned with on-going work at Lincoln. The plugin(s) will be released under a GPL license and made available on the wordpress.org plugin repository. We will seek to have the plugin included as part of the CUNY Academic Commons in a Box project.

## Engagement and dissemination

We blog regularly about our work (http://lncd.lincoln.ac.uk/projects) and maintain an active Twitter account of all project work (@lncd). We have discussed our proposed project with Matt Gold, Director of the CUNY Academic Commons in a Box project and he has agreed to a formal connection between both projects, offering user testing, Developer mentoring and peer-review and the possibility of including our work as part of the CUNY project.

The work of the project will be disseminated widely at the University of Lincoln, through the HEA Change Academy 'Embedding OER' project, run by Sue Watling, Learning and Teaching Co-ordinator in CERD.

Once complete, the plugin will be activated for all staff at the University of Lincoln on our BuddyPress platform.

The outputs of the project will be GPL licensed and developed and hosted on Github, a 'social coding' platform that encourages and facilitates code forking and collaborative development. The plugin will be made available to all WordPress.org users via the official plugin repository. An announcement will be made on the BuddyPress.org developer forum and we will use that platform as our main method of communicating project progress to the BuddyPress community. We will also post announcements and updates to the JISC 'WordPress in education and research' mailing list.

-------------- 

# REMINDER OF EVALUATION CRITERIA (and weighting):

* Extent to which bid meets the scope of the Call (Strong / Weak / Out of Scope)
* Value for money (10%)
* Robust project plan (30%)
* Clear and compelling use case (20%)
* Potential benefits/impact (20%)
* Engagement with users and stakeholders (10%)
* Risk assessment (10%)