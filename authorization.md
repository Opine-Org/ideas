# Authorization

### Overview

Authorization should be universally available within the system according to the concept of activity-based-authorization.

### Applications

- Guard a website or API endpoint
- Guard individual features on a webpage
- Guard content on a webpage
- Guard search results

### Implementation

- YAML activity-role association
- TAML activity-route association
- User-Role association in database
- Content activiy association in database

### Library API

- get all activities
- get all roles
- get all users-by-role
- get all routes by activity
- get all activities by role(s)
