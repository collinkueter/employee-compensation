# Employee Compensation

We've launched a new company a year ago and the company is growing beyond expectations. Currently compensation is being handled through an Excel document which is getting out of control. The HR department would like a simple program to keep track of expenses.

## Assumptions

1. All employees are given an Id when they are hired
2. All employees are paid per hour
3. All employees have a hourly rate
4. Pay periods run from the first day of the month till the last day of the month, paycheck being issued the following day after the end of the month

## Phase One Requirements

As part of phase one, a simple CLI application will suffice.

### View

1. View the total number of hours for a specific employee
2. View the total number of hours per year for a specific employee
3. View the total number of hours per pay period for a specific employee

### Input

1. Input the number of hours per by pay period
2. Input correction to a previous entry

### Audit

1. All entries must have an entry date
2. All entries must have the id of the employee who made the entry
3. All corrections to an entry must retain history

### Process Period

Processing a period allows an HR employee to generate pay for a specific period. Processing a period generates a report with the following requirements

1. Year to Date (YTD) hours recorded
2. Year to Date (YTD) pay amount
3. Hours recorded per pay period
4. Pay amount per pay period

## Phase Two Requirements (Optional)

The HR department is loving the new application but would like a "pretty" interface. Another department will handle the creation of the UI but your job is to design the REST API for the web designers to consume.

### Requirements

1. Design (not implement) a RESTful style API which provides all the requirements of Phase One
2. The RESTful API should exhibit behavior consistent with at least Level 2 maturity on the [Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html)

## Sample Data

```javascript
{
  employees: [
    { id: "1a2b3c", name: "Abe Bunker", hourlyRate: 25.0 },
    { id: "1b2c3d", name: "Chad Darcy", hourlyRate: 21.25 },
    { id: "2b3c4d", name: "Ethan Franklin", hourlyRate: 19.75 },
    { id: "3d4e5f", name: "Gene Hansen", hourlyRate: 22.4 },
    { id: "4e5f6g", name: "Ian Johnson", hourlyRate: 23.99 }
  ];
}
```
