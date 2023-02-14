# WhenWeMet
[//]: # "Heading is subject to change."
[//]: # "Contributors: Dhyey Patel, Nachiket Dighe, Nehang Patel, Saumick Pradhan, Tharun Ravi Kumar"

Have you ever found a need for an event planner for wedding? Was it really expensive to hire an event planner? Worry not, this repository consists of a software that helps you create the perfect wedding plan that fits your budget and time availabilty!

## Vision

#### Describe the top-level objectives, differentiators, target customers, and scope of your product.
* Our team is designing a dynamic software to recommend an optimal wedding plan using in-house machine learning methods. It will use a ML model to distribute the budget as per the user preferences and suggest a wedding plan with possible venues, caterers, cake bakeries, musicians, etc.
* The customer demographic for our software includes all the people who are looking to get married and for an event planner.
* The primary scope for this project is to target the audience within the Greater Cincinnati area.

#### What is your product (high-level view)?
* In this project, the user would be asked to input the budget of the wedding, time availabilty for the wedding, and preferences on events (such as prioritize venue and catering service).
* Our software would calculate and distribute the budget to give an optimal wedding plan to the user; this will have recommendations for venues, caterers, musicians, etc.
* This would not be as expensive as hiring an event planner, as we would ask for one time fee. It also would give a wedding plan quicker.

[//]: # "One time fee or Monthly subscription"

#### Whom is it for?
* The target audience are people that are interested to have a wedding in Cincinnati.

#### What problem does it solve?
* Hiring an event planner could often times become too expensive.
* Hiring an event planner is also time consuming.

[//]: # "Add your comments above!"

#### What alternatives are available, who are your competitors?
* Event Planners such as Zola, The Knot, WrightPlace Wright Event, etc.
* Event Planner Softwares like Hubilo, slido, eventsquid, etc.

#### What is novel in your approach, that is why is this project compelling and worth developing?
* We are applying ML methodologies to recommend as per user preferences and the budgets. It doesn't require an user to do extra work of hiring an event planner, talking through what they prefer.

## Software Architecture

#### Make it clear that the system can be built, making good use of the available resources and technology.
* We will need to generate a dataset of all the service providers in the chosen local region. Then we will generate recommendations based on a pretrained model using the data we collected. We will use Google Cloud Platform to store our datasets and embeddings. For the first iteration, we want to have a smaller text corpus. Our product will have a web interface and will be hosted on UC homepages server.  

#### Describe at a very high level the system's architecture, identifying the components/modules that will interact.
* The datasets created will have the search categories (eg. venues, caterers, cake bakeries, musicians, etc.) mapped with the costing options. After prepreocessing the dataset, we will train our model on this corpus. The model will be trained and embeddings will be saved on GCP. The user will enter their budget weights for each categories and our model will recommend options for each category based on that. 

#### Describe the specific data you will access/store.
* We will be storing data related to the different types of wedding “attributes” that people can potentially opt for based on their desired budget. We will include information about the available venues, caterers, event management services, decorators, etc., which people can choose from based on what their budget is. We would provide all these services (listed in varying prices) and people will be able to choose from them, according to their liking.

#### What languages/toolkits do you intend to use for the development?
* UI Tools (html, css, js), VS code, ML model, etc.

## Challenges and Risks
#### What is the single most serious challenge you see in developing the product on schedule?
* One of the main challenges we would face if we developed the product on time is the UI and AWS development, because for a wedding planner website, we would need to ensure that the UI is appealing to the viewers/users, as well as collect information on the various weddings and build API's for using that information and connecting it both front and backend of the software.'

#### How will you minimize or mitigate the risk?

[//]: # "Needs to be worked on!"
