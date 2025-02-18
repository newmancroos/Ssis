### SSIS


## What is SSIS?
- A platform for ETL (Extract, Transfer and Load) operations

![image](https://github.com/user-attachments/assets/63e14d71-16dc-44a1-bce8-948ed074f46f)

## SSIS Projects
- A versioned congtainer for patammeters and packages

## SSIS Package
- A Unit of task flow execution
- A Unit of Deployment

## Control Flow

- It is the brain of package
- Decides the order of execution for all its components

## Tasks
- Indivitual units of work

## Precedence Constarints
- Direct tasks to execute in a given order 
- Defines the workflow of SSIS package

## Data Flow
- It is the heart of package
- Provides the capability to implements ETL

    <b>Source</b><br/>
      - A Component which specify the location of the source data<br/><br/>
    <b>Transformation</b><br/>
      - All changes to the data within the data pipeline<br/><br/>
    <b>Destination</b><br/>
      - A Component which specify the destination of the transformed data<br/><br/>
    <b>Variables</b><br/>
      - SSIS variables can be set to evaluate to a expression at runtime<br/><br/>
    <b>Parameters</b><br/>
      - Parameters behave cuch like variables but with few main exceptions
      - Parameters can make a package dynamic
      - Parameters can be set outside the package
      - Can be designated as values that must be passed in for the package to start
      - It is much like configurations<br/><br/>
    <b>Connection Manager</b><br/>
      - It is for current dataflow but we can convert it to Project connection manager so that we can use it in multiple packages
