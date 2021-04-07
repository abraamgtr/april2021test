# Task: Body weight logging

# Background
MacrosFirst is an app where users log the foods they eat each day and measure their macronutrient consumption. Most users are measuring their macros to achieve a body weight goal; either gaining, losing, or maintaining their body weight. In this ticket we will add the ability for users to log their bodyweight.

## This ticket
Please build an interface where users are able to:
1. Log a new body weight entry.
    + The body weight entry creation screen should contain a Save button and two inputs (both of which are required in order to save):
        * Date, using a date picker where default value is today.
            - Forbid users from logging >1 entry for the same date.
        * Weight, allowing for numerical inputs only.
1. View a scrollable table containing all logged body weight entries. The table should be sorted by date, descending, and display two columns:
    + Date
    + Weight

    As the user logs a new weight entry, this table should grow with the addition of the new row.
1. [Bonus Points] Edit a previously recorded body weight entry by tapping on its row in the table. Editing should allow:
    * Modifying the date
    * Modifying the weight
    * Deleting the entry

## Example Design
![alt text](https://github.com/macrosfirst/april2021test/raw/main/example.png "Example")