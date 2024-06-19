# Student Mentoring System - Docs



## Introduction

Welcome to the Student Mentoring System (SMS) documentation.
This page is intended to serve as a reference for onboarding and completing common use-cases, as well as shedding light on design decisions where appropriate.

## Key Concepts

### Users

There are 2 broad classes of users, each with 2 privilege levels.
Students have limited access to the system, and may be granted mentor privileges.
Staff are involved in the system as supervisors, but may be granted coordinator privileges, allowing them to create groups and subjects etc.

The SMS was designed to allow students to create their own accounts. During registration, they would supply their name and email address and set a password, and also declare which course they were enrolled in from a generated list, and indicate how far they had progressed into the course.

Once enrolled, students would be responsible for submitting applications and availability, as well as logging their attendance throughout semester. Mentors are additionally responsible for setting session dates ahead of time.

> !!! note Mentors can also apply to be mentees

Staff accounts, on the other hand, are created by the course coordinator. A staff member should change their password when they log in for the first time. Having the coordinator create staff accounts is an easy means of preventing unauthorized access. Staff accounts require a name, email and password.

### Applications

Once authenticated, students can submit applications. There are 3 types of applications: applications to run a mentor group (mentor applications), applications to join a mentor group (mentee applications) and applications to become a mentor (mentorship applications).

When a mentorship application is approved by a coordinator, the student account receives mentor privileges, and can then submit mentor applications.

Once mentor applications are approved by a coordinator, that application can be used to assign mentees through group creation.

Mentee applications are deleted once the student is assigned to a group for that subject, but mentor applications remain so that other groups may be created.

### Groups

A group consists of two or more students (one mentor and up to five mentees), with a staff member assigned as a supervisor. The scope of a group is one subject, and they are expected to meet once a week for at least an hour.

Groups are created by the coordinator by pairing mentor and mentee applications. Existing groups can also have mentees added to them.

> !!! Students should act as a mentor for no more than 2 groups concurrently. Group sessions should have 5 mentees max

Mentors can see the names of mentees in their group, but mentees


## Getting Started

There are a few steps to complete before students can be paired up into groups. Students and staff will need accounts to be created, subjects will need to be entered into the database and the timeslot table needs to be populated.

> !!! These steps detail workflows for the coordinator only
