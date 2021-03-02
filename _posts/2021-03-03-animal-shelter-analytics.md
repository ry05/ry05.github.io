---
layout: post
title: Saving Animal Lives with Data: An Introduction to Animal Shelter Analytics
image: /img/animal-shelter-analytics/icon.png
tags: [data science, data analytics, data for social good]
share-img: /img/animal-shelter-analytics/icon.png
---

It is currently estimated that there are about [5,000 independently-run animal shelters in the world](https://en.wikipedia.org/wiki/Animal_shelter). I personally feel there might be more. The efficiency of operations at these shelters depend largely on their ability to satisfy their main objective, usually to [optimize select metrics](https://www.vet.cornell.edu/hospitals/maddies-shelter-medicine-program/shelters/shelter-resources/every-nose-counts-using-metrics-animal-shelters). And in order to calculate these metrics, there is a requirement to **collect, maintain and analyze data**. 

But, how many times have we come across the use of data in animal shelters? I never did till I made the decision to approach a local animal shelter with a speculative application to be hired as a data analyst intern. The details of how I landed this opportunity has been discussed in detail in an [earlier piece](https://ry05.github.io/2020-05-30-first-data-role/). 

This article is a summarization of the different practices that could be put into action in order to help shelters function better with the help of data-driven efforts. Or as I like to call it, **Animal Shelter Analytics**. 

## What is an Animal Shelter?

The most common descriptions of animal shelters revolve around the idea of providing animals a location to stay, especially if they have been abandoned or injured. In a more basic sense, animal shelters offer rehabilitation and housing to animals in need of the same. Mostly. organizations running these establishments are not-for-profits and their operations are heavily-reliant on the donations they receive.

The first animal shelters were not exactly what one could call "animal-friendly". [Animals that were stray or "unwanted" were killed by shelters and this was normalcy](https://blogs.scientificamerican.com/dog-spies/the-history-of-science-in-animal-shelters/).However, as time passed by the sheltering system began seeing a paradigm shift towards the benefit of the living beings they were protecting. This change could even be seen in the evolution of terminology used. For example, "animal welfare" was coined, thus reflecting a more humane approach to sheltering.

Another way to look at the sheltering system is to view it as a means to "control" stray animal populations. While there is a need to protect animals, it is also an equally important requirement to ensure that human life is not hampered or endangered by an unmonitored animal population. Some examples of this outlook include the practice of sterilization of stray dogs in order to keep their numbers in check.

Often, the term animal shelter is used to refer to those shelters that accommodate domestic animals or pets such as dogs and cats. However, there are organizations like the one I worked at that work towards the conservation of urban wildlife.

> *[Urban wildlife refers to (usually) non-domesticated species that co-exist with human beings in urbanized locations](http://urbanwildlifegroup.org/urban-wildlife-information). For example, squirrels, snakes, kites etc. fall under this category*

## What Role does Data play in an Animal Shelter?

A very big role! Data is probably the most essential part of running an animal shelter. There is data to be collected about the animals, the costs of operation, the funds available etc. It is this data that could be used to [perform several important operations at a shelter including saving more lives, optimizing running costs and connecting animals with prospective donors](https://cdn.ymaws.com/theaawa.org/resource/resmgr/conferences/2018_conferences/Shelter_Data_Scarlett.pdf).

Now, let's take a step back and establish why there is even a need to incorporate data-driven practices into a shelter's operations. Firstly, data helps **validate the authenticity** of facts and figures. This in turn brings in transparency into the shelter. Given the fact that most shelters run as charitable trusts or not-for-profits, this sense of transparency lies at the apex of all needs.

The next reason why data is key is the ability of good data collection to aid in a **precise evaluation of progress**. A good shelter almost always has a strong plan about the targets it wants to achieve. In order to realize the extent to which the shelter has been successful, it needs to be able to *quantify* its contributions with objectivity.

The third reason is that data provides **well-informed plans of action**. For example, consider a case where shelter X receives 20 cranes for treatment in a space of one week. If no data is maintained about these animals, the only operations the shelter can do is try and save each of the 20 cranes. However, if there is data collected about these cranes and if it is noticed that all the cranes have been brought in from the same locality, the shelter can then send in a team to review what's going on in the locale that's causing trouble to the cranes. This is [attacking the root cause of a problem](https://www.tableau.com/learn/articles/root-cause-analysis) and is way more efficient than fixing individual outcomes of the root cause.

### The evolution of animal shelter data collection

In this fabulous [talk](https://www.youtube.com/watch?v=vB4x1KJQb_k), Kristen Hassen, Director of Maddie's Fund along with her colleagues provided a historical evaluation of software used at shelters to collect data.

As per their observations, shelter software has gone through 3 waves to be where it is currently. The first wave had software that was built to only perform the task of keeping a count of the animals. Basically, it treated animals as "inventory" and offered no support for adoptions. Naturally, we can envisage the level of primitivity such software operated with.

The second wave was better than the first wave as shelter software makers now began to recognize the importance of adoptions. Software became more centered around the concept of "life-saving". Another welcome change in shelter software during this time was that it became more user-friendly and also provided opportunity to store the animals' medical history and behavioral patterns.

The third wave i.e contemporary is focused on the community. Software helps track data forming the bridge between animals and people. Shelters' now have the power to use their data to quantify their impact and address root causes.

I have a slightly different take on the third wave. I believe that the third wave is still luxury for most animal shelters in developing countries like India. The shelter I worked for had a very dedicated, passionate team collecting data about all their animals, however they did so using spreadsheets and manual entry, thus avoiding the use of any kind of shelter software.

The third wave can also be thought of as the wave that has brought about the inclusion of *metrics* into the operations of a shelter with greater seriousness. A metric is a measure that can [quantify the status of a process](https://www.klipfolio.com/blog/kpi-metric-measure). 

In her talk titled [Magical Metrics and Dazzling Data](https://www.youtube.com/watch?v=IpKOHdr-9Pc), Dr. Janet Scarlett, Founder of the Shelter Medicine Program at Cornell University provides a perspective on how metrics can be used to improve conditions at an animal shelter, track outbreaks and monitor animal health at the shelter. 

In another talk titled [Making better use of shelter data](https://www.maddiesfund.org/making-better-use-of-shelter-data.htm?p=topic1004), Dr. Scarlett stresses on how metrics at animal shelters are often under-utilized resources and introduces the idea of estimating housing capacity using average length of stay (ALOS).

Some of the most common metrics used by animal shelters are

1. **Intake :** Number of animals coming into the shelter
2. **Outcome :** How many animals are adopted, returned, euthanized, dead, transferred?
3. **Save rate :** Percentage of animals leaving the shelter alive
4. **Live Release Rate :** (Total Live Outcomes / Total Outcomes)
5. **Length of Stay :** How long did a particular animal stay at the shelter?
6. **Shelter-specific metrics :** Decides the capacity of a shelter
   1. Number of staff
   2. Number of available cages
   3. Amount of funding available

## Towards a Theory of Animal Shelter Analytics

Now that you understand the domain of animal shelters, its time to introduce you to the concept of animal shelter analytics. This is not a universally-defined discipline, however I believe the name is appropriate based on my experience at the shelter.

### Everything data-driven starts with identifying stakeholders

The core task of a data-driven practice is to ensure that [stakeholders](https://www.thebalancesmb.com/stakeholder-2502118#:~:text="Stakeholder" refers to anyone%2C,foundations that give you grants.) involved are happy with the solution. For that, it is first important to identify the stakeholders. In an animal shelter, there are essentially 5 kinds of stakeholders as described below.

![](C:\Users\Ramshankar\Dropbox\My PC (LAPTOP-67V4712P)\Desktop\ry05.github.io\img\animal-shelter-analytics\stakeholders.png)

<center>Stakeholders at an Animal Shelter (Credits: Author)</center>

According to [Fernandes et. al](https://www.mdpi.com/2077-0472/9/6/132), there exists a growing need  to encourage collaborations among stakeholders in order to take better decisions and achieve long-lasting improvements in the sphere of animal welfare. However, to do so there must be clear, compelling narratives and points of view that resonate with each of the 5 categories of the stakeholders depicted above. 

Raw data will usually be handled at the administrative level by the shelter staff. While that is an important part of the activities of the shelters staff, it would also be helpful if they are provided with an ability to visualize the raw data and see it in terms of meaningful graphs and pictures.

The interns/trainees and volunteers will have a better idea of what is expected of them and how much they need to act upon based on the insights provided to them by the staff.

The advisory board will be able to gauge the depths of the shelter’s impact by having a look at visualizations and they will be able to do so in very quick time.

Finally, the general public is arguably the most important of all stakeholders in an animal shelter such as PFA. It is paramount importance to let the community know about the work and efforts of the shelter and to do so, the organization must communicate to the wider public through well-designed narratives.

A key reason why data-driven decision making is important is because it is **objective**. It creates quantifiable views of the shelter’s activities and hence acts like a common point for each of the concerned parties to discuss on.

### Defining animal shelter analytics

Making definitions in an academic way is not exactly one of my virtues. Hence, I shall make use of a diagram to define this idea of animal shelter analytics. The diagram is pretty self-explanatory.

![](C:\Users\Ramshankar\Dropbox\My PC (LAPTOP-67V4712P)\Desktop\ry05.github.io\img\animal-shelter-analytics\definiton.png)

<center>3 Main Components of Animal Shelter Analytics (Credits: Author)</center>

### Using animal shelter analytics

Animal shelters collect data such as information about the animal, rescue counts, locations of rescue etc. These datasets contain patterns that offer deeper insights into the shelter's operations. Domain experts and data-teams can sit together, discuss about key focus points, analyse to get insights, use metrics to quantify the progress of the shelter and even decide on new metrics to define the efficacy of a shelter and incorporate these into the shelter's practices.

The following are good broad use-cases I was able to think of where Animal Shelter Analytics can prove beneficial :

**Understanding the shelter's operation**

Details such as how many rescues, how many volunteers, the different kinds of species, adoption and donors data etc.

**Understand the vulnerability of a given species**

Details pertaining to the rescues and status of one given species

**Geographical mapping of rescue hotspots**

Geographically visualizing locations from where the most rescues of a given species occur

**Building public relations and improving community involvement**

Channelizing data analytics to plan better outreach programs and connect potential donors to injured animals

## Current Challenges in Animal Shelter Analytics

Having established an understanding of how data analytics can help shelters improve their operations, it is now time to discuss about some of the key challenges that make this idea not-so-easy to implement.

*All the challenges mentioned here were those that I faced first-hand during my internship at the shelter. Some of these could be common to other shelters too and some might not be so.*

### Challenge 1: Unsatisfactory data quality

There is no bad data, just data that is not satisfactorily collected or maintained. This is a lesson I learnt on my first day at the job. The shelter had some very impressive records of the animals it had rescued over the past 6 years, however a closer look exposed several problems with the way it was maintained.

 Firstly, there were inconsistencies with how the data was collected every year. Each year, columns were renamed or new columns were introduced; but these columns were rarely populated thus leading to the problem of missing data. These inconsistencies reflected a lack of framework when collecting animal records.

Another predominant issue was inconsistent data entry. Inconsistencies noticed in the shelter data included

1. Spelling errors : The names of the same species were given different spellings each time
2. Case errors : Uppercase and lowercase used at will
3. Scientific name confusions : Some species are given scientific names that are not the actual scientific names of the species
4. Irregular format for dates

These problems with the data cause the [quality of the data to be lower than what it should be if the organization has to make data-driven decisions](https://www.forbes.com/sites/forbesagencycouncil/2019/10/01/the-age-of-analytics-and-the-importance-of-data-quality/?sh=6f178cb65c3c). Bad quality data could cause the an upstream propagation of wrong insights which could in turn lead to bad decisions. And nobody wants that!

Cleaning all this data took me several days. Especially the part of scientific name confusions as this required me to google each species' name and check if its recorded scientific name is correct. The process of data cleaning I followed is a topic for another article!

### Challenge 2: Lack of shelter software

I don't consider myself an expert here, but most animal shelters in India are not yet operating with explicit shelter software. Spreadsheets are what these organizations use to store their data. 

Now, I am too early in my career to comment about the [spreadsheet vs other software debate](https://medium.com/@hypergiant/why-are-you-still-using-excel-fef6c3821a7b). But, one thing that I took away from my internship was that using spreadsheets to store data requires more careful consideration than when one uses software built explicitly to store data.

Software built for data collection could enforce certain standards that could be built into it, thus helping [attack poor data quality at its source](https://hbr.org/2020/02/to-improve-data-quality-start-at-the-source). While spreadsheets like [MS-Excel do allow you to use constraints](https://bettersolutions.com/excel/data-analysis/solver-add-in-constraints.htm#:~:text=Creating constraints lets you restrict,the Add Constraint dialog box.) to ensure some level of quality while entering data, the level of sophistication involved is lower than custom-built software.

### Challenge 3: Inertia to adopt data-driven culture

Again, I am no expert. But, I strongly believe that a reason why animal shelters have not adopted a data-driven culture is because it's **simply not easy to do so**. From my experience at the shelter, the work they do is phenomenal and very time consuming. Since its a not-for-profit, they are almost always crunched in terms of resources, yet manage to save so many lives every day. 

With so much going on, its [always a challenge to incorporate a new priority](https://www.europeanbusinessreview.com/3-challenges-companies-face-in-becoming-data-driven/). Moreover, there is always a question of *"Will this be worth our time?"*. It's always a bit difficult to answer this question as any answer would fail to convince the stakeholders involved unless they are willing to put some skin into the game.

## How to solve these challenges?

Identifying challenges is a relatively easy task. The real value lies in the ability to produce solutions. In the context of the three above challenges at the shelter, I made a few recommendations to the stakeholders in my final report, couple of them which I will be discussing here.

### Solution 1: Create a rulebook for data entry

The idea is to have a set of fixed, organization-specific guidelines while entering data. This will ensure a unified structure to the data and thus simplify the process of analytics later on.

### Solution 2: Initiate a data-driven culture

As described in challenge 3, this is not easy. However if a shelter can pull this off, many more lives will be saved. A few ways in which animal shelters can develop such a data-driven culture are

1. Upskill volunteers and employees to be more [data literate](https://online.hbs.edu/blog/post/data-literacy). If they know the importance of data, they will surely be more careful when dealing with it.
2. Include technical internships at the shelter where students familiar with computation and analytics can provide their services aid the shelter's operations.
3. Reach out to companies who would be willing to help with setting up databases or build [CRM software for the shelter](https://www.youtube.com/watch?v=eS-ORssgnwE) as a part of their CSR activities.
4. Maintain relevant documentation about data and collect metadata i.e data about data.
5. Ensure that everybody at the shelter is accountable to the data-driven process. Each employee must realize that any data that's a mess at time T will only get worse at time T+1 unless interrupted!

## Conclusion

There is great potential in animal shelter data to positively bring about a balance between the interactions between man and animal. Some shelters have realized this already while many more are yet to tap into the abundance of data hidden away in their spreadsheets. 

It is high time that all animal shelters adopt data-driven practices if they are to aid more animals. Having clear data-driven practices can also help the shelter gauge their progress as an organization. As Peter Drucker once famously put it, *"What gets measured, gets managed"*.  
