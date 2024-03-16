# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


## TestGuru Project Entities
The TestGuru application includes a number of core entities that represent the main functionalities and concepts of the platform. These entities are essential for the creation, management, and taking of online tests. Below is a list of these key entities:

- **User**: Represents both test creators (e.g., teachers, educators) and test takers (students, candidates). Users can have different roles and permissions within the platform.

- **Test**: Represents a set of questions on a particular topic. Each test is created by a user and can be taken by other users.

- **Question**: Represents a single question within a test, which can vary in type (e.g., multiple choice, true/false, short answer).

- **Answer**: Represents the possible answers for a question. This includes correct answers as well as distractors (wrong answers).
- **Result**: Represents the outcome of a test attempt. This includes the user's score, percentage, and any feedback.