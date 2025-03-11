# Project

As part of this project, you will gain practical experience in navigating ethical issues in the context of application design and development. You will also learn how to use the value-driven design toolkit to identify primary use cases, identify stakeholder groups and understand their values and value tensions. Additionally, you will learn how to apply the ACM Code of Ethics and Professional Conduct to guide the development of the system. 

## Changelog

| **Version** |   **Date**   |                            **Changes**                            |
| :---------: | :----------: | :---------------------------------------------------------------: |
|    v1.0     | Jan 6, 2025  |                    Initial version of project                     |
|    v1.1     | Jan 17, 2025 |                 Minoring formatting/link updates                  |
|    v1.2     | Jan 22, 2025 | Removed M3 turnitin submission; updated AI disclosure link for M3 |
|    v1.3     | Mar 11, 2025 |            Fixed date/day mismatch for M2/M3 deadlines            |

## Structure

This project is broken down into 3 milestones:

- Milestone 1: Value-Driven Request for Proposal
- Milestone 2: Product Requirements Document - Design and Development
- Milestone 3: Project Pitch + Presentation

Between the milestones 1 and 2, each team will be required to do a check-in with their assigned TA to ensure the project is on track.

## Schedule

|         Project Element          | Due Date (11:59pm PST) |
| :------------------------------: | :--------------------: |
|           Milestone 1            |     Friday, Feb 28     |
| Milestone 1.5 - Project Check-in |      March 17-21       |
|           Milestone 2            |    Friday, April 4     |
|           Milestone 3            |    Tuesday, April 8     |

---

<div class="accordion">

<details>
<summary><b>Milestone 1: Value-Driven Request for Proposal</b></summary>

## Milestone 1: Value-Driven Request for Proposal

In this project milestone (M1), you will learn about value-driven design and apply the approach to develop a request for proposal. 

## Scenario

The School of Computing Science at SFU, a department in a public university in BC, has historically used GPA as the only indicator for admissions into the department. With the disappearance of provincial exams, the School of CS is considering adopting an alternative system to rank promising candidates for acceptance. They are also considering the use of artificial intelligence. They issue an open request for proposals to local Canadian companies for an Admissions Management System.

You are the founders of <name your group of 4>, and you aim to bid to become the developer of this project. As part of the bid, you have been tasked to provide a report that will guide the product design and outline risks. This report will be used to determine the feasibility of the project and to guide the development of the system. The report will also be used to determine the ethical implications of the system and to ensure that the system is designed in a way that is consistent with the values of the department, university and the broader community.

## Frameworks and Guidelines

