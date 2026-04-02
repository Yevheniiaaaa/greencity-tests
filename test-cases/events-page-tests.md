# QA-1
## Verify that the sign-up form is displayed after clicking the [Create event] button for an unauthorized user
### Priority
Medium
### Preconditions:
1. User is not logged in.
2. The 'Events' page is opened.
   
| № | Step | Test data | Expected result | Execution result |
|---|------|-----------|-----------------|------------------|
| 1 | Click the [Create event] button |  | Sign-up form is displayed | Not Started |
# QA-2
## Verify that the 'Create event' page is displayed after clicking the [Create event] button for an authorized user
### Priority
Medium
### Preconditions:
1. User is logged in.
2. The 'Events' page is opened.

| № | Step | Test data | Expected result | Execution result |
|---|------|-----------|-----------------|------------------|
| 1 | Click the [Create event] button |  | The 'Create event' page is displayed | Not Started |
# QA-3
## Verify that the search field returns relevant results for valid input on the 'Events' page
### Priority
Medium
### Preconditions:
1. The 'Events' page is opened.

| № | Step | Test data | Expected result | Execution result |
|---|------|-----------|-----------------|------------------|
| 1 | Click on the search icon |  | The search field is displayed | Not Started |
| 2 | Enter a valid input in the search field | Еко | Relevant results are displayed on the page | Not Started |
# QA-4
## Verify that the search field returns no results for invalid input on the 'Events' page
### Priority
Medium
### Preconditions:
1. The 'Events' page is opened.

| № | Step | Test data | Expected result | Execution result |
|---|------|-----------|-----------------|------------------|
| 1 | Click on the search icon |  | The search field is displayed | Not Started |
| 2 | Enter an invalid input in the search field | '$$$' | 1. "We didn't find any results matching to this search" message is displayed on the page | Not Started |
