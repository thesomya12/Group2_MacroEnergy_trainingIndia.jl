# 5 zone, electricity-only example with 1 planning period, based (loosely) on the India grid

This is a simple example of a fize-zone model with electricity-only generation and load. It is loosely based on the India grid. It is intended to demonstrate the basic structure of a macro case repository, using five locations, connected by electricity transmission lines, allowing a range of electricity generation types, and allowing a selection of build rates. All assets have been modified from the "off-the-shelf" asset selection available in the downloadable "multisector_three_zones_reduced" example case. This example case was selected due to its use of reduced asset format compatible with translation to csv files (advisable as regions and assets expand).

# Disclaimer
Thermal generating assets for coal, biomass and diesel have been modified from the natural gas asset, and only the emissions parameter has been roughly adjusted to relect the input commodity. All other asset parameters need adjusting not just for Inida, but also for a plant operating on that commodity.

All commodity and resource availabilities and prices are either reflective of the regions the off-the-shelf assets were orginally contructed for (north-east coast USA), or for new thermal generating plants, copied from the input/parameter/cost files for another technology.

# Activity
Select the "base" version of one asset and re-paramterize its inputs (capacity, availability, costs), technology specs (fuel intake, efficiences, etc), and outputs (co2, electricity, etc) to be appropriate for the regions and infrastructure located in India in a selected base year. Rerun the model with your changes and visualize the outputs. The Tableau twb file in the viz_info folder will automatically read in and re-display results from the results folder. As long as location and asset instance names are not changes, the Tableau file will automatically display all results in the pre-determined format using a free version of Tableau reader, or a licensed version of Tableau. If changes are made to locations of assets or instance names, the a licensed version of Tableau or another viewing platform will be needed in order to view full results.  

##Markdown syntax guide: https://www.markdownguide.org/basic-syntax/

# Change documented  

## Asset Chosen:

## Aspect altered:

## Resources accessed to make alteration:

## Parameters/Inputs modified:
1. A
2. B
3. C

## Verified how?

## Verified with run of Macro?
Y/N
Details

## Limitations/Cautions/Further work needed
1. A
2. B
3. C