The CS department requires that you ground your proposal in following frameworks and guidelines:
- Foresight into AI Ethics (FAIE) - [Link](https://openroboethics.org/wp-content/uploads/2021/07/ORI-Foresight-into-Artificial-Intelligence-Ethics-Launch-V1.pdf)
  - This value-driven ethical design toolkit (Steps 1-6) should be used to identify the primary use cases, identify stakeholder groups and understand their values and value tensions. Through this process, you will synthesize your findings, along with the ethical risks (Step 8).

- ACM Code of Ethics and Professional Conduct - [Link](https://www.acm.org/code-of-ethics)
  - This code of ethics should be used to guide the development of the system. The department requires that you identify at least 4 principles from the ACM Code of Ethics that are relevant to the development of the system and explain how these principles will be upheld (1 principle per group member).

In addition to the frameworks and guidelines, the department requires that you:
- Conduct research on at least 4 other universities in the world and their admissions processes (1 per group member). 
  - This research should aim to identify the values that are important to these universities and how they are reflected in their admissions processes. Through this process, you will synthesize your findings and identify the values that are important to the broader community. Highlight any value tensions that may exist.

- Describe the algorithm design, the data that will be used and rationale for its selection.
  - The department is keen to understand the ethical implications of the algorithm and the data that will be used. As part of this process, your team will be required to select which data you will require from the prospective students and explain why you need this data. You will also be required to disclose how or what data will playa role in student ranking and selection. While disclosing this information, you will be required to highlight the weight of each data point and any formulas that will be used to calculate the student's ranking. 
- Some of the data that the department has suggested that you may require includes:
  - High school transcripts with:
    - grades on required courses
    - grades on non-required courses
  - Scholarship and award history
  - Name
  - Gender
  - Photo
  - Phone number
  - Birthdate
  - Social Insurance Number (SIN)
  - School district
  - School name
  - School address
  - Country of citizenship
  - Country of birth
  - English language proficiency
  - Self-reported ancestry
  - Disability status
  - Extracurricular activities
  - Essay question responses**

    - ** Note: *The department is also considering using an AI-detector for the essay questions. The AI-detector will be used to determine if the essay question responses are authentic and assign a score to the responses called "AI-score". As part of your proposal, you will be required to address how you will or will not use the AI-score for the algorithm design.*

## Report Description

You will submit a report comprising of the following major headings:
- Foresight into AI Ethics (FAIE):
  - The outcomes of Steps 1-6 and Step 8 from the value-driven ethical design toolkit. 
- ACM Code of Ethics and Professional Conduct
  - The 4 principles from the ACM Code of Ethics that are relevant to the development of the system and an explanation of how these principles will be upheld.
- Research on at least 4 other universities in the world and their admissions processes
  - The values that are important to these universities and how they are reflected in their admissions processes. Highlight any value tensions that may exist.
- Algorithm Design and Data Selection
  - The data that will be used and rationale for its selection. 
  - The ethical implications of the algorithm and the data that will be used. 
  - The data that you will require from the prospective students and explain why you need this data. 
  - How or what data will play a role in student ranking and selection?
  - The weight of each data point and any formulas that will be used to calculate the student's ranking. 
  - Address how you will or will not use the AI-score for the algorithm design.
  - Questions to consider and address while completing this section (source: [Government of Canada, Algorithmic Impact Assessment Framework](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/responsible-use-ai/algorithmic-impact-assessment.html)):
    - Will you have documented processes in place to test datasets against biases and other unexpected outcomes? This could include experience in applying frameworks, methods, guidelines or other assessment tools.
    - Will you be making this information publicly available?
    - Have you assigned accountability in your institution for the design, development, maintenance, and improvement of the system?
    - Will the system be able to produce reasons for its decisions or recommendations when required?
    - Will there be a mechanism to capture feedback by users of the system?
    - Will the system enable human override of system decisions?
    - Will there be a process in place to log the instances when overrides were performed?
    - Will you de-identify any personal information used or created by the system at any point in the lifecycle?

## Details
- You're welcome to use this opportunity to use and become familiar with LaTeX (although we won't go over this tool in this course). SFU has a paid plan that you should be able to access via [this page](https://www.overleaf.com/edu/sfu). If you optionally choose to use LaTeX, please make sure to adhere to the guidelines below. 
- The report should be 2000 words in length (+/- 10% => range: 1800-2200 words), 1.5-spaced, 12-point font, Times New Roman font, 1-inch (2.54 cm) margins. Include the word count at the end of the report (before the references section, if there is one) -- the element "Word Count: XXX" does not count towards your essay word count.
- If you (optionally) use external sources such as websites, academic papers, journals etc., then cite them using [IEEE citation format](https://www.lib.sfu.ca/help/research-assistance/subject/engineering-science/citing-writing) and include a references section at the end of the report (references are not counted towards your word count)

## Submission
- This is a group assignment for a team of 4 students, and only one submission per group is required. 
- Classmates outside of your group may read your report during a Weekly Online Activity focusing on peer reviewing. 
- Submit the report as a PDF document named:
  - Project_Group#_M1.pdf -- example: Project_Group4_M1.pdf (the group number is the number assigned to your group in the course, under "People" in Canvas. The M1 stands for Milestone 1, which you will change to M2 for Milestone 2, and M3 for Milestone 3.)

### Turnitin and Canvas
- You will be submitting the same PDF report to both canvas and turnitin
- Details to join course on [Turnitint](http://turnitin.com/)
  - Create a new account using your SFU email (or use an existing account linked to your SFU account)
  - Class ID is **46893104**
  - Enrollment key is **SunsetLand**.
- Submit the PDF to the assignment on turnitin prior the deadlines
  - Failure to submit assignment on both Canvas AND turnitin will result in a penalty.

### Turnitin Resources
- [How to set up your turnitin account](https://help.turnitin.com/feedback-studio/turnitin-website/student/account-basics/setting-up-your-account-using-an-enrollment-key.htm)
- [How to submit an assignment to turnitin](https://help.turnitin.com/feedback-studio/turnitin-website/student/submitting-a-paper/file-upload-submission.htm)


<!-- Syntax & Grammar (15%):
• Paper is free of spelling and grammatical errors
• Uses language that clearly and effectively conveys ideas
• Writes with clear sentence and paragraph structure, and appears to have been revised using the techniques described in class 

Coverage & Organization (15%):
• Report covers all the required sections, organized appropriately
• Provides a concise and engaging abstract and introduction
• Writing shows a logical flow

Research (20%):
• Shows evidence of appropriate and relevant research
• Cites all references using proper conventions 

Depth & Insight (50%):
• Provides insight into the topic in various dimensions (e.g. social, individual, economic, ethical, regulatory)
• Presents information that is coherent, organized, and connected by clear transitions
• Concludes with a clear, concise summary of the findings -->

</details>

<details>
<summary><b>Milestone 1.5: Project Check-in</b></summary>

## Milestone 1.5: Project Check-in

During this check-in, your group will have the opportunity to meet with your assigned TA and receive feedback on all the elements completed thus far. Although there are no marks associated with this check-in, your group is expected to have the following elements completed and ready to discuss with your TA:

[Canvas assignment](https://canvas.sfu.ca/courses/88206/assignments/1054202?module_item_id=3627984)

**`All group members are expected to attend this check-in, failure to do so will result in a -10% deduction from the project grade for each member who does not attend. This penalty will only be applied to the group members who do not attend the check-in.`**

</details>

<details>
<summary><b>Project Milestone 2: Product Requirements Document</b></summary>

## Project Milestone 2: Product Requirements Document

In this project milestone (M2), you will build upon the Admissions Management system from M1 where you acquired knowledge of use cases, stakeholders and risks. You will now apply your learnings to develop a Product Requirement Document (PRD), which will guide the design and development of the system.

## Scenario

The School of Computing Science at SFU has accepted your proposal and has awarded you the contract to develop the Admissions Management System. You are now required to develop a product requirements document that will guide the design and development of the system. The document will also be used to determine the feasibility of the project and to guide the development of the system. 

## Product Requirements Document (PRD)

Following initial use case and stakeholder research, you are now ready to create a product requirement document (PRD) outlining the system requirements. The PRD will be used to guide the design and development of the system. While PRDs are living documents, your goal is to create the first version of this document for your stakeholder for their approval.

The PRD should include the following sections:

1. Cover Page
   - Title of the document
   - Date
   - Name of your "company"
   - Name of your product
   - Name of the authors and student IDs
2. Table of Contents including page numbers
3. Executive Summary (typically 150-250 words)
   - A brief summary of the document, how it is organized, and what the reader can expect to find in the document 
   - A brief summary of the product, who it is for, and why it is being developed
4. Introduction
    - Background 
    - Scope of the product (outline any features that are out of scope)
    - Definitions, acronyms, and abbreviations (if any)
5. Personas, Use cases and Wireflows
    - Describe 3 personas for the system 
    - Describe use cases for each persona
      - You may use persona templates other than those provided in M1. For example, you can use [this as a resource](https://www.figma.com/resource-library/how-to-create-a-persona/)
      - *Note: You may re-use content from M1. If you do, you must add the complete text of your Milestone 1 to your Appendix and refer to it in your Milestone 2.*
    - User wireflow diagrams for the following stakeholders using tools such as Figma/Balsamiq 
      - Prospective students
      - Admissions committee
      - System administrator
    - Resources:
      - [Balsamiq: Wireflows](https://balsamiq.com/learn/articles/wireflows/)
6. Ranking Algorithm Diagram and Description
   - Visualize your algorithm design using a flowchart or similar diagrams
   - Provide a high-level description of the algorithm
   - What to include:
     - Data sources/input
     - Logical flow of the algorithm (how it processes an application to make a decision)
     - Data output
7. Application Design
    - System architecture diagram 
      - Indicating overall system components and connections between modules, inclduing your algorithm and data sources
      - Include any connections (including input/output) to external third-party systems (e.g. student information systems, databases, AI-detector services etc.)
      - You may use [this template](https://www.figma.com/community/file/989634471195357925/architecture-diagram-example-multiplayer) or similar
8. API Documentation
    - Develop a REST API documentation for your Ranking Algorithm and how it interacts with with the Admissions Management System
      - This should include what information is required to be sent to the Ranking Algorithm and what information will be returned back to the Admissions Management System
    - Outline the API endpoints/functions and what data will be sent/received including the data parameter type (e.g. JSON, XML) Each endpoint/function should have:
      - Descriptive name + description (plain text)
      - Input/output parameters + description (data type, in a table format)
      - Example request/response (code snippets)
    - REST APIs typically include the following
      
      ```code
        Request type: GET (pull data), POST (submit data), PULL (update data), DELETE (remove data)
        Base Server URL: https://ranking.[your-company-name].ca
        Endpoint: /ranking/<function>
        [Request type] [Base server URL]/[endpoint]?
          variable1:value1&
          variable2:value2&
          ...
      ```
    
    - For example, [here is Figma's documentation](https://www.figma.com/developers/api#:~:text=via%20your%20app!-,Authenticate%20users,-To%20authenticate%20any) on `Authenticate users`:
      - To authenticate any users, ask them to visit the following URL:

        ```code
        GET https://www.figma.com/oauth?
          client_id=:client_id&
          redirect_uri=:callback&
          scope=:scope&
          state=:state&
          response_type=code
        ```

        |  Parameter   |         Description         |
        | :----------: | :-------------------------: |
        |  client_id   | The client ID for your app. |
        | redirect_uri |             ...             |
        |    scope     |             ...             |  
    
    - Resources
      - [Postman: What is API documentation?](https://www.postman.com/api-platform/api-documentation/)
      - [Example: Figma API documentation](https://www.figma.com/developers/api)
      - [Example: Stripe API documentation](https://docs.stripe.com/api)
      - [Example: Spotify API documentation](https://developer.spotify.com/documentation/web-api)
      - [Example: Apple API documentation](https://developer.apple.com/)
      - [Example: Google API documentation](https://developers.google.com/docs/api/reference/rest)
      - [Example: Meta API documentation](https://developers.facebook.com/docs/)
      - [Example: Amazon API documentation](https://developer.amazon.com/docs)
      - [Example: Canvas API documentation](https://canvas.instructure.com/doc/api/)

9. Screening AI-based Essay Responses
    - Describe how the system will or will not use AI to screen essay responses
      - If you are using AI, describe how it will be used and how it will be integrated into the system (e.g. as a library package, as a third-party service, as a custom-built model, etc.)
      - If you are not using AI, describe why you are not using AI and what alternative methods you are using to achieve the same functionality (e.g. traditional algorithms, manual human processes, etc.)
    - Regardless of whether you are using AI or not, this should be reflected in your system architecture diagram 
10. Regulatory Requirements and Standards Compliance
    - Since SFU is a public university in BC, Canada, you are required to adhere to Canadian regulations and standards. As part of this section, you are required to describe how your system will adhere to:
      - [Government of Canda's PIPEDA](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/): Describe how your design meets at least 4 principles of this act 
      - AI-Usage Risk (if applicable): Describe risks associated with the AI used in your design and how what efforts your team has taken to attempt to mitigate this risk.
      - Manual human processes (if applicable): Describe risks associated with manual human processes and how what efforts your team has taken to attempt to mitigate this risk.
11. References (if applicable) 
12. Appendix
    - Changelog (if applicable)
      - In case you're changing any part of your product based on TA feedback from M1. Change log should include the version number, date of change, and a brief description of the change.
    - Full screenshot of your diagrams and wireflows (if a small version is included in the main document)
    - AI-disclosuure forms for each group member
    - Member Contributions
      - In a table format, use bullet-points to describe the contributions of each team member for each section of the document. 
      - Example:
      
      | Section | Member 1 | Member 2                | Member 3                | Member 4                |
      | :-------: | :--------: | :-----------------------: | :-----------------------: | :-----------------------: |
      | 1        | [list of contributions] | [list of contributions] | [list of contributions] | [list of contributions] |
      | 2        | [list of contributions] | [list of contributions] | [list of contributions] | [list of contributions] |
    
      - In a seperate table, describe the percentage of contribution for each team member for each section of the document. Each row should sum up to 100%. The last row of the table should include the total percentage of contribution for each team member.
      - Example:
        | Section | Member 1 | Member 2 | Member 3 | Member 4 |
        | :-----: | :------: | :------: | :------: | :------: |
        |   1     |   25%    |   25%    |   25%    |   25%    |
        |   2     |   50%    |    0%    |   35%    |   15%    |
        |   3     |   40%    |   10%    |   40%    |   10%    |
        |  ...    |   ...    |   ...    |   ...    |   ...    |
        |  Total  |   115%   |   35%    |   100%    |   50%   |
      - This information is subject to an audit by the teaching team through spot-checks and/or interviews with team members. Providing false information will result in a penalty to the group's grade.
    
## Details
- You're welcome to use this opportunity to use and become familiar with LaTeX (although we won't go over this tool in this course). SFU has a paid plan that you should be able to access via [this page](https://www.overleaf.com/edu/sfu). If you optionally choose to use LaTeX, please make sure to adhere to the guidelines below. 
- The report should be 1.5-spaced, 12-point font, Times New Roman font, 1-inch (2.54 cm) margins. Include a page number at the bottom of each page (excluding the cover page). There are no specific word count/page requirements for this milestone, but the document should be comprehensive and complete. Typically, a PRD is about 10-20 pages long, but this can vary depending on the complexity of the system. Last semester, the average length of the PRD was 15-20 pages (including diagrams and wireflows).
- If you (optionally) use external sources such as websites, academic papers, journals etc., then cite them using [IEEE citation format](https://www.lib.sfu.ca/help/research-assistance/subject/engineering-science/citing-writing) and include a references section at the end of the report (references are not counted towards your word count)

## Submission
- This is a group assignment for a team of 4 students, and only one submission per group is required. 
- Submit the report as a PDF document named:
  - Project_Group#_M2.pdf -- example: Project_Group4_M2.pdf 

### Turnitin and Canvas
- You will be submitting the same PDF report to both canvas and turnitin
- Details to join course on [Turnitint](http://turnitin.com/)
  - Create a new account using your SFU email (or use an existing account linked to your SFU account)
  - Class ID is **46893104**
  - Enrollment key is **SunsetLand**.
- Submit the PDF to the assignment on turnitin prior the deadlines
  - Failure to submit assignment on both Canvas AND turnitin will result in a penalty.

### Turnitin Resources
- [How to set up your turnitin account](https://help.turnitin.com/feedback-studio/turnitin-website/student/account-basics/setting-up-your-account-using-an-enrollment-key.htm)
- [How to submit an assignment to turnitin](https://help.turnitin.com/feedback-studio/turnitin-website/student/submitting-a-paper/file-upload-submission.htm)

</details>

<details>

<summary><b>Milestone 3: Presentation</b></summary>

## Milestone 3: Presentation

In this project milestone (M3), you will present your Admissions Management System to stakeholders of the School of Computing Science at SFU. This presentation will be used to showcase the system design and development to the stakeholders.

## Scenario

The School of Computing Science at SFU will be reviewing your Product Requirements Document (PRD) and make an approval decisions for the development of the Admissions Management System. You are now required to present the system design and development to the stakeholders. The presentation will be used to showcase the system design and development and to demonstrate how the system will meet the requirements outlined in the PRD.

## Presentation Description

The video presentation should include the following elements:
- Introduction
  - Briefly introduce the team and the scope of the project
  - Provide an overview of the presentation and what the audience can expect
- Ranking Algorithm  
  - Describe the algorithm design 
  - Walk-through the logical flow of the algorithm
- How your design meets the needs of the stakeholders 

## Details
- The presentation will submitted as pre-recorded video with subtitles
  - The use of AI tools to generate subtitles must be reported in the AI-disclosure form.
  - You are responsible for accuracy of your subtitles, regardless if you use AI or not.
- The video should be 5 minutes in length (max), no minimum length
  - A 10% penalty will applied to videos over 5 minutes
- The presentation should be engaging and informative 
- Support your presentation with visual easy-to-read slides for each section 
  - You're encouraged to be creative with your slides, but ensure they are professional and easy to read
- Each team member should have at least a 30 second speaking role in the presentation
- Make sure to practice your presentation multiple times before the actual presentation
  - Ensure transitions between speakers are smooth and that the presentation flows well

## AI-Disclosure 
- AI-usage for this submission is permissible, however all prompts and details must be disclosed and submitted as per course AI-policy.
  - Everyone will have to disclose this regardless if they use AI or not.
  - [Link to AI-usage Disclosure form](https://parsa-rajabi.github.io/CMPT-376/#/ai-policy?id=disclosure-form)
  - Failure to submit this form will be considered a violation of AI course policy and a 25% penalty will be applied to your grade.
- If you're planning to use AI, I recommend keeping track of all your prompts and results in a separate (google, word, etc.) document for ease when you're submitting the form. 

## Submission
- This is a group assignment for a team of 4 students, and only one submission per group is required.
- A link to the video presentation should be included on the first slide of the presentation
  - Should you choose to so, you can upload it to YouTube and set the [visibility to unlisted or public](https://support.google.com/youtube/answer/157177)
  - If you choose not to use YouTube, then you can upload your video to your personal google drive and/or your [SFU oneDrive](https://sfu.teamdynamix.com/TDClient/255/ITServices/KB/ArticleDet?ID=3820#sign_in)
  - Regardless of which option you choose, you must verify that your link works. You can do so by accessing the link in an incognito browser
  - Video links that are not accessible or do not work will receive a 25% penalty.
  - If you have any concerns about privacy, please reach out to the teaching team for alternative submission options.
- Submit the presentation slides as a PDF document named:
  - Project_Group#_M3.pdf -- example: Project_Group4_M3.pdf

### Turnitin and Canvas
- No turnitin submission is required for this milestone.

</details>


<details>

<summary><b>Group Project Expectations</b></summary>


## Group Project Expectations

This group project is intended for collaborative teamwork. Each member is expected to:

- **Communicate Regularly**: Stay in touch with fellow members.
- **Attend Meetings**: Ensure presence and attention at all group gatherings.
- **Maintain Professionalism**: Always be respectful and courteous to others.
- **Deliver Quality Work**: Complete tasks on time and to the best capability.
- **Seek and Offer Assistance**: Aid team members and ask for help when needed.
- **Foster Inclusivity**: Create an environment where everyone can voice their opinions.
- **Be Receptive**: Welcome feedback, constructive criticism, and be adaptable.
- **Promote Equal Contribution**: Ensure everyone participates equally in the project.
- **Stay Accountable**: Own up to one's actions and tasks.
- **Engage Actively**: Participate fully in all discussions and activities.
- **Update Regularly**: Inform the team about progress and challenges.
- **Decide Collectively**: Prioritize team decisions over individual ones.
- **Uphold Transparency**: Be honest and clear about all matters.

### Group Project Participation Policy

**Objective**: To ensure equitable contribution in collaborative group tasks and to address non-participation issues effectively.

#### Step 0: Peer Resolution

- **Criteria for Engagement**: Before official intervention, group members are encouraged to address and resolve any perceived non-participation issues internally within the group.
  
- **Evidence Requirement**: If proceeding to the next step, written evidence of attempts to resolve the conflict (such as meeting notes, email correspondence, or other relevant communication) will be required. This evidence serves to demonstrate that the group has made genuine attempts to address the issue before seeking official intervention.

#### Strike 1: Non-participation Initial Consultation

- **Criteria for Identification**: A student may be identified for non-participation if, after attempts at peer resolution, a majority of the group members, supported by the observations of the assigned TA, express continued concerns about the student's contribution levels.

- **Procedure**: The identified student will be required to attend a consultation with the assigned TA and the course instructor.

##### Consultation Outline:

1. Review of specific concerns raised by peers and discussion of the evidence from Step 0.
2. Solicitation of the student's perspective and reasons for observed non-participation.
3. Development of an action plan to rectify non-contribution.
4. Reinforcement of the academic importance of equitable teamwork and responsibility.

- **Record Keeping**: The TA will document the proceedings of the consultation, and this record will be made available to the student and preserved for future reference.

#### Strike 2: Non-participation Individual Project Transition

- **Criteria for Identification**: If, subsequent to the initial consultation, the student is again identified by a majority of their peers (with TA observations in consideration) for inadequate contribution, they will receive a second notification.

##### Procedure:

1. The student will transition from the group project to an independent project. The student will be required to complete an individual project that is comparable in scope and complexity to the group project. The student is expected to complete the individual project within the same time frame as the group project.

- **Notification**: The course instructor will formally communicate the transition and its reasoning to the student in written form, delineating both the rationale and the expectations for the independent project.

##### Additional Notes:

- Open communication with peers and teaching team is crucial. Engaging in early dialogue can mitigate issues effectively.
- In cases of extenuating circumstances, such as significant health or personal challenges, discretion in the application of this policy will rest with the course instructor and department.
- Guidance on effective collaboration and group dynamics will be provided at the outset of the project to establish clear participation expectations.

</details>


</div>
