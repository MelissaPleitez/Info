# Reasoning behind Practice-lab-1 modeling.


## Summary

Model Name: Practice-lab-1
Model Purpose: Represent things a business needs to remember in order to perform business processes, in this case represent the xtwitter's information structure that will be or had been implemented in a database.
Creation Date: 09/19/2023
Author: Melissa Pleitez

## Context

Problem Context: Adding support for the following features:
* Tweet Reply
* Bookmark
* Likes
* Quotes
* Retweets
* Followers
Justification for the Model: The definition of the Active Record Models, Migrations, Associations to create a Twitter database model.

# Model Architecture

## Diagrams

1. Entity-Relationship Diagram (ERD)

Description: We have the following tables: USERS, TWEETS, FOLLOWERS, LIKES, BOOKMARKS and REPLIES.
Your relationships:
USERS and TWEETS: They have a One-to-many relationship, since a user can have many tweets, and many tweets can belong to one user.
FOLLOWERS and USERS: They have a One-to-many relationship too, through the IDs: follower_id and followee_id, we can say that a user can have many followers and many followers can follow one user

Key Entities: [List the main entities in the ERD]
2. System Architecture Diagram
Purpose: [Explain the purpose of the system architecture diagram]
Components: [List the key components/modules depicted in the diagram]
Interactions: [Describe the interactions between components]
