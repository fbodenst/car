# HV Battery Connector 
* Current rating 350A
* HV Cable - we will go with 95mm2 - at 400A this is a good compromise vs. 120mm2. Other option would be 70mm2 (options given by the plug manufacturers)
* We go woth Amphenol connectors and A coding - A coded connectors will only mate with A coded plugs

# MSD - Manual service disconnect
* We will go with an integrated solution where the plug has a 400A integrated fuse

# Battery Box Design

## General
* Bottom plate 10mm AL, side plates 
* Side plates 4mm
* We might add a fan to the LV compartment
* We will aim for 2mm clearance on every side of a battery module and fill those gaps with foam (thermal conductive for top and bottom)
* Put padding in between mounting points of battery module and base plate - 2mm gap in CAD

## Cooling
* We will do air cooling in V1 - mostly because there will be no DC fast charging and no track load profile

## Electrical 
* We go with a 30mm x 5mm busbar internally - should be fine with the 250A cont. current from the motor and is standard for suppliers

## TODOs
* Need to think about how to stabilize middle layer
* Endplate design
* Cutout in middle section -> maybe it makes sense to do busbar design early 
* Change position of MSD to beginning of string for better integration
