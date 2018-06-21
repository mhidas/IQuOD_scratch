# IQuOD_scratch
Scratching around with the IQuOD v0.1 dataset. 
Thomas Moore - June 22, 2018 - thomas.moore@csiro.au

As an end-user who has very recently discovered the IQuOD effort I’m trying the v0.1 NC files.  

What I'm currently working on is ingesting 30 years of CTD observations at one time (about 400M obs and 1M casts), create some xarray datasets and / or pandas dataframes that make sense given the different dimensions, and write some basic tools that allow me to slice, dice, and filter by typical things like time, space, and flags. 

Basically I’m trying to interrogate the data and make a case for its use in planning our upcoming Data Analysis (DA) run.  I will eventually need to turn these big xarray datasets and/or pandas dataframes into many, many files specific for the subsequent ingest into a boutique DA system under development.

This code is specific to our compute cluster but hopefully can, as a start, aide in discussions around IQuOD file formats and related tools? 
¯\_(ツ)_/¯ 
