# StackOverflow
LLD Stack Overflow - https://github.com/ashishps1/awesome-low-level-design/blob/main/problems/stack-overflow.md

# Actors
* User
* System

# Use Cases
* Post/Answer/Comment on Questions
* Vote on Question and Answers
* Question can have tags
* Search on Keywords,tags or user profiles
* System should provide reputation score on interation activity.

# Entities
* User
* Question
* Answer
* Comment
* Tags
* Vote

# Classes and its relationships
* User has many Comments, Answer, Questions
* Question has many Tags, Comments, Answer, Votes
* Answer has many Comments, Votes
