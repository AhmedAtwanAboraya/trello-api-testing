# Trello API End-to-End Testing

## Overview

This project demonstrates end-to-end API testing for Trello using Postman. The workflow validates board, list, card, and checklist operations across multiple users with different access permissions.

## Tools Used

* Postman
* JavaScript for test scripts
* Trello REST API
* Git & GitHub

## Test Scenarios

### Board Management

* Create board as Ahmed
* Retrieve board details as Ahmed
* Invite Mo to the board
* Update board details as Ahmed
* Verify board access as Mo

### List Management

* Create lists as Ahmed and Mo
* Retrieve lists using both accounts
* Update lists using both accounts
* Validate shared access permissions

### Card Management

* Create cards as Ahmed and Mo
* Retrieve cards using both accounts
* Update cards using both accounts
* Validate card visibility and permissions

### Checklist Management

* Create checklists for cards
* Retrieve checklists using both accounts
* Update checklist items
* Validate checklist synchronization between users
* Delete checklists

### Cleanup

* Delete cards
* Delete board

## Key Features

* End-to-end workflow validation
* Multi-user testing scenarios
* Dynamic variable handling
* API response validation
* Authorization and permission testing
* Collection variables in Postman

## How to Run

1. Import the Postman collection.
2. Configure your collection variables.
3. Add valid Trello API credentials for both users.
4. Run the collection using the Postman Collection Runner.

## Required Collection Variables

* apiKey
* ahmedToken
* moToken
* boardId
* listId
* cardId
* checklistId
