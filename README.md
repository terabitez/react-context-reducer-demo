# React context with React reducer demo

This is simple data explorer project to demonstrates the use of React context and reducer to pull data from server and display according to filter parameters.

## Setup

To get started, install the dependencies with `npm install`.

Run the application with `npm start`.

Launch application in browser at [http://localhost:3000](http://localhost:3000).

## Specification


The data is a list of application records and is fetchable at `/data`. Each application has 3 levels of business capabilities. Business capabilities are hierarchical as shown in the image (Business capability 1 -> Business capability 2 -> Business capability 3)

The app will:

- Requests the dataset.
- Build a hierarchical navigation tree displaying the different levels of business capabilities. 
- Have a range slider to be able to further filter the dataset based on the total spending value
- Present a list of applications from the data set, showing name and total spend. The list depends on the navigation tree and the range filter

