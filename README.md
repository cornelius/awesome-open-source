# Awesome Open Source

> A curated list of resources related to how to do [open source](https://en.wikipedia.org/wiki/Open_source) projects

Open source is a way of running projects openly and collaboratively, giving users and developers the freedoms to use, share, and modify the sources. It's prevalent in open source software, but extends to complementary areas such as documentation or design, and broader areas such as open content and open collaboration.

This list focuses on resources about the why and how to do open source projects, not so much about the what of concrete projects. It does contain links to lists of awesome open source projects, though.

[Contributions](CONTRIBUTING.md) are welcome. Read the [guidelines](CONTRIBUTING.md) how to contribute.

## Contents

* [Governance](#governance)
* [Licensing](#licensing)
* [Legal](#legal)
* [Culture](#culture)
* [Organizations](#organizations)
* [Funding](#funding)
* [Conferences](#conferences)
* [Community](#community)
* [Development best practices](#development-best-practices)
* [Marketing](#marketing)
* [Infrastructure](#infrastructure)
* [Research](#research)
* [Surveys](#surveys)
* [Inner Source](#inner-source)
* [History](#history)

## Governance

* [Open Source Archetypes](https://blog.mozilla.org/wp-content/uploads/2018/05/MZOTS_OS_Archetypes_report_ext_scr.pdf) - Framework for classifying options how to run open source projects
* [Open Source Survey](https://opensourcesurvey.org) - Survey ran by GitHub from 2017 about open source development practices and communities
* [Open Source Governance Models](https://github.com/cornelius/open-source-governance) - Collection of data about open source governance models
* [On Consensus and Humming in the IETF](https://tools.ietf.org/html/rfc7282) - Article about rough consensus which is a pattern used in many open source projects in some way
* [OASIS Open Projects](https://oasis-open-projects.org/) - Program to support projects bringing together open source and open standards
* [Sustainable Free and Open Source Community](https://sfosc.org/) - Principles of sustainable open source communities and overview of possible open source business models
* [Sustain](https://sustainoss.org/) - Group of people, events, and material about sustainability of open source projects
* [Open Governance](https://github.com/opengovernance/opengovernance.dev) - Checklist and some pointers regarding open governance in context of open source
* [Minimum Viable Governance](https://github.com/github/MVG) - A minimum governance model template
* [The Four Opens](https://openinfra.dev/four-opens/) - Example of an open governance model

## Licensing

### Licenses

* [OSI approved licenses](https://opensource.org/licenses) - Canonical list of open source software licenses approved by the Open Source Initiative (OSI)
* [Annotated Open Source Definition](https://opensource.org/osd-annotated) - The definition of open source which is the base for the OSI license list, with rationales
* [Creative Commons](https://creativecommons.org) - Open licenses for non-code such as documentation or artwork
* [Choose an open source license](https://choosealicense.com/) - Simple license chooser to help you choosing a license for your project
* [Open Source License Compendium (OSLic)](https://telekom.github.io/oslic/) - Compendium with instructions how to fulfill obligations of open source licenses
* [Open Source License Compliance Handbook](https://github.com/finos-osr/OSLC-handbook) - Detailed guideline how to comply to a large selection of open source licenses
* [Open Source License Checklists](https://www.osadl.org/Access-to-raw-data.oss-compliance-raw-data-access.0.html) - Formal machine-readable representations of obligations of many open source licenses
* [TLDRLegal](https://tldrlegal.com/) - Summary of licenses in plain English
* [Making Your Code Available Under An Open Source Licence](http://oss-watch.ac.uk/resources/opensourceyourcode) - Overview of how to choose and apply open source licenses
* [Open source licenses: What, which, and why](https://arstechnica.com/gadgets/2020/02/how-to-choose-an-open-source-license/) - Overview of the most important Open Source licenses and what they mean
* [copyleft.org](https://copyleft.org/) - Detailed information about the GPL and other copyleft licenses
* [GPL Cooperation Commitment](https://gplcc.github.io/gplcc/) - Pledge to cooperatively solve GPL v2 violations
* [The MIT License, Line by Line](https://writing.kemitchell.com/2016/09/21/MIT-License-Line-by-Line.html) - A very thorough explanation of the MIT license
* [License Center](https://github.com/LeChasseur/ifrOSS/blob/master/Lizenzcenter.md) - Categorized list of open source, open content, open data, open hardware licenses
* [Universal License List](https://open.windriver.com/info/uni-license-list/index.html) - Aggregated list of licenses encountered by a combination of scanning tools
* [Scancode LicenseDB](https://scancode-licensedb.aboutcode.org/) - Extensive list of licenses with meta data such as SPDX identifiers, classification, and links to text representations

### License agreements

* [Contributor License Agreement and Developer Certificate of Origin references](https://toscalix.com/2019/10/13/references-about-cla-dco-fla-and-similar-topics/) - Many links to material about CLA, DCO, FLA and related information
* [Why CLAs aren't good for open source](https://opensource.com/article/19/2/cla-problems) - Article with an argument against CLAs (with a counter-argument in the comments)
* [Contributor Agreements](http://contributoragreements.org/) - Information and a tool to create contributor agreements
* [DCO](https://developercertificate.org/) - Developer certificate of origin used by the Linux Kernel and other projects

### License compliance

* [SPDX](https://spdx.org/) - Standards to represent and communicate license information
* [Tooling Ecosystem working with SPDX](https://docs.google.com/document/d/1A1jFIYihB-IyT0gv7E_KoSjLbwNGmu_wOXBs6siemXA/edit) - Extensive list of tools working with SPDX information
* [Software Bill of Materials](https://www.ntia.gov/SBOM) - Explanations and examples about what a Sotware Bill of Materials is and how it's used
* [Clearly Defined](https://clearlydefined.io) - Project of the Open Source Initiative to get clearly defined license data for open source projects
* [Open Source License Compliance in Software Supply Chains](https://dirkriehle.com/publications/2017-selected/license-clearance-in-software-product-governance/) - Article about what to consider when making sure products based on open source are compliant to the open source licenses
* [REUSE](https://reuse.software/) - Specification and tools to declare copyright and license in open source software
* [Blue Oak Council](https://blueoakcouncil.org/) - Resources around legal licensing questions, focused on permissive licenses
* [How and why to properly write copyright statements in your code](https://matija.suklje.name/how-and-why-to-properly-write-copyright-statements-in-your-code) - Guide how to write copyright statement including legal background

## Legal

* [Model Trademark Guidelines](http://modeltrademarkguidelines.org) - Guidelines for open source projects how to write trademark guidelines
* [Open Usage Commons](https://openusage.org/) - Organisation for holding trademarks for open source projects
* [Open Invention Network](https://www.openinventionnetwork.com/) - Defensive patent pool and community to protect open source from patent threats
* [OpenChain Project](https://www.openchainproject.org/) - Project to define, support, and certify open source compliance programs
* [Balanced Employee IP Agreement](https://github.com/github/balanced-employee-ip-agreement) - Reusable agreement which makes sure employees keep the rights on side projects they do not do as part of their job
* [Open Source Casebook](https://google.github.io/opencasebook/) - Legal analysis of key legal topics in open source, including primary sources
* [Understanding US export controls with open source projects](https://www.linuxfoundation.org/blog/2020/07/understanding-us-export-controls-with-open-source-projects/) - Whitepaper on what to consider regarding export control regulation which might affect open source projects
* [Journal of Open Law, Technology & Society](https://jolts.world/) - Free legal journal covering issues in the realm of openness, in particular open source software
* [The International FOSS Law Book](https://github.com/IFOSSLawBook/ifosslawbook) - Background of how open source is seen from the point of view of legal systems in different countries
* [Requiring a specific Open Source Software in public
contracts – best practices to adopt](https://www.lfenergy.org/wp-content/uploads/sites/67/2019/10/Note_OpenSource_CompetitionLaw_EN-1.1.pdf) - Guide for requiring open source in public tenders
* [Guidelines on the acquisition and reuse of software for public administrations](https://docs.italia.it/italia/developers-italia/gl-acquisition-and-reuse-software-for-pa-docs/en/master/index.html) - Guidelines for acquiring open source software in Italy

## Culture

* [The Cathedral and the Bazaar](http://www.catb.org/~esr/writings/cathedral-bazaar/) - Influential paper by Eric Raymond from 1997 laying out the principles of open source
* [Contempt Culture](https://blog.aurynn.com/2015/12/16-contempt-culture) - Advice about how to create a healthy and respectful culture, explained at the example of contempt towards other programming languages
* [The people behind the code](https://github.com/customer-stories?anchor=results&type=developers) - Interviews with open source contributors
* [Open Source Diversity](https://opensourcediversity.org/) - List of information, projects, and other resources supporting more diversity and inclusion in open source communitites
* [What is open?](https://okfn.org/opendata/) - Beyond open source software, what is open data and content?
* [Open Advice](http://open-advice.org/) - Answers the question what 42 prominent contributors would have liked to know when they started with open source

### Maintainers

* [Awesome Maintainers](https://github.com/nayafia/awesome-maintainers) - Open source maintainers talking about maintaining open source projects
* [The Open Source Contributor Funnel](https://mikemcquaid.com/2018/08/14/the-open-source-contributor-funnel-why-people-dont-contribute-to-your-open-source-project/) - A model how people become contributors to open source projects
* [The role of a maintainer](https://matthewrocklin.com/blog//2019/05/18/maintainer) - Best pratices for open source maintainers

### Code of Conducts

* [Contributor Covenant](https://www.contributor-covenant.org/) - Popular code of conduct which can easily be adapted to most projects
* [Ubuntu Code of Conduct](https://www.ubuntu.com/community/code-of-conduct) - The Ubuntu code of conduct which has been the base for several other code of conducts
* [KDE Community Code of Conduct](https://www.kde.org/code-of-conduct/) - A code of conduct stressing pragmatism and mutual support

## Organizations

* [Growing Open Source Projects with a Stable Foundation](https://www.cyrius.com/foss-foundations/growing-open-source-projects.pdf) - Primer about the role of foundations in the open source ecosystem

### Big Free and Open Source Software Foundations

* [Free Software Froundation (FSF)](https://www.fsf.org/) - Organization behind the GNU project, including the family of GNU Public Licenses
* [Free Software Foundation Europe (FSFE)](https://fsfe.org/) - European organization advocating for Free Software
* [Open Source Initiative (OSI)](https://opensource.org/) - Organization stewarding the Open Source Definition
* [Linux Foundation](https://www.linuxfoundation.org/) - Organization supporting open source communities and industries through governance, events, and training
* [Apache Software Foundation](http://www.apache.org/) - Organization providing home and governance to a large set of open source projects, including the Apache HTTP Server
* [Eclipse Foundation](https://www.eclipse.org/org/foundation/) - Organization home to the Eclipse IDE and hundreds of other projects in domains such as IoT and others

### Umbrella Organizations

* [Umbrella Organizations](https://en.wikipedia.org/wiki/List_of_free_and_open-source_software_organizations#Umbrella_organizations) - List of organizations acting as umbrella organizations for open source projects
* [Software Freedom Conservancy](https://sfconservancy.org/) - Non-profit organization supporting open source communities in legal matters
* [Software in the Public Interest](http://www.spi-inc.org/) - Non profit organization acting as fiscal sponsor to many open source projects
* [Commons Conservancy](https://commonsconservancy.org/) - Umbrella organization for open source projects, based in Europe
* [NumFOCUS](https://numfocus.org/) - Umbrella organization for open source scientific compute projects

## Funding

* [Nadya Eghbal's "Lemonade Stand"](https://github.com/nayafia/lemonade-stand) - A comprehensive list of funding methods for open source projects
* [Open Source Software Funding Platforms Registry](https://www.oss.fund/) - List of platforms for funding open source software development
* [Open Collective](https://opencollective.com/) - Open source platform for managing and connecting projects, fiscal sponsors, and financial contributors
* [Decentralized funding? An analysis of three programs](https://nadiaeghbal.com/grant-programs) - Analysis of some programs to fund open source development in an open and decentralized way through development grants
* [COSSI: Commercial Open Source Software Company Index](https://docs.google.com/spreadsheets/d/17nKMpi_Dh5slCqzLSFBoWMxNvWiwt2R-t4e_l7LPLhU/edit#gid=0) - List of companies which make more than million USD revenue from open source software
* [FOSS Contributor Fund](https://github.com/indeedeng/FOSS-Contributor-Fund) - Framework for selecting projects a company supports financially

## Conferences

* [LWN.net Community Calendar](https://lwn.net/Calendar/) - Calendar tracking events, such as conferences, relevant to the open source community
* [List of Free Software events](https://en.wikipedia.org/wiki/List_of_free-software_events) - Detailed list of events related to open source
* [FOSDEM](https://fosdem.org) - Biggest open source developer event in Europe, taking place each February in Brussels
* [Open Source Summit](https://en.wikipedia.org/wiki/Open_Source_Summit) - Linux Foundation's main event
* [OSCON](https://en.wikipedia.org/wiki/O%27Reilly_Open_Source_Convention) - O'Reilly's now discontinued commercial open source conference
* [Linuxtag](https://en.wikipedia.org/wiki/LinuxTag) - Now discontinued annual event which was instrumental in making open source popular

## Community

### Community Management

* [Measuring Engagement](https://docs.google.com/presentation/d/1hsJLv1ieSqtXBzd5YZusY-mB8e1VJzaeOmh8Q4VeMio/edit#slide=id.g4435d357b_20) - Study by Mozilla about how responsiveness affects contributions
* [Open Source Guides](https://opensource.guide/) - Collection of resources about how to run and contribute to an open source projects
* [The Art of Community](https://www.jonobacon.com/books/artofcommunity/) - Standard reading on community management
* [Five Pillars of Building Developer Communities at HashiCorp](https://janairis.medium.com/five-pillars-of-building-developer-communities-at-hashicorp-9c8f50198eb8) - How to build a community
* [Awesome OSS Management](https://github.com/todogroup/awesome-oss-mgmt) - List of packages and projects helpful for managing open source projects and offices
* [Open Source Guides for the Enterprise](https://www.linuxfoundation.org/resources/open-source-guides/) - Resources for running an open source program office
* [Open Source Program Offices: The Primer on Organizational Structures, Roles and Responsibilities, and Challenges](https://www.linkedin.com/pulse/open-source-program-offices-primer-organizational-roles-haddad/) - Comprehensive overview about how Open Source Program Offices work
* [TODO Group](https://todogroup.org/) - Group as forum for open source program managers
* [Open Source Management Training](https://training.linuxfoundation.org/training/fundamentals-of-professional-open-source-management) - Free online course from the Linux Foundation about managing open source programs in the enterprise
* [Open Leadership Training Series](https://mozilla.github.io/open-leadership-training-series/) - Best practices of working open
* [Producing Open Source Software](https://producingoss.com/) - Book about how to run an open source project
* [Open Source Programs Survey](https://github.com/todogroup/survey) - Survey about motivations and expectations in running open source programs in a company
* [Open Source in the Enterprise](https://aws.amazon.com/opensource/enterprise-oss-book/) - Mini-book with guidelines for enterprises how to use and create open source software
* [Seven questions to steer open source project community development](https://www.redhat.com/en/blog/seven-questions-steer-open-source-project-community-development) - Checklist with questions how to position open source projects
* [All Contributors](https://allcontributors.org/) - Specification and automation to recognize all contributors, not only code contributors
* [OpenDRI & GeoNode: A Case Study for Institutional Investments in Open Source](https://opendri.org/resource/opendri-geonode-a-case-study-for-institutional-investments-in-open-source/) - Case study how building a community around an open source project created a 200% return on investment

### Mentoring Programs

* [Google's Summer of Code](https://summerofcode.withgoogle.com/) - Large open source mentoring program organized by Google
* [Outreachy](https://www.outreachy.org/) - Mentoring program focused on supporting diversity
* [Season of KDE](https://community.kde.org/SoK) - Mentoring program for volunteers in the KDE community

### Onboarding

* [First Timers Only](https://www.firsttimersonly.com/) - Introduction how to start with open source contributions with links to projects helping with that
* [First Contributions](https://github.com/firstcontributions/first-contributions/blob/master/README.md) - Playground for learning the GitHub contribution process by doing it at an example
* [How students can get started contributing to open source software](https://opensource.com/education/16/1/how-students-get-started-open-source) - Overview of programs for students to get started with open source

### Community Metrics

* [Stackalytics](https://wiki.openstack.org/wiki/Stackalytics) - Open source tool providing contribution statistics used by OpenStack and others
* [Bitergia](https://bitergia.com/) - Open source contribution metrics
* [Open Source Contributor Index](https://opensourceindex.io/) - Statistics about the top contributing companies on GitHub

### Project quality

* [CII Best Practices Badge Program](https://bestpractices.coreinfrastructure.org) - The Linux Foundation's Core Infrastructure Initiative's self-certification program for demonstrating adherence to best open source practices
* [How you know your Free of Open Source Software Project is doomed to FAIL](https://spot.livejournal.com/308370.html) - Tom Callaway's famous post about what not to do when running an open source project
* [What does a sustainable open source project look like?](https://medium.com/libraries-io/what-does-a-sustainable-open-source-project-look-like-bf9b8cf824f8) - Criteria of what makes an open source project sustainable
* [Methodologies for measuring project health](https://nadiaeghbal.com/project-health) - What are meaningful metrics for measuring health of a project?
* [Community Health Analytics Open Source Software (CHAOSS)](https://chaoss.community/) - Project to define metrics for community health
* [Determining the True Openness of Open Source Projects](https://www.linuxfoundation.org/publications/2019/06/determining-true-openness-of-os-projects/) - Definition of areas how to make an open source project, including best and worst practices
* [How to Select Open Source Components](https://www.computer.org/csdl/magazine/co/2019/12/08909944/1f8KJAfHutG) - Selection criteria for open source components
* [Open Source Project Criticatility Score](https://github.com/ossf/criticality_score) - Project and tool to quantify criticality of open source projects
* [fosstars-rating-core](https://sap.github.io/fosstars-rating-core/) - Framework for defining ratings for open source projects
* [Open Source Insights](https://deps.dev/) - Tool to show details about dependencies of open source packages

## Development best practices

* [Semantic Versioning](https://semver.org/) - Popular release versioning scheme reflecting what kind of changes are in a release
* [Keep a changelog](https://keepachangelog.com) - Guidelines for maintaining a changelog
* [Contributing Template](https://github.com/nayafia/contributing-template) - Template for contribution guidelines
* [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/) - Comprehensive resource about how to write great commit messages
* [Conventional Commits](https://www.conventionalcommits.org/) - Conventions for writing structured commit messages which also can be read by machines
* [Code Review Developer Guide](https://google.github.io/eng-practices/review/) - Google's code review guidelines
* [How the top 100 projects on GitHub do user support](https://github.com/nayafia/user-support) - Study about how open source projects do user support
* [disclose.io](https://disclose.io/) - Standardized best practices for security issue disclosures

### Documentation

* [How to write documentation that's actually useful](https://www.hpe.com/us/en/insights/articles/how-to-write-documentation-thats-actually-useful-1707.html) - Tips how to write good documentation
* [Beautiful docs](https://github.com/PharkMillups/beautiful-docs/) - Lists of examples of great documentation and tools to generate documentation
* [Awesome README](https://github.com/matiassingers/awesome-readme) - A curated list of awesome READMEs
* [You are what you document](https://www.ybrikman.com/writing/2014/05/05/you-are-what-you-document/) - Guides and good examples for all kinds of documentation

## Marketing

* [What I learned from an old GitHub project that won 3000 starts in a weeek](https://www.freecodecamp.org/news/what-i-learned-from-an-old-github-project-that-won-3-000-stars-in-a-week-628349a5ee14/) - Case study of successfully marketing an open source project
* [afs.one](https://afs.one) - Directory of successful use of open source software

## Infrastructure

### Code Hosting

* [GitHub](https://github.com) - Largest code hosting site
* [Scaling from 2,000 to 25,000 engineers on GitHub at Microsoft](https://jeffwilcox.blog/2019/06/scaling-25k/) - Detailed report about how to scale an organization on GitHub with pointers to tools and best practices
* [GitLab](https://gitlab.com) - Code hosting site whose code is available as open source under an open core model
* [Savannah](https://savannah.gnu.org/) - Code hosting site for the GNU project and other free software projects

### Communication

* [Mailman](https://www.list.org/) - Popular open source mailing list software
* [Discourse](https://www.discourse.org/) - Open source forum software
* [IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) - The chat tool originally used by a lot of open source communities
* [Jitsi](https://jitsi.org/) - Open source video conferencing
* [BigBlueButton](https://bigbluebutton.org/) - Open source web conferencing system with a focus on online learning

## Research

* [On the abandonment and survival of open source
  projects: An empirical investigation](https://arxiv.org/pdf/1906.08058.pdf) -
  What happens when maintainers leave a project
* [Roads and Bridges: The Unseen Labor Behind Our Digital Infrastructure](https://www.fordfoundation.org/about/library/reports-and-studies/roads-and-bridges-the-unseen-labor-behind-our-digital-infrastructure/) - Extensive report about the challenges of maintaining open source as digital infrastructure
* [TheFLOSSary](https://gitlab.tubit.tu-berlin.de/mirko.boehm/TheFLOSSary) - Glossary of Free/Libre and Open Source Software related terms, reusable in LaTeX documents
* [The Hidden Benefit of Giving Back to Open Source Software](https://hbswk.hbs.edu/item/the-hidden-benefit-of-giving-back-to-open-source-software) - Report about study how contributing to open source projects allows companies to capture more value form using these projects
* [Getting Started with FLOSS Governance and Compliance
in Companies](https://dirkriehle.com/wp-content/uploads/2019/06/Getting-Started-with-FLOSS-Governance-Final.pdf) - Research about what the best practices are to introduce a governance program for commercial use of open source software
* [Socio-technical research using data excavation lab (STRUDEL)](https://cmustrudel.github.io/) - Collection of research about topics such as sustainability and diversity in open source
* [Guiding Development of Contribution and Community Strategies in Open Source Software Requirements Engineering](https://cs.lth.se/johan-linaker/doctoral-thesis/) - Research and guidance about what to share and contribute in an open source community as corporation
* [A $5 Billion Value:
Estimating the Total Development Cost
of Linux Foundation's Collaborative Projects](https://www.static.linuxfound.org/sites/main/files/lfpub_cp_cost_estimate2015.pdf) - Study about how much it would cost to develop open source projects from scratch
* [The impact of open source software and hardware on technological independence, competitiveness and innovation in the EU economy](https://digital-strategy.ec.europa.eu/en/library/study-about-impact-open-source-software-and-hardware-technological-independence-competitiveness-and) - Study about economic impact of open source in Europe

## Surveys

* [Open Source Program Survey](https://github.com/todogroup/survey) - Survey by TODO Group about open source adoption and open source programs
* [The State of Enterprise Open Source](https://www.redhat.com/en/enterprise-open-source-report/2020) - RedHat report about relevance of open source in enterprises
* [Open Source Survey](https://github.com/github/open-source-survey) - GitHub's survey about open source development

## Inner Source

[Inner Source](https://en.wikipedia.org/wiki/InnerSource) is not [Open Source](https://en.wikipedia.org/wiki/Open_source) but there is a lot of overlap, especially in terms of culture, practices, and people. That's why it's a section on this list.

* [InnerSource Commons](https://innersourcecommons.org/) - Community of practitioniers of Inner Source
* [InnerSource Commons Spring Online Summit 2020](https://www.youtube.com/playlist?list=PLCH-i0B0otNQeYBH5QvNRBDA3CMrS9lL9) - Recordings of the talks from the InnerSource Commons Conferene in spring 2020
* [Adopting InnerSource](https://innersourcecommons.org/resources/books/adoptinginnersource/) - Book with case studies about how companies are doing Inner Source
* [Europace's journey to InnerSource](https://www.slideshare.net/EnricoHartung/europaces-innersource-journey) - An example how you can do Inner Source by conducting experiments based on basic Inner Soure principles
* [The Inevitability of InnerSource](https://www.nearform.com/blog/the-inevitability-of-innersource-danese-cooper-tech-talk-video/) - Inner Source in a nutshell, explaining what it is and why it's so powerful
* [Inner Source from a Financial Compliance Perspective](https://www.youtube.com/watch?v=xYLRqUTjcpY) - Explanation of Inner Source from an economic point of view
* [InnerSource Patterns](https://patterns.innersourcecommons.org/) - Tactics of applying Inner Source methodologies in the format of common patterns

## History

* [Revolution OS](https://www.youtube.com/watch?v=jw8K460vx1c) - Documentary film about the history of free software, open source, and Linux from 2001

---

This list is licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
