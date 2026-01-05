# Why junction box between battery modules and BMW
Because without a junction box you’d end up with:
* lots of inline splices floating around,
* no strain relief,
* and a messy shared return splice somewhere random.

The junction box gives you one clean “transition node”


# Overall electrical safety
* we need to decide where to put the fuse - potentially in between bms voltage connector 1 and 2 (so grp 3 and 4)
* we might want to add 2 service disconnects to make the battery really safe by keeping battery voltage below 60V while working on it

* we need to add bat output relay


# Battery Pack 
## Dimensions
Height: 
* min 223mm
* max 276mm

Length:
* min 1224mm
* max 1452mm

Width: 
* min 260mm
* max 270mm

## Design
* Try to stay close to min dimensions
* Bat+ top, Bat- bottom, both feed into rail
* Service disconnect after 2 packs
* Clean intermodule electrical connection [Link](https://www.youtube.com/watch?v=fPJml5GVxwU).
* reduce from 5 to 4 modules in V1
* FR4 isolation between 2 and another layer on top for output relay and contacts level
* We stick with Formula SAE mech desin guidelines. 3.2mm alu strength bottom, remaining 2.3mm
* Elements to be integrated: BMS, Current Sensor, AIR, IMD, Precharge Resistor, TSAL (Tractive System Active Light)

