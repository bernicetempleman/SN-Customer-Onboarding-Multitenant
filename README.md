# Customer-Onboarding-Multitenant
The Customer Onboarding project includes the entire details for the fresh customer to get onboarded on the multi-tenant instance including Domain, Company, Department, Locations, Users, Groups, Roles, Categorization, Resolution details, & SLA using Import Sets and Transform Maps. It also includes separate Requirement Design documents as per the industry best standards. Leverages Import Sets and Transform Map.

Per Domain
    10 departments
    10 cost centers
    5 business units
    10 locations
    20 users
    5 groups
    2 members minimum per group
    user roles 15 users with roles, minimum
    10 SLA's - Response and Resolution
    cmdb_ci_win_server - 5 items
    cmdb_ci_linux_server - 5 items
    cmdb_ci_unix_server - 5 items
    Oracle / SQL (cmdb_ci_database) - 10 items / 5 Oracle / 5 SQL

## Technologies Used
- IT Service Management
- IT Infrastructure Library
- ServiceNow'JavaScript

## Features

List of features ready and TODOs for future development
- Onboaed new customers (Domain, Company, Department, Locations, Users, Groups, Roles, Categorization, Resolution details, & SLA
- Customer's data will be domain separated
- create custom SLAs and schedules based on customer's requirements.

To-do list:
- Create additional customer experiences based on the customer's needs and requirements.

## Getting Started

- Create a FRS document based on customer requirements
 ![image](https://user-images.githubusercontent.com/12488769/144729693-7010503f-9439-46ae-9f80-b942c186f87a.png)

- Create a new instance 
![image](https://user-images.githubusercontent.com/12488769/144729743-4b475a63-fb75-40cc-b32c-c4d3cc204c3c.png)

- Activate the domain separation plugin: 
![image](https://user-images.githubusercontent.com/12488769/144729789-ed7929d3-8167-439b-aa71-f602d25f2b39.png)

- Create users with admin role 

- Create parent domain and child domains
![image](https://user-images.githubusercontent.com/12488769/144729853-fa6474dc-832c-4a00-8098-ebc3eb4c79a8.png)

- Create a company for each domain
![image](https://user-images.githubusercontent.com/12488769/144729888-948fe27a-e890-4ce7-94fd-06d7f6291c75.png)

- Add the domain picker and select domain
![image](https://user-images.githubusercontent.com/12488769/144729906-32113c5e-c29a-4dc9-b7b7-32886a0d53db.png)

- Create and select an update set
![image](https://user-images.githubusercontent.com/12488769/144729929-dcf6684d-4cf9-4c8a-b3b8-62409fa83883.png)

- Create an Excel file with customer data separated (tables separated into sdifferent sheets)
 ![image](https://user-images.githubusercontent.com/12488769/144729955-49f0d056-67ab-4c5f-9d61-2feb66f19afb.png)
 
 - For each sheet, load the data, create a transform map (Set Coalesce and Choice action),
 and transform data
![image](https://user-images.githubusercontent.com/12488769/144729981-3fec241b-0034-4104-ba0c-6900aa869560.png)

![image](https://user-images.githubusercontent.com/12488769/144730004-2f86ad40-a1d3-487d-99a5-765eab7c0ed8.png)

![image](https://user-images.githubusercontent.com/12488769/144730015-de497928-e17c-49b4-bfdb-ef70e9e2b954.png)

![image](https://user-images.githubusercontent.com/12488769/144730036-6842c4d1-f584-443d-8a79-20b4f7b68140.png)

 - verify the imported data was successful and in the correct domain
![image](https://user-images.githubusercontent.com/12488769/144730091-72fdf348-3cca-4db9-891c-2e86d58239ee.png)

![image](https://user-images.githubusercontent.com/12488769/144730127-8b459e55-fc23-4c91-ad2f-d31941f09bdc.png)

 - Create schedules and holiday schedule per requirements
![image](https://user-images.githubusercontent.com/12488769/144730188-f25d5758-992f-4a7c-b1af-7b46e1685d98.png)

![image](https://user-images.githubusercontent.com/12488769/144730226-020cf096-b2f0-4073-9b0a-313be86cc672.png)

 - Create SLAs (override SLA so the customer does not have multiple SLAs)
![image](https://user-images.githubusercontent.com/12488769/144730301-3111a98f-c5b5-4fc1-981c-6757ba98dddf.png)

 - Complete the update set
![image](https://user-images.githubusercontent.com/12488769/144730252-7999bf21-50aa-474f-b33d-8c2f090d96c1.png)



## Usage
Admin role would set up new customer. After the new customer is onboarded, their users can access ServiceNow.

## Contributors
Here list the people who have contributed to this project. 
- Bernice Templeman
- Phillip Caruthers
- Samuel Hagadorn
- Malykai Mejia

## License
This site was built using [GitHub](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links).

This project uses the following license: [license_name](https://github.com/bernicetempleman/PROJECT-NAME).
