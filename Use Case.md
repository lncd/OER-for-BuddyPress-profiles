**Use Case**: Enhance staff profiles with Open Educational Resources

# CHARACTERISTIC INFORMATION

**Goal in Context:** Allow staff to edit their institutional online profile and aggregate and link to Open Educational Resources from popular third-party services.

**Scope:** Academic profiles.

**Level:** Primary task.

**Preconditions:** The (intended) use of BuddyPress extended profiles within an academic context.

**Success End Condition:** Staff can aggregate and link to Open Educational Resources hosted on third-party websites by editing their BuddyPress profile.

**Failed End Condition:** Staff are unable to aggregate and link to Open Educational Resources hosted on third-party websites by editing their BuddyPress profiles.

**Primary Actor:** An Academic member of staff

**Trigger:** An 'institutional change' project to promote the production and use of OER.

# MAIN SUCCESS SCENARIO

1. Academic publishes OER on third-party website (e.g. YouTube)
2. Academic signs into her Institution's BuddyPress platform.
3. Academic chooses to edit existing academic profile.
4. Academic authorises third-party website to link to her online profile.
5. Academic saves the edit, which updates her profile.
6. Academic has linked to and/or aggregated OERs hosted on a third-party website.
7. The aggregated data from the staff profile is available for re-publishing on other institutional websites (e.g. the corporate website).

# EXTENSIONS

4a1. The third-party website does not provide a RESTful API, but does provide an RSS/XML feed.

4a2. The Academic copies and pastes the RSS feed into the required field of her online institutional profile, setting appropriate filters.

4b1. The third-party website does not provide a RESTful API, nor an RSS/XML feed.

4b2. The Academic copies the link to her profile on the third-party website and and pastes it into the required field of her online institutional profile.

# SUB-VARIATIONS

1. The individual is not a member of staff but rather a student wishing to create a public portfolio of work.

7. The information aggregated into the updated BuddyPress profile may need to be re-presented on other third-party websites and web services. 

# RELATED INFORMATION

**Priority:** Top

**Performance Target:** 5 mins.

**Frequency:** Once per third-party service added. Occasional changes to filter for each service.

**Channel to primary actor:** Web browser

**Secondary Actors:** WordPress, BuddyPress, third-party web services

**Channel to Secondary Actors:** Web browser, WordPress/BuddyPress APIs, WordPress database, third-party APIs/feeds, 

# OPEN ISSUES

* Which third-party services will be supported?
* Will profile fields differ, depending on staff/student role?
* How will third-party data be re-published on other websites, such as the corporate website? What are the licensing conditions? What are the technical issues?
* To what extent can the BuddyPress profile be treated as a producer application rather than consumer application?

# SCHEDULE

**Due Date:** Release 1.0 (September 2012).

# License for this grant application

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.