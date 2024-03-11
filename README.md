# belly-button-challenge
<img width="613" alt="Screenshot 2024-03-11 at 6 01 04 PM" src="https://github.com/caelwillis/belly-button-challenge/assets/146779765/f18e77f6-5201-4114-8c9b-ca0c58076ac6">

In this assignment, we are tasked with creating an interactive dashboard which will allow us to catalogue and inspect a belly button biodiversity dataset.

First we must read the JSON file containing our data. We define our source URL, and then us D3 to read the data and log it to our console. We want to allow data to be viewed according to the sample ID of the individual we are analyzing. To accomplish, a dropdown menu is created from a list appended with all sample ids in our dataset.

<img width="194" alt="Screenshot 2024-03-11 at 6 02 49 PM" src="https://github.com/caelwillis/belly-button-challenge/assets/146779765/68c5dadb-75c2-4180-86f7-252649bffd01">


Our first vizualisation of this data will be a horizontal bar chart displaying the top 10 OTUs found in each member of our dataset. We will code this chart to display the results of the first sample ID in our dataset upon launching this dashboard. Selecting sample IDs from our dropdown menu will change the data reflected in our bar chart to match that of the individual based on sample ID.

<img width="438" alt="Screenshot 2024-03-11 at 6 04 00 PM" src="https://github.com/caelwillis/belly-button-challenge/assets/146779765/78aaab96-a426-4357-8d46-1100109e2816">


The next vizualization will be a bubble chart displaying the same results as what is shown in our bar chart. This will also display initial results showing information for the first sample ID in our dataset, and will display results corresponding to the individual who's sample ID is selected from the dropdown menu.

We are then creating a box which will display the metadata key-value pairs for the selected sample ID. We now have an interface that will greatly assist in our ability to compare and draw conclusions from the data which we have been provided.
