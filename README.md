# SHACOG
## 2017 Local Government Budgets Dataset

## What is in each file / folder?
- **2017 Municipal Budgets (folder)**: Source Budget Docs
- **SHACOG Municipality Budgets 2017.xlsx**:
	- ***Budget sheet*** with aggregate figures
	- ***Census sheet*** with population and economic data

## How were the budget figures calculated?

***Each municipality had a different way of showing the breakdown of its revenues and expenditures.***  This meant I needed to create my own common standards to apply to all...

### Revenues
I decided to include ***ALL*** budgets and separate funds, not just **general fund revenues** in the data set.  I made sure to include **previous funds** left over from the previous year as well.  Here are the funds that were included:

- General
- Capital Projects 
- Capital Improvements
- Sanitary Sewer
- Highway Aid (State Funds)
- Liquid Fuels Fund
- Parking Fund
- Park Fund
- Sinking Fund
- Street Lights Fund
- Library Fund
- Community Events Fund

### Expenditures

First of all, ***interfund transfers were not considered "expenses" in this dataset***.  They were treated as such in the budget documents, but since I was adding across all funds this would have been double counting.

Expense breakdowns by category were even more complicated than revenues due to the various styles of departmental divisions!

I decided to simplify things and came up with categories based roughly on Baldwin Borough's [interactive budget viewer](baldwinboroughpa.opengov.com/transparency#/).  I also made my own minor adjustments...

**For example**: *Swimming pool* expenditures were usually listed under *recreation* but I thought it would be interesting to compare that separately.  Conversely, *Winter road maintainance* was usually listed separately, but I chose to add it to *public works* spending.

## What counted under each category?
### General Government:
- Buildings & Facilities
- Executive
- Administration
- Engineering & Inspections
- Solicitor & Legal Services
- Tax Collection
- Elected Officials
- Fiscal Agent Fees
- Financial Audits
- Finance Departments
- Legislative
- Publications
- Information Technology

### Parks & Recreation
- Parks Department
- Recreation Department
- Park Services
- Trees / Forestry
- Environmental
- Recreation Centers
- Community Centers
- Senior Citizen Centers
- Stadiums
- Tennis Courts / Golf Courses / Ice Rinks
- Fireworks
- Parades

### Police
- General Police Department
- Investigations
- Police Communications
- Traffic Enforcement
- Police Support
- DARE & Outreach Programs
- Police Vehicles & Equipment

### Public Works
- Public Works Department
- Maintenance of Roads & Bridges
- Street & Road Repairs
- Traffic Control Devices, Signals, Signs
- Street Lights
- Winter Snow / Ice Removal
- Storm Sewers & Drains
- Solid Waste Collection & Disposal
- Sewage Treatment
- Sewage Plants
- Recycling
- "Sanitary Sewer" Fund Expenditures
- Health & Sanitation
- Worker's Compensation
- Public Works Vehicles
- Equipment Maintenance

### Other
- Pension Contributions
- Insurance Payments
- Debt Servicing
- Emergency Dispatch
- Planning & Zoning
- Crossing Guards
- Animal Control
- Community Outreach
- Miscellaneous