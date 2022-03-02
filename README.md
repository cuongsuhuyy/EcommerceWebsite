# EcommerceWebsite
Prepare
- Visual Studio 2019 Enterprise 2019
- Microsoft SQL 2012
- Visual Code (any version)
- Git
- Jira
- Slack - Slack app mobile

Structure
- Font-end: Angular (update version used later)
- Back-end: dotNet core (update version used later)
- Database: Sql 2012
- REST API: For comunicate with db
- API: if need more than CRUD

Flow JIRA
- When get new task:
  - Step 1: move to in progress
  - Step 2: when finish, check pull code again then create MERGE REQUEST and add Reviewer (CuongSu)
  - Step 3: move task to Review then ping slack reviewer
- If get Blocking Points
  - Move to blocking points, then ping slack channel ecommercewebsite for set up meeting discuss
- If get Pending
  - Move to pending, then assign task for persion needed. After that ping slack channel ecommercewebsite to that persion

Style create MERGE REQUEST
- [NumberTask]:Short Description about task
