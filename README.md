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
- Allways add details description when create MERGE REQUEST

C# Coding Conventions (PLEASE FIND MORE DETAIL IN DOCUMENTS BRANCH - CODING CONVENTION)

1.	Naming Convention

There are several naming conventions to consider when writing C# code.

In the following examples, any of the guidance pertaining to elements marked public is also applicable when working with protected and protected internal elements, all of which are intended to be visible to external callers.
•	Pascal case
Use pascal casing ("PascalCasing") when naming a class, record, or struct.
When naming an interface, use pascal casing in addition to prefixing the name with an I. This clearly indicates to consumers that it's an interface.
When naming public members of types, such as fields, properties, events, methods, and local functions, use pascal casing.

•	Camel case
Use camel casing ("camelCasing") when naming private or internal fields, and prefix them with
When writing method parameters, use camel casing.

2.	Commenting and Summary conventions
•	Place the comment on a separate line, not at the end of a line of code.
•	Begin comment text with an uppercase letter.
•	End comment text with a period.
•	Insert one space between the comment delimiter (//) and the comment text, as shown in the following example. 

All methods must be summarized. You just need to type /// statement on the method that needs summary then add description in summary.


Link Refer
https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions
https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/language-specification/documentation-comments



