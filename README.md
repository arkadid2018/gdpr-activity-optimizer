<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

Final project for the Building AI course

## Project name

GDPR activity optimizer

## Summary

A machine learning-based tool designed to analyze and classify GDPR processing activities to identify similarities and redundancies to effectively streamline processing protocols.

## Background

The main objective of this project is to develop a machine learning-based tool that can analyze and classify GDPR processing activities according to their description, purpose, legal basis, categories of personal data, processing systems/applications, categories of data subjects and recipients, source of personal data, legal obligation, and retention period. The tool should be able to identify similarities and redundancies among processing activities and suggest ways to streamline the processing protocols.

## How is it used?

The solution will be used by a team responsible for the GDPR-compliance in the municipality. Usage is by running the Python program in one of the available EDI's like IntelliJ Idea. 

## Data sources and AI methods
The project will use data from processing activities that are stored in an external graph-database application. Some attributes of the processing activity, such as description and purpose, are recorded on the node or entity of the processing activity itself, while others, such as legal basis and categories of personal data, are obtained from nodes that are linked by references to the node of the processing activity. 
I don't claim to be an expert in AI even after finishing this course. My basic knowledge suggests that these techniques might be useful:
•	Natural language processing to extract relevant information from the textual attributes of the processing activities, such as description and purpose, and convert them into structured data that can be compared and analyzed.
•	Classification algorithms like Random Forest to classify processing activities into predefined categories based on their attributes.
•	Other classification or clustering algorithms to group processing activities based on their similarities or redundancies to identify potential ways to simplify or merge them.

## Challenges

One of the biggest challenges my idea project will face is the preparation and encoding of data and the selection and optimal application of algorithms to identify similarities and redundancies among GDPR-activities.

## What next?

The next step is to produce the application user interface and automate the process for identifying similar protocols when a new processing protocol is registered or and existing one is updated.


## Acknowledgments

