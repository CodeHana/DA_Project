# EDA Course Project Introduction

## Summary

A client has come to Sophie, Kim, & Rita in desperate need of help. We are passing this task on to you, our very capable students. The client could really benefit from the data science services of a skilled practitioner like you. How can you help them reach their goals?  

> Sophie, Kim, & Rita -
>
> It was great to meet with you and chat at the event where we recently met and had a nice chat. We’d love to take some next steps to see if working together is something that would make sense for both parties.
>
> As we mentioned, we are interested in harnessing the power of data and analytics to optimize the effectiveness of our street team work, which is a significant portion of our fundraising efforts.
>
> WomenTechWomenYes (WTWY) has an annual gala at the beginning of the summer each year. As we are new and inclusive organization, we try to do double duty with the gala both to fill our event space with individuals passionate about increasing the participation of women in technology, and to concurrently build awareness and reach.
>
> To this end we place street teams at entrances to subway stations. The street teams collect email addresses and those who sign up are sent free tickets to our gala.
>
> Where we’d like to solicit your engagement is to use MTA subway data, which as I’m sure you know is available freely from the city, to help us optimize the placement of our street teams, such that we can gather the most signatures, ideally from those who will attend the gala and contribute to our cause.
>
> The ball is in your court now—do you think this is something that would be feasible for your group? From there we can explore what kind of an engagement would make sense for all of us.
>
> Best,
>
> Karrine and Dahlia
>
> WTWY International


For this project, you are going to deliver a preliminary analysis to your client. Your goal is to address their needs so that they can use data to inform their business choices.

To do this, you will take advantage of free, accessible data about the patterns of transit traffic in New York City: [MTA turnstile data](http://web.mta.info/developers/turnstile.html). Using this data source, as well as any other relevant dataset(s) of your choosing, perform an exploratory analysis in Python and SQL that offers insightful and actionable quantitative findings (including visualizations) to your client. Communicate your process and findings in a 5 minute presentation at the end of week 2 and a short written description.


## Components
Metis projects are broken down into 5 component parts -- **design, data, algorithms, tools, and communication** -- that are each scored individually. Below is a description of each component as it relates to this project. For more detail  on how these components are graded and how extra points are rewarded, refer to the [project success guide](./project_success_guide.md).  


### Design:

*  The project should include a rationale for the steps you take which address a specific need for the client organization. It should be centered around discovering useful, actionable insights that inform your client about the movement of people in the city.
*  All **deliverable deadlines should be met**, reflecting **professionalism** and **effective scoping and workflow**

### Data:

* The primary data source should be [MTA turnstile data](http://web.mta.info/developers/turnstile.html) 
* Aim to use at least 3 months worth of data; consult with an instructor if you are considering deviating from this rule of thumb, which may vary depending on your use case
* You are welcome and encouraged to incorporate any additional, relevant data sources 
 
### Algorithms

* Perform a thorough Exploratory Data Analysis of the MTA turnstile data; clean, explore, aggregate, and visualize the data as appropriate to address the client's problem 
* The MTA Analysis Pairs [1](../../pairs/mta-pair-1), [2](../../pairs/mta-pair-2), and [3](../../pairs/mta-pair-3), which we'll cover over the next few days, will help you get started with your data exploration

### Tools
* **Ingesting the raw data into a SQL database** is required. We provide two options for this:
  - The [Quick Setup](../../resources/get_mta/get_mta.md) is **highly recommended**
  - The [Manual Setup](../../resources/project_starter_code.md) is more in-depth
* **Querying from that database into Python via SQLAlchemy** is required
  - You must correctly use at least **four** of the following commands: `GROUP BY, JOIN, WHERE, HAVING, LIKE, CASE ... END, PARTITION BY, RANK ... OVER, CREATE TABLE, AND / OR / NOT, INSERT, UNION, ROW_NUMBER,` a subquery, a common table expresssion

* **Exploratory data analysis in pandas** is required
* **Python visualization libraries** (such as matplotlib and seaborn) are required   
* Other tools not covered in the course are optional but welcome
* Major examples of applicable tools not covered in the course:
  - *Processing* tools could include Google Cloud or Amazon Web Services for cloud computing resources
  - *Visualization* tools could include more advanced Python libraries such as Bokeh and Plotly or resources outside of python such as Tableau


### Communication:
* Students will deliver a **5 minute slide presentation** at the end of the course. These should be given in a compelling, 
clear manner and include effective visuals for communicating your objectives and findings.
* You will also submit a **~1 page written description** summarizing your work: it should begin with a **~100 word abstract**
to be followed by a breakdown of your project along the 5 major components.
  

## Deliverables:

**Please submit all project deliverables through the [Student Submissions Form](https://docs.google.com/forms/d/e/1FAIpQLSeM7MPx5r_FaX6ordJGkG1ObLh94GEE8qzlvEFxfvmWsKmXNA/viewform)**. All project deliverables and code should be uploaded to a personal, project-specific GitHub repository. Click [here](https://github.com/thisismetis/Metis_Fundamentals/tree/main/git_and_github) for instructions on how to set up a personal repo. 

**For exact deliverable dates, refer to the main schedule [here](/README.md).**
  
**For exact deliverable details, refer to the (linked) Metis Fundamentals project deliverable templates**.

 * [Project proposal](https://github.com/thisismetis/NBM_Metis_Fundamentals/tree/master/project_deliverable_templates/project_proposal.md): short description shared with instructors
    - Additionally, students may meet with an instructor for a scope meeting
 * [Minimum Viable Product (MVP)](https://github.com/thisismetis/NBM_Metis_Fundamentals/tree/master/project_deliverable_templates/mvp.md) submission  
 * [Written description, presentation slides PDF, and project code](https://github.com/thisismetis/NBM_Metis_Fundamentals/tree/master/project_deliverable_templates/final_deliverable.md) 
 * [Project Presentation](../../resources/Presentation%20Content.pdf). **Do not wait to start your slides.** Start with an outline, and make incremental changes to guide your story (and thereby your analysis) as you go. Also, don't forget to practice at least once with a classmate or a TA! You should have content (*at least* a slide) for each of the following:
   - Introduction (think *motivation*)
   - Methodology
   - Results
   - Conclusion (think *impact*)
 

