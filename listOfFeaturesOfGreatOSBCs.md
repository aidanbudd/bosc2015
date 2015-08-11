# List of features of great open source bioinformatics communities

- **Open transparent effective efficient respectful communication**
    - A friendly, responsive, culture of discussion
        -  **reasons why this is important for a great community of this kind**:
            - communication and discussion is the life-blood of community; it's how the interactions that make up the community happen. If this is positive and constructive, most people are encouraged by, and enjoy the interaction, and thus are more likely to do more of it
            - if the response to questions, contributions, is quick, then people are more likely to be able to keep track of discussions, feel that they are active, have them more likely to deliver useful answers/solutions, and to reach these more quickly
        - **challenges in both (a) establishing and (b) maintaining this feature in such a community**
            - enough, enthusiastic, positive people need to be listening to people comments, acknowledging their actions, and responding to them, for people to feel that they are being listened too, and to build active discussions. If you start as a small group, this is a challenge, as it requires more contirbution/time commitment from each member than when the group is larger
            - once you have a larger group of contributors to discussions, it's important to actively support and promote the friendly, respectful, welcoming tone
        - **tips for both (a) establishing and (b) maintaining this feature**:
            - BioJS uses a "Gitter channel (https://gitter.im/biojs), which currently includes 47 members, is a public chat-room that is directly linked to our GitHub repository. Developers use the Gitter channel to announce new commits, bug fixes, patches and forks. Questions and answers about source code are posted to the room on a daily basis and, as a matter of principle, the core development team attempts to provide immediate responses on the Gitter channel." (quoted from http://elifesciences.org/content/4/e07009)

    - Welcoming, supportive, including (lots of?) positive interaction between experienced and new members
    - Extensive access to and communication with users
    - All people who'd enjoy being part of it know about it
    - Clear vision and mission
    - Quick responses to bug fixes/feature requests
    - Contributions acknowledged and rewarded
        - **reasons why this is important for a great community of this kind**:
            - Its one of the important factors that motivates members to keep on being an active contributor
            - Helps in self sustaining and increasing visibility within a community
        - **challenges in both (a) establishing and (b) maintaining this feature in such a community**:
            - In a smaller community where people are passionate about certain project and don't care about getting credits until they don't get it (address this by fixing the problem before it occurs)
        - **tips for both (a) establishing and (b) maintaining this feature**:
            - A profile page for each member where the contributions can be recorded
            - Motivating academics by publishing papers using models like BioJS: Professional credit. BioJS published an 'Application Note' in *Bioinformaitcs* with all contributing members as authors. BioJS has organised that application-note-type-articles are publishable in F1000 for individual BioJS modules, giving contributors an easy way of getting their contributions acknowledged within the scientific literature
            - Even a small edit/update should be mentioned: Social credits
            - A common update news with the topic "Who's doing what?"
            - Updates of contribution in the documents, release notes, monthly new letters
    - Has a mailing list to keep users up-to-date about the projects they are involved in, or provides syndication feed.
    - Well designed strategy to increase its visibility to the community (use of social media, conferences etc.)
    - Provides a short glossary to help users quickly understand basic things, for example, types of open-source licenses, version control systems (VCS), & other relevant components of open-source – Optional.
    - Effective efficient decision making

- **Rich in resources (e.g. infrastructure, project leads, learning materials and help from experienced members for new members etc)**
    - Enough members who take on a mentoring role - helps keep active contributors motivated, guiding projects, avoiding conflicts etc.
    - Members are diverse in terms of demographics, perspectives, and experience

- **Self-sustaining/perpetuating**
    - A self-sustaining community requires a critical mass of contributors. How do you grow to include many contributors? A key aspect is reducing the entry barriers towards contributions. Using open-source social coding tools like github for code and documentation are important. But there are many ways of doign this. Modular design of the codebase is very helpful for this (e.g. I know best: ruby gems &  bionode; CPAN and CRAN are likely similarly valid examples). As an example, shifting from "central control" of a main repository which would consider only high-quality code that fit a specific philosophy (Goto et al (2010) Bioinformatics) to a modular design where anyone could create anything was a revitalising game changer for the bioruby community. Inded, the biogems initative provided a means (template), encouragement, and active indexing of all contributions (on http://biogems.info); this rapidly and dramatically increased the number of bioruby contributors (pjotr prins may have some stats; Bonnal 2012 Bioinformatics).
    - (there may be some overlap between this section "Contributions acknowledged and rewarded" which will need to be resolved). 

- **Effective structure**
    - Effective efficient (inspiring?) leadership
    - Project provides support and encouragement for associated sub-projects/sub-communities
    - Offer different levels of contributions (e.g. Code contributions, documentation enhancements, User support)
    - Organisational structure is flexible, adapted through time to respond to changing needs

- **Excellent software and related infrastructure**
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

- **Endorse & actively encourage the development of high quality source code**
    - '*Adhere to the language community accepted coding styles*', and thereby ensure that the source code is readable and more accessible to a wider range of developers.
    - '*In-Line Documentation*' - the average developer should be able to understand each line of code without having to dig into the code. Thus, in-line documentation is helpful in guiding a potential contributor in understanding a section of code.
    - '*Simple Logic*' is desirable in contrast to complex one-liners that tend to take time to decode.
    - '*Continuous Integration (CI) driven development*' should be preferred. This ensures that the project works as expected under a number of different case scenarios. Moreover, if in place properly and correctly, this provides a quick test to see whether a PR should be merged. Code Linter can also be incorporated into the unit tests to ensure that the source code quality does not deteriorate over time.
    - '*Version Control*' - The type and style of versioning should be *clearly* documented. [Semantic versioning](http://semver.org) is commonly used and if so, it should be used correctly (breaking changes *must* result in a major version update). If these rules are not adhered to, this can result in breaking upstream software that depend on that code.
    - '*Change Log*' - Explain (in detail) what has been updated between minor, and more importantly, between major versions. If neccessary provide guides on how to update from previous versions.
    - '*Use easy to install dependencies*' - when developing tools for the scientific community, it is important to remember that the target market (the average biologist) will not have installed all developer packages (as a typical programmer would). And moreover, a number would find it difficult to simply install a package. Therefore, wherever possible dependencies that are easier to install should be preferred.
    - '*Root-less Installation*' should be catered for. If necessary, provide detailed documentation on how to install the software *and* dependencies without root access.
    - '*DRY*' - Follow the don't repeat yourself rule to ensure that single reponsibility is maintained throughout.
