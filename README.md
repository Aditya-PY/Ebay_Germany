# Exploring eBay Car Sales Data

This project will be using a dataset of used cars from eBay Kleinanzeigen, a classified section of the German eBay website.

The main purpose of this project is to clean data and perform simple aggregate analysis on the price and mileage of the listed cars.

The original dataset is not available anymore. It was originally scraped and uploaded to Kaggle by user [orgesleka](https://www.kaggle.com/orgesleka).
However you can find a copy of it [here](https://data.world/data-society/used-cars-data) on the data.world website.

The version of the dataset we will be working on has been modified in the following ways:

* 50,000 data points from the full dataset (out of 370,000 data points) have been sampled by dataquest.io, to ensure the code runs quickly.
* The dataset has been dirtied a bit to more closely resemble what one would expect from a scraped dataset (the version uploaded to Kaggle was cleaned to be easier to work with).


## Introduction 

The dataset include the following columns:

    dateCrawled - When this ad was first crawled. All field-values are taken from this date.
    name - Name of the car.
    seller - Whether the seller is private or a dealer.
    offerType - The type of listing
    price - The price on the ad to sell the car.
    abtest - Whether the listing is included in an A/B test.
    vehicleType - The vehicle Type.
    yearOfRegistration - The year in which the car was first registered.
    gearbox - The transmission type.
    powerPS - The power of the car in PS.
    model - The car model name.
    kilometer - How many kilometers the car has driven.
    monthOfRegistration - The month in which the car was first registered.
    fuelType - What type of fuel the car uses.
    brand - The brand of the car.
    notRepairedDamage - If the car has a damage which is not yet repaired.
    dateCreated - The date on which the eBay listing was created.
    nrOfPictures - The number of pictures in the ad.
    postalCode - The postal code for the location of the vehicle.
    lastSeenOnline - When the crawler saw this ad last online.
