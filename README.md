# CS-340-Client-Server-Development
Python dashboard application using MongoDB, PyMongo, and Dash to visualize and filter Austin Animal Center data for the Grazioso Salvare rescue organization.

# CS 340 Client/Server Development Portfolio Artifact

## Project Overview

This repository contains the completed artifacts for CS 340 Client/Server Development. The project involved developing a MongoDB database interface using Python and PyMongo, creating a reusable CRUD module, and building an interactive dashboard using the Dash framework for Grazioso Salvare, a rescue animal training organization. The dashboard allows users to filter animal shelter data, visualize animal locations on a map, and analyze breed distributions through interactive charts.

## How do you write programs that are maintainable, readable, and adaptable?

I write maintainable, readable, and adaptable programs by organizing code into reusable components, using meaningful variable and function names, adding comments where necessary, and separating functionality into logical modules. In Project One, I created a CRUD Python module that handled all database interactions. This approach allowed the dashboard developed in Project Two to access MongoDB without duplicating database connection or query logic.

The primary advantage of this design was reusability. The dashboard could call the CRUD module whenever data was needed, making the code easier to maintain and modify. If database connection information or query logic changes in the future, only the CRUD module needs to be updated rather than every application that uses it. This module could also be reused in future projects that require MongoDB connectivity, web applications, reporting tools, or automation processes.

## How do you approach a problem as a computer scientist?

When approaching a problem, I begin by analyzing the requirements and breaking the project into smaller, manageable tasks. For the Grazioso Salvare project, I first focused on creating reliable database functionality through CRUD operations. Once database access was working, I developed the dashboard components and then connected them to the database.

This project differed from many previous assignments because it required integrating multiple technologies, including MongoDB, Python, PyMongo, Dash, and data visualization tools. Rather than solving a single programming problem, I had to design a complete solution that connected the database backend with an interactive user interface.

In future projects, I would continue using this structured approach by identifying requirements, designing the database schema, creating reusable data-access modules, and then building user-facing components that interact with the data through well-defined interfaces.

## What do computer scientists do, and why does it matter?

Computer scientists solve problems by designing software systems that help organizations collect, manage, analyze, and visualize information. Their work matters because it allows businesses and organizations to make better decisions, improve efficiency, and reduce manual effort.

In this project, the dashboard helps Grazioso Salvare identify dogs that are suitable candidates for different rescue training programs. Instead of manually reviewing large amounts of shelter data, users can quickly filter records, visualize locations, and analyze breed information through an intuitive interface. This improves decision-making and allows the organization to focus more time on its rescue and training operations.

The skills demonstrated in this project—including database management, software design, data visualization, and full-stack development—are valuable because they help organizations transform raw data into meaningful information that supports their mission.

## Repository Contents

* ProjectTwoDashboard.ipynb
* CRUD_Python_Module.py
* Project Two README Documentation
* Dashboard screenshots demonstrating functionality

## Technologies Used

* Python
* MongoDB
* PyMongo
* Dash
* Plotly Express
* Dash Leaflet
* Pandas
* Jupyter Notebook
* Codio Virtual Lab

## Repository Link

https://github.com/GibbsDR/CS-340-Client-Server-Development
