# USE CASE: 1 Generate Countries Report


### Goal in Context

As an *Organization that reports on population* we want *to produce a report on the Countries of the world* too allow *for easy access to information regarding countries and their populous*

### Scope

Organization.

### Level

Important task.

### Preconditions

We know the role.  Database contains current world and population data.

### Success End Condition

A report is available for organization to provide for staff and public.

### Failed End Condition

No report is produced.

### Primary Actor

Population Information team.

### Trigger

A request for population information is sent to us.

## MAIN SUCCESS SCENARIO

1. User selects report to find individual report 
2. User inputs to receive specific report
3. Report is then captured and is used further for information analysis

## EXTENSIONS

1. **Report selection**:
    1. All the countries in the world organised by largest population to smallest.
    2. All the countries in a continent organised by largest population to smallest.
    3. All the countries in a region organised by largest population to smallest.
    
2. **User input report selection**
    1. The top N populated countries in the world where N is provided by the user.
    2. The top N populated countries in a continent where N is provided by the user.
    3. The top N populated countries in a region where N is provided by the user.
    
## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release v0.1-alpha-3
