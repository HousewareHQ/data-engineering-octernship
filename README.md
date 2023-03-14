## Houseware

### Company information 

Houseware's vision is to empower the next generation of knowledge workers by putting the data warehouse in their hands, in the language they speak. Houseware is purpose-built for the Data Cloud’s untouched creators, empowering internal apps across organizations. 

### Why participate in an Octernship with Houseware

Houseware is changing the way the data warehouse is leveraged, and we want you to help build Houseware! Our team came together to answer the singular question, "how can we flip the value of the data warehouse to the ones who really need it, to the ones who drive decisions". 

In this role, you'll have the opportunity to work as a Data engineer with the Houseware team on multiple customer-facing projects. You'd be involved with delivering the data platform for the end user, while taking complete ownership of engineering challenges - this would include communicating with the stakeholders, setting the right expectations, and ensuring top quality for the code & the product being shipped.

### Octernship role description

We're looking for data engineers to join the Houseware team. 

We are hell-bent on building a forward-looking product, something that constantly pushes us to think by first principles and question assumptions, building a team that is agile in adapting and ever curious. While fast-paced execution is one of the prerequisites in this role, equally important is the ability to pause and take stock of where product/engineering is heading from a long-term perspective. Your initiative is another thing that we would expect to shine through here, as you continuously navigate through ambiguous waters while working with vigor on open-ended questions - all to solve problems for and empathize with the end users.

| Octernship info  | Timelines and Stipend |
| ------------- | ------------- |
| Assignment Deadline  | 26 March 2023  |
| Octernship Duration  | 3-6 Months  |
| Monthly Stipend  | $600 USD  |

### Recommended qualifications

- You have a solid problem-solving framework.
- You are well-versed with the Modern Data Stack, and have worked with Cloud Data Warehouses before
- You have prior experience writing backend systems, and are proficient in SQL/dbt.

### Eligibility

To participate, you must be:

* A [verified student](https://education.github.com/discount_requests/pack_application) on Global Campus

* 18 years or older

* Active contributor on GitHub (monthly)

# Assignment

## Segment users on DuckMart!

### Task instructions

You have been given a task to segment the user audience for a fictional online service called "DuckMart". You have to design and implement a backend service that allows for segmenting the user audience based on user attributes and user events.

As part of this activity, you'll have to do the following
- Dummy data generation: Create dummy data using tools like Mockaroo
- Data transformation: Write a Python script to transform the data from the CSV files into a format suitable for loading into the database.
- Data loading: You are required to load the transformed data into DuckDB

Database Schema: The following are the requirements for the database schema:

- User Attributes: User ID, Name, Age, Gender, Location, Signup Date, Subscription Plan, Device Type.
- User Events: User ID, Event Name, Timestamp.

A few examples of events are "PURCHASE_MADE" or "ADDED_TO_CART".

Query Requirements: The following are the requirements for the queries:

- Segment users by age groups: Create a segment of users in the age range 25-34 years and list out the user IDs of all such users.
- Segment users by location and events: Create a segment of users whose location="California" and have logged in to the product at least once(event_name='LOGIN') and list out the User IDs of all such users.

You are then required to write out a backend API endpoint that can scale to any kind of "Segmentation usecase" like the two examples mentioned above. Building on top of the mentioned data schema(Users, Events), the consumer of this API should be able to specify the segmentation criteria in a JSON-like format and the backend API should be able to convert it into the relevant SQL. Please specify what the spec for the JSON-like payload looks like.

### Task Expectations

You will be evaluated based on the following criteria:
- Correctness and completeness of the implementation.
- The JSON spec that powers the "Segmentation API"
- Performance and scalability of the implementation.
- Quality of the SQL queries and their optimization.
- Quality of the code and documentation.
- Ability to explain and justify design decisions.

### Task submission

Students are expected to use the [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) when working on their project. 

1. Please push your final code changes to your main branch
2. Please add your instructions/assumptions/any other remarks in the beginning of the Readme file and the reviewers will take a look
3. The PR created called Feedback will be used for sharing any feedback/asking questions by the reviewers, please make sure you do not close the Feedback PR.
4. The assignment will be automatically submitted on the "Assignment Deadline" date -- you don't need to do anything apart from what is mentioned above.
5. Using GitHub Issues to ask any relevant questions regarding the project


