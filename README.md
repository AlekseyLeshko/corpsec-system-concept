# corpsec-system-concept

## Idea
I would like to get experience in system design.
I will resolve the fictional problem.

## Business task
We want a system where a client can manage all their company info.
Some company changes must have a document for this change. For example: if a client wants to up company paid-up capital then our system can do this task with all paperwork. The client must get it with minimum documents, questions and headaches.

## Goal
I have a solution architecture for this business task.
The solution's architecture is the core mechanism for this issue expressed as models and services in the code.
I have test cases for validation product requirements.

## Assumptions
- I don't pick a language. Just a plain TS
- I don't choose and design an infrastructure and data centre works. I have ultimate and magical AWS. It can do everything.


## First step: questions for stakeholders
I - I
S - stakeholders

I: Do we only work with existing companies?
S: No, We should create a new company for our clients.

I: What is the difference between an existing company and not existing?
S: The main difference is a not existing company can change their data as a client wants.

I: Do we have any limits for a not existing company?
S: Yes, we have. if a not registered company has a corporate charter then our system must create documents for changing a paid-up capital, shares, etc.

I: What countries do we work in?
S: For example, in the SG. However, you thinking about the whole world.

I: Do you know country based requirements?
S: Currently, no anyways we are totally sure each country has them.

I: As I know, sometimes regions or states have special rules and laws. Should we consider them?
S: Right now, no. In future, of course, yes.

I: Do we have operation specialists?
S: Yes, we have.

I: What tasks are they doing now?
S: They collect company data, like principal activities, shareholders, a website, etc.
