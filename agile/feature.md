# Feature

In Agile methodologies, the features represent a chunk of functionality that delivers considerable business value and fulfills a stakeholder need. Features are a collection of user stories. This is used only if you are using [Scrum](../scrum/intro.md).

>[!TIP]
> A feature is a service that fulfills a stakeholder need. Each feature includes a benefit hypothesis and acceptance criteria.

## Who writes the Features in Scrum?

As the products became more and more complex and more and more teams adopt Agile methodologies, there are indications of who defines the Features.

The Product Manager owns the Features. That doesn't mean that (s)he writes them, but has the final say on the content and prioritization of the feature.

Depending on the product and organization size, the Product Manager (the one who owns the vision of the product) and the [Product Owner](../scrum/product-owner.md) (the one who defines the [Product Backlog](../scrum/product-backlog.md) — converts the vision into actionable user stories) are the same people, while in bigger organizations they are represented by multiple people.

Some organizations use the role of **Feature Owner** instead of Product Manager to define the person is owns the responsibility of defining and making sure the feature is implemented as expected.

## Why use features in Scrum and not only user stories?

In exchange for the user stories that are small enough to fit into a sprint, the features must be big enough that they deliver a considerable benefit when rolled out to the users. We use futures to manage big product functionalities. The role of the features is in managing product development from a macro level. At the higher management level, we talk about futures.

## What's the difference between features and epics in Agile?

Think about epics as product major versions, projects, big initiatives. I like to use epics in the context of a complex program and features only on. In the end, it is a matter of how big is your product? For a product where multiple teams are working on it for several years, it might make sense to structure the product backlog on three levels of details: epics, features, user stories. But a product in which there is only one team of 8–12 people working makes more sense to simplify the administration work and have only two levels of details for the product backlog: features and user stories. The bottom line, it is a matter of need and preference.

## How big should the product features be?

A feature must be done in a maximum of 2–3 months. If you are using the Scaled Agile Framework (SAFe), they must fit in 1 Program Increment. If you are following investment funding cycles, they must fit into these cycles. The reason is that you can measure feature points velocity per program increment and for showing progress to the investors.

## What are the feature points?

It is the same as story points but at the features level. Feature points are measurement units of the complexity, effort, and knowledge involved in realizing the features.

## How to write features?

The main steps in defining features are:

Define benefit hypothesis — what will be the gain the functionality to bring to the users. It represents the "Why".

Tom as a Product Manager in ECR, noticed that multiple clients prefer to rent a car via phone instead of the website because they need someone to advise them on the car to select. This issue limits the number of clients and causes a huge overhead to the support of the team. On the other hand, Tom knows that the business he operates in is innovative and the clients need more advice. That is "Why" Tom wants the system to be able to advise clients on what car to pick depending on their needs.

As a Product Owner, you can write the following information in the WHY section of your feature. This information is very valuable in defining the solution and for the good understanding of the team of what is the final usage of the feature they will build.

### Evaluate the business value

There are multiple ways of calculating the business value from simple systems to complex ones. It is essential to consider: the number of users, the frequency of using the feature, the time criticality of releasing the feature, development effort, the return of investment.

As responsible of defining the Feature Tom deploy a short study to measure the business value that such feature could bring him. For a week, the support team asked everyone who booked a car via phone if they would book it through the website if they had personalised advice regarding their electric car needs. 68% of the clients said yes, because they’ll save time, 32% said they feel more confident talking to someone so they can learn more about the electric cars.

Tom asked the support of the marketing team to learn how much time the users spent on the description of the cars and how many of them have booked a car after.

Using these information, Tom compiles an report on how much will the new feature increase the sales online. He’s findings say that he can get up to 25% more sales in a month for the entry level offers if the clients get the right information. 10% of the Support team time. And in the same time, it will free up to He shares this information in the Feature as it is crucial for the prioritisation of the features. Tom will need to prioritise first the Features that bring the most of the benefits vs effort.

### Description

Try to share the context of the feature, how the users are going to use it. The description would focus on what the need is rather than how to implement the feature.
In our Feature — Your Electric Advice, the Product Manager share in the description the most frequent questions the Support team is getting asked by the clients who book an entry level offer. These are questions that the clients must find the answers on the website. Tom proposes a user flow that will be discussed and refined further with the team. As the team learns more about the Feature, the description evolves.

Ideally the description will contain the information that is important from Product Manager’s perspective and the technical details that the team decides — like how the scrum team will implement the feature.

### Define acceptance criteria

Knowing the conditions to mark a feature as done is crucial. They work the same way as the acceptance criteria of the user stories. The features are a way to measure the progress of product development.

When it comes to Feature Acceptance Criteria, Tom, as a Product Manager writes:

- **GIVEN** I’m a user looking for a small car to rent
- **WHEN** I’m introducing the details of my rental needs, my personal preferences and the cars that I like driving
- **THEN** I’m receiving 3 recommendations with a personalised description of why I should pick a certain car.

Tom will add multiple acceptance criteria as the one above. He also knows that for him is important that the user finds the information on the site, and it is up to the team(s) to decide how to implement a certain feature. Therefore his acceptance criteria will not be related to the "how" a certain feature will be implemented, but on the functionality.

### What are the characteristics of the features?

Features must:

- **provide business value** that can be measured in an objective way
- **be estimable**: there must be enough information for the agile team to estimate the work of implementing the feature
- **small enough** to fit into a program increment or maximum of three months as the time from “to do” to “done”, but big enough to justify the administration work involved
- **be testable**: the scrum team and the product management team must test automatically or manually the features.