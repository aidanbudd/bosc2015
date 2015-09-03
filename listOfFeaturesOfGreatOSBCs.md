# List of features of great open source bioinformatics communities

- {Communicativeness} **Open transparent effective efficient respectful communication**
    - A friendly, responsive, culture of discussion
        -  **reasons why this is important for a great community of this kind**:
            - {Constructiveness} communication and discussion is the life-blood of community; it's how the interactions that make up the community happen. If this is positive and constructive, most people are encouraged by, and enjoy the interaction, and thus are more likely to do more of it
            - {Responsiveness} if the response to questions, contributions, is quick, then people are more likely to be able to keep track of discussions, feel that they are active, have them more likely to deliver useful answers/solutions, and to reach these more quickly
        - **challenges in both (a) establishing and (b) maintaining this feature in such a community**
            - {Attentiveness, Openness} enough, enthusiastic, positive people need to be listening to people comments, acknowledging their actions, and responding to them, for people to feel that they are being listened too, and to build active discussions. If you start as a small group, this is a challenge, as it requires more contirbution/time commitment from each member than when the group is larger
            - {Respectfulness, Supportiveness} once you have a larger group of contributors to discussions, it's important to actively support and promote the friendly, respectful, welcoming tone
        - **tips for both (a) establishing and (b) maintaining this feature**:
            - {Communicativeness, Practical tip} BioJS uses a "Gitter channel (https://gitter.im/biojs), which currently includes 47 members, is a public chat-room that is directly linked to our GitHub repository. Developers use the Gitter channel to announce new commits, bug fixes, patches and forks. Questions and answers about source code are posted to the room on a daily basis and, as a matter of principle, the core development team attempts to provide immediate responses on the Gitter channel." (quoted from http://elifesciences.org/content/4/e07009)

    - {Positivity} Welcoming, supportive, including (lots of?) positive interaction between experienced and new members
    - Extensive access to and communication with users
    - All people who'd enjoy being part of it know about it
    - {Purposefulness} Clear vision and mission
    - {Responsiveness} Quick responses to bug fixes/feature requests
    - {Recognition} Contributions acknowledged and rewarded
        - **reasons why this is important for a great community of this kind**:
            - Its one of the important factors that motivates members to keep on being an active contributor
            - Helps in self sustaining and increasing visibility within a community
        - **challenges in both (a) establishing and (b) maintaining this feature in such a community**:
            - In a smaller community where people are passionate about certain project and don't care about getting credits until they don't get it (address this by fixing the problem before it occurs)
        - **tips for both (a) establishing and (b) maintaining this feature**:
            - {Practical tip} A profile page for each member where the contributions can be recorded
            - {Practical tip} Motivating academics by publishing papers using models like BioJS: Professional credit. BioJS published an 'Application Note' in *Bioinformaitcs* with all contributing members as authors. BioJS has organised that application-note-type-articles are publishable in F1000 for individual BioJS modules, giving contributors an easy way of getting their contributions acknowledged within the scientific literature
            - Even a small edit/update should be mentioned: Social credits
            - {Practical tip} A common update news with the topic "Who's doing what?"
            - {Practical tip} Updates of contribution in the documents, release notes, monthly new letters
    - {Practical tip} Has a mailing or similar channel (e.g. Slack, gitter) list to keep users up-to-date about the projects they are involved in, or provides syndication feed.
    - {Purposefulness} Well designed strategy to increase its visibility to the community (use of social media, conferences etc.)
    - {Practical tip} Provides a short glossary to help users quickly understand basic things, for example, types of open-source licenses, version control systems (VCS), & other relevant components of open-source – Optional.
    - {Governance} Effective efficient decision making

- **Rich in resources (e.g. infrastructure, project leads, learning materials and help from experienced members for new members etc)**
    - {Supportiveness} Enough members who take on a mentoring role - helps keep active contributors motivated, guiding projects, avoiding conflicts etc.
    - {Diversity} Members are diverse in terms of demographics, perspectives, and experience

- **Self-sustaining/perpetuating**
    - {Accessibility, Practical tip} A self-sustaining community requires a critical mass of contributors. How do you grow to include many contributors? A key aspect is reducing the entry barriers towards contributions. Using open-source social coding tools like github for code and documentation are important. But there are many ways of doign this. Modular design of the codebase is very helpful for this (e.g. I know best: ruby gems &  bionode; CPAN and CRAN are likely similarly valid examples). As an example, shifting from "central control" of a main repository which would consider only high-quality code that fit a specific philosophy (Goto et al (2010) Bioinformatics) to a modular design where anyone could create anything was a revitalising game changer for the bioruby community. Inded, the biogems initative provided a means (template), encouragement, and active indexing of all contributions (on http://biogems.info); this rapidly and dramatically increased the number of bioruby contributors (pjotr prins may have some stats; Bonnal 2012 Bioinformatics).
    - (there may be some overlap between this section "Contributions acknowledged and rewarded" which will need to be resolved). 

- **Effective structure**
    - {Governance} Effective efficient (inspiring?) leadership
    - {Supportiveness} Project provides support and encouragement for associated sub-projects/sub-communities
    - {Accessibility, Practical tip} Offer different levels of contributions (e.g. Code contributions, documentation enhancements, User support)
    - {Governance} Organisational structure is flexible, adapted through time to respond to changing needs

- {Professionalism} **Excellent software and related infrastructure**
    - Usability
        - Understandability
        - Documentation
        - Buildability
        - Installability
        - Learnability
    - Sustainability and maintainability
        - Identity
        - Copyright
        - Licencing
        - Accessibility
        - Testability
        - Portability
        - Analysability
        - Changeability
        - Interoperability
        
The points originally under this category, it was pointed out by @mr-c, were a subset of the criteria described by the Software Sustainability Institute's ["Software Evaluation: Criteria-based Assessment"](http://software.ac.uk/sites/default/files/SSI-SoftwareEvaluationCriteria.pdf) written by Mike Jackson, Steve Crouch and Rob Baxter. Thus, I've simply added here the list of criteria from that document, reference it for more explanation of what's meant. (Note I've left out several of the features from the SSI document (Governance, Community, Supportability, Evolvability), as IMHO they're covered by features listed, in this document, in different categories than the "Excellent software and related infrastructure" here)
    

- **Supports(/enables?) reproducible research**
    - Values openness (this is implied, therefore should be a part of introduction rather than a feature; <Aidan>although, there are many aspects to openness, [to ideas, to new people, to publication, to code], perhaps it's worth having it as an extra 'feature' given that [I think] great communities of this kind also have these general, other kinds of openness as a feature...?</Aidan>)
    - Values reproducibility

- {Professionalism, Practical tip} **Endorse & actively encourage the development of high quality source code**
    - '*Adhere to the language community accepted coding styles*', and thereby ensure that the source code is readable and more accessible to a wider range of developers.
    - '*In-Line Documentation*' - the average developer should be able to understand each line of code without having to dig into the code. Thus, in-line documentation is helpful in guiding a potential contributor in understanding a section of code.
    - '*Simple Logic*' is desirable in contrast to complex one-liners that tend to take time to decode.
    - '*Continuous Integration (CI) driven development*' should be preferred. This ensures that the project works as expected under a number of different case scenarios. Moreover, if in place properly and correctly, this provides a quick test to see whether a PR should be merged. Code Linter can also be incorporated into the unit tests to ensure that the source code quality does not deteriorate over time.
    - '*Version Control*' - The type and style of versioning should be *clearly* documented. [Semantic versioning](http://semver.org) is commonly used and if so, it should be used correctly (breaking changes *must* result in a major version update). If these rules are not adhered to, this can result in breaking upstream software that depend on that code.
    - '*Change Log*' - Explain (in detail) what has been updated between minor, and more importantly, between major versions. If neccessary provide guides on how to update from previous versions.
    - '*Use easy to install dependencies*' - when developing tools for the scientific community, it is important to remember that the target market (the average biologist) will not have installed all developer packages (as a typical programmer would). And moreover, a number would find it difficult to simply install a package. Therefore, wherever possible dependencies that are easier to install should be preferred.
    - '*Root-less Installation*' should be catered for. If necessary, provide detailed documentation on how to install the software *and* dependencies without root access.
    - '*DRY*' - Follow the don't repeat yourself rule to ensure that single reponsibility is maintained throughout.


- **Misc. features of the community itself and people involved**
   - {Openness} **Open Spirit**
It's not enough to just make the source code available.  The project's key movers and shakers must genuinely be open to others peooples thoughts, suggestions, leadership and contributions.

   - {Positivity} **Have fun**
Likely as not, a lot of the time you spend working on your OS project will be in your own time.  If you're in it for the long haul, try to spend more time on the things you enjoy, than the things that must be done but which you don't enjoy. 

   - {Openness} **Open Hearted**
Be nice to people.  Likely as not they're not paid to work on the project either, and will not want to work with awkward or unpleasent people.

   - {Governance} **Make friends in high places**
Your community is more likely to thrive if it is seen to have the backing of "big beasts" including senior individuals, respected institutes or industry partners.

   -  {Attentiveness} **Seek - and then follow - advice**
This can include advice from technical experts beyond your community, political advice from senior players, as well as scientific advice to ensure the communities aims are relevant.  Importantly (at the risk of sounding daft) don't ask for advice, and then blithly ignore it.  People will (righly) assume that you are being arrogant or stupid.

   - {Transparency} **Sustainability is important**
Individuals and institutes are more likely to buy into your product if they can have some confidence it is stable, and will be supported in the long-term.  To convey stability, make sure that the origin, history and future intents are public and transparent.

   - {Supportiveness} **Make supporting others your no.1 priority**
It is always fun to cherry pick, but supporting others in their usage (of the products of your community) must always be the number 1 priority.  It is primarily they, not you, who will determine the success of the project in the long term. 

   - {Practicality} **Promise less, deliver more**
It can be difficult managing ambitions and the excitement of new ideas, especially in a community that is not bound by hard-nosed financials strictures.  Brain storm for sure, but then focus on the achievable practical things, with the bigger picture in mind.  Importantly, be seen to deliver on the things you promise.

   - {Respectfulness} **Respect the Elder Geeks**
Very often there is a small nucleus in any community who are the real driving force, and who have strong opinions and how things should be done.  They should be acknowledged and respected, as it is these individuals who are the projects powerhouse.

   - {Recognition} **Credit is infinitely divisible**
It benefits everything and harms no one to properly acknowledge the contributions of others, not many how small.  Everyone who matters will, sooner or later, realise who are the major players are, so there is nothing to lose by this.

   - {Professionalism, Transparency} **Be professional**
It might be a hobby, but that doesn't mean you shouldn't apply the same professionalism as you would apply to the day job.  Most of all, ensure that the basic stuff is done right (and that might mean announcing new releases, making change logs, making sure things don't go out broken etc.).  And be transparent about what you'd like to do, but can't because of limited resources.

   - {Communicativeness, Positivity} **Make friends and code**
Invest time and energy in cultivating positive relationships with others in the community.  The productivity and long-term success of the project depends upon it.

   - {Governance, Practical tip} **Delegate**
If you are an Elder Geek, then you should know you will never reach the end of that To-Do list.  Describe tha tasks clearly and concisely, and then try to farm them out to others.  Everyone will benefit, especially newcomes who want to contribute in a meaningful way but who might be unclear where to start.

   - {Transparency, Practical tip} **Have a nice Web site**
Advertise your community, it's mission, products, aims etc. in a nice clean Web site.  This may be the first port of call for newcomers to the project, so it should function as a staging post for getting involved.

   - {Accessibility} **Be accessible**
As a member of an existing OS community, it's easy to be blind to the barriers (and there can be many different types of barriers) to joining that community.  So be sure to document all the different ways someone can get involvded, the roles that can be played and matching these to different types of "phenotype" of community member.

   - {Purposefulness} **Have a (common) sense of purpose**
Everyone in a community will (and should) have their own agenda; it is is important to be clear about it on a personal level, but even more important to forge a common sense of purpose. Try to document, for your community, it's mission and aims - and a vision for the future - and be clear that everyone should support that vision (or help you change it). 

   - {Governance} **Roles and responsibilities**
For people to join a community in a productive way, it can help to clarify or even formalise what sort of roles can be played and what are the expectations of that role.  It is OK to demand formal responsibilities for certain roles, while other roles can be very open with no formal responsibiltiies at all.  This helps build professionalism.

   - {Governance} **Governance**
All long-lasting communities are goverened, even if this is ad-hoc defacto governance.  It may pay to to have a formal governance structure and be clear about the tiers of governance (regardless of whether there is formal management, or this is just an informal thing). In the spirit of openness, the base-level of any governance model should always be the general (scientific) public: anyone should be free to pass comment and have their voice heard (and this should be acknowledged and with a mechanims for it). 

   - {Practicality} **Meet (not too) regularly**
Momemntum is built by regular meetings, but getting the frequency right is important: respect the fact that everyone is busy.  It is better to have well attended, relatively infrequent meetings than regular meetings to which noone goes.  This goes for virtual as well as face-to-face meetings.  And aim for at least one "all hands" meeting per year - over beer!

   - {Governance, Professionalism} **Have well defined process**
How does this community go about it's business?  This vital information should be made transparent: there should be clearly documented processes for contribtuion, with sufficient (but only necessary) information: keep it simple and you'll get more contribution.

- ** List of features (i.e. annotations between {} above **
   - **Accessibility**
   - **Attentiveness**
   - **Communicativeness**
   - **Constructiveness**
   - **Diversity**
   - **Governance **
   - **Openness**
   - **Positivity**
   - **Practical tip**
   - **Practicality**
   - **Professionalism**
   - **Purposefulness**
   - **Recognition**
   - **Respectfulness**
   - **Responsiveness**
   - **Supportiveness**
   - **Transparency**
