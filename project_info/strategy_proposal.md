# BURGr Community Data Projects: Strategy Proposal 2017

Dear BURGr Community,

Much discussion was partaken of at the openning meeting of 2017 regarding the concept of data projects that would run during the course of the year and that could be explored by members, whether collaboratively or individually. 

## Outline

* [Overview](#overview)
* [Guidelines](#guidelines)
* [Example Project](#example)
* [Resources](#resources)

## <a name='overview'></a>Overview

The basic goal of this idea is that BURGr is a Data Science focused Meetup group with a particular focus in the use of the R programming language. As a result, it would be a natural direction to involve members in data analysis such that members can:

* freely learn from each other in a relational context (i.e. while getting to know each other)
* immediately practice the skills and ideas that they acquire from presentations and other interactions. 
    * If the community datasets serve as a suitable aid, presenters have the option (not obligation) to use them as a case study to demonstrate the ideas that they wish to convey.
    * this would have the immediate benefit of enabling users to master said concepts more easily.
* serve as a platform for users to gain exposure to datasets and techniques that they can translate, via the community projects, to their respective roles, whether industry or academic.

Essentially, these projects will serve as a "smooth beverage" with which members can enjoy their BURGr experience :smile:

## <a name='guidelines'></a>Guidelines

This proposal is that a reasonably small selection of datasets or groups of datasets be selected and ratified by the group. Selection of such a set could be via some form of voting mechanism (e.g secret ballot or online poll). Alternatively, the decision making progress can be delegated to a representative sample of the group, who would have to presumably have to rationalise such a decision.

It is recommended that, like [Kaggle](https://www.kaggle.com/), which caters for inexperienced users via its [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic) tutorial competition, the shortlist of diffferent projects of differing complexity. This would have the advantage of encouraging newer users to relish the data challenge and "pick up the BURGr" (get their hands dirty), while satisfying the appetites of more seasoned connoisseurs. Thus, catering simultaneously for members at multiple skill levels to maximise both interest and learning outcomes.

To serve the goals stated [above](#overview) the BURGr community datasets would be drawn from different domains that are conceptually accessible to all members. This would serve to maximise engagement by:

1. Broadening the audience who benefits by making the analysis more easily accessible. Members should not have to invest a lot of effort to understand the background and meaning of the dataset, but should focus on applying data science techniques to 
2. This in turn makes it easier for members to transfer group learning iutcomes to their own projects andd domains through the similarities that they observe.
3. Allows the group to simultaneously tackle different kinds of data analysys problems simultaneously, thus serving the above objectives.

* Essentially, it is recommended that the datasets be organised as <b>"projects"</b> containing one or more (read reasonable number) of _related_ data files. Further, it would be very useful (and highly advised) to suggest one (or more) goals to be pursued by adopting the dataset. Members would be free to adopt or ammend said goal, but it would give a useful guide to what the dataset(s) within the project, and what kind of techniques and learning outcomes can be achieved. Additionally, this makes it easier to select such a proposal for adoption by the group.

* Optionally, members can submit one or more <b>"question problems sets"</b> (or menus) to one or more projects to enable users to extract more value from existing project data. It is possible that question sets may involve data from different projects, however, it might be advisable to create a new project from the existing projects to serve problem sets involving multiple existing projects.

## <a name='example'></a>Example Project

The proposed project below is an example of a potential submission. The level of detail serves, therefore, as a guide but it is useful to remember to provide enough information to make the project interesting without going overboard (high indigestion probability). Linking out is a good strategy :smile:. 

### Title:
Travel Healthy (or something possibly less tacky :smile:)

### Aim:
Provide a group of datasets of moverate complexity that can be analysed individually or be combined to suitably tackle a meaningful question that involves the domain areas of:

* Respiratory health (Asthma)
* Environmental health (Air pollution)
* Transportation trends (Traffic counts)

### Background:
The datasets below pertain to the United States. A previous attempt to  obtain similar datasets from Australian "sauces" (sic) was, sadly futile and frustrating. The granularity of the sources is intended to be at the state level, since finer granularity such as city, was impossible to achieve for all three source domains. The aim of selecting this level of detail is to have a list of datasets of moderate complexity and "medium" difficulty (hopefully). These datasets can hopefully be used individually, or in concert, to tackle interesting questions.

The goal was to have datasets that have potentially interesting groups ([classification analysis](https://en.wikipedia.org/wiki/Statistical_classification) or [clustering](https://en.wikipedia.org/wiki/Cluster_analysis)) and possibly useful trends over time ([regression](https://en.wikipedia.org/wiki/Regression_analysis) or [forecasting](https://en.wikipedia.org/wiki/Forecasting)).

### Datasets:

* **Respiratory health**: [Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data](https://www.cdc.gov/asthma/brfss/default.htm)

* **Transport**: [US Federal Highway Administration (FHWA)](https://www.fhwa.dot.gov/policyinformation/travel_monitoring/tvt.cfm) (the sheets called **Page 4**, **Page 5** and **Page 6** of the _**xls**_ file hold the key raw data)

* **Environmental health**: EPA Emissions data - [Average Annual Emissions by State](https://www.epa.gov/air-emissions-inventories/air-pollutant-emissions-trends-data) is a good place to start. but other options are (note: composition not explored):

    * [Air Emissions Sources](https://www.epa.gov/air-emissions-inventories/air-emissions-sources)
    * [Pre-generated Annual Summary Data](https://aqsdr1.epa.gov/aqsweb/aqstmp/airdata/download_files.html#Annual)
    * [National Emissions Inventory (NEI)](https://www.epa.gov/air-emissions-inventories/national-emissions-inventory-nei) (Note: gaps between data years... interesting interpolation challenge?)

### Potential Questions: 

Please feel free to contribute any question problem sets to this project :smile:

1. **Relatively Simple:** What are the top 10 states or territories with the highest prevalence of adult asthma in the 18-24 age group in [2014](https://www.cdc.gov/asthma/brfss/2014/tableC3.htm)?

2. **Intermediate-ish:** In 1998 and 1999, which type of pollutant sources (tier1_description) were responsible for the highest _and_ lowest carbon monoxide (CO) emissions across the **whole** counry? ([recommended data source](https://www.epa.gov/sites/production/files/2016-12/state_tier1_90-16.xls))

3. **Intermediate-ish:** Following from question 2, which state(s) on the East coast produced the lowest quantity carbon monoxide emissions in total (i.e. from all sources) in the years mentioned?

4. **Hard-ish:** Is there any relationship between the overall asthma (either lifetime or current) prevalence in adults and the concentrations of fine particles (PM25) across the country during the period covered by both datasets.

5. **Hard-ish:** Following from question 4, is there any geographical influence (by state) on this relationship.

6. **Hard-ish:** Following from question 5, can you predict the overall asthma prevalence for the years 2015, 2016 and 2017 (optional)?

### Notes:
For the stout of heart, domains such as weather (climate), other diseases, regional demographics or other domains of interest can be used in combination with the datasets identified here. If so, please feel free to propose an ammendment to the currrent project.

Please feel free to substitute one of the sources above for a more suitable source if indigestion (frustration) sets in.

Please feel free to flag any dead links or inappropriate data sources or usage thereof. The aim is to use good quality open datasets to avoid any <u>legal</u> or other drama.

### Contributed problem sets:

To be added or linked to from here :smile:

<br/>

<br/>

## <a name="resources"></a> Resources

This section contains a very small, rather biased, selection of resources to guide members as they dine. The focus of this document is not data science resources, which can be convered in more depth elsewhere. Thus, feel free to share resources with other members, and use this small selection as a means to acquire your own resource toolkit :wink:.

* A simple R quickstart can be found at [Codeschool](http://tryr.codeschool.com/) (Benefit: no installation of R required).

* Some useful cheatsheets can be obtained from [Roger Peng](http://www.biostat.jhsph.edu/~rpeng/UCLAWorkshop/cheatsheet.pdf) and [RStudio](https://www.rstudio.com/resources/cheatsheets/)

* Potentially useful datasets are available at [Kaggle](https://www.kaggle.com/datasets), [UCI Machine Learning Repo](http://archive.ics.uci.edu/ml/), [Datahub](https://datahub.io/dataset) and [Wikipedia](https://en.wikipedia.org/wiki/List_of_datasets_for_machine_learning_research).

* For those keen on more "formal-ish" training, [introductory (but comprehensive)](https://www.coursera.org/specializations/jhu-data-science) and [more advanced](https://www.coursera.org/specializations/r) courses exist online from a variety of providers. Use what works for you, how it works for you, to get where you need to go! :smile:
