# Page 1

## Introdution

Describe your home's location and general overview.

## Emergency contacts

| Item/Service  | Provider | Phone | Section |
| ------------- | -------- | ----- | ------- |
| Electricity | | | [Electricity distributor](#electricity-distributor) |
| Electrician | | | |
| Fire  |  Emergency Services  | 000 | |
| Internet | | | [Internet retailer](#internet-retailer) |
| Locksmith | | | |
| Plumber | | | |
| Storm and flood | State Emergency Service | 132 500 | |
| Water and sewer | | | [Water and sewer supplier](#water-and-sewer-supplier) |


# Page 2

## External connections diagram

Diagram of property with outline of buildings and important connection points. For example:
- Electricity:
  - Meter box.
  - Point of connection (from pole or underground service).
  - Main circuit breakers.
  - BESS location and circuit breakers.
  - Solar PV inverters.
- Water:
  - Water meter and shutoff.
  - Garden water main shutoff.
  - Sewer inspection outlet and access points.
- Property access points (driveways, gates).
- Home entry points.


# Page 3

## Table of contents

Provide a table of contents.

## Glossary

Table describing terms used in your home manual.

| Term | Description |
| ---- | ----------- |
| AC | Air Conditioning |
| GPO | General Power Outlet |
| HVAC | Heating, Ventilation, and Air Conditioning |
| HW | Hot Water |
| IO | Inspection Outlet |
| LAN | Local Area Network |
| PV | Photo-voltaic solar system |
| TBC | To Be Confirmed |
| WAN | Wide Area Network (aka Internet) |


# Energy
## General

Overview of your home's energy supply: services (electricity supply, BESS, solar PV systems). Our home only uses electricity (we removed the fossil methane supply in 2017), so I only documented that.

## Electricity distributor

Table with details of our electricity network (wholesale) distributor - who to call in an outage.

| Item | Details |
| -- | -- |
| Provider | *name*, *url*, *phone* |
| Emergency phone | |
| Connection location | *attachment point to home* |
| Service type | *E.g., 240V single phase, 63A* |
| Meter location | |
| Internal sub-board location | |
| National Metering Identifier | |
| Meter 1 - consumption | |
| Meter 2 - solar1 | |

## Electricity retailer

| Item | Details |
| -- | -- |
| Provider | *name*, *url*, *phone* |
| Emergency phone | |
| Account # | |
| Customer # | |
| Password entry | |

## Electricity circuits

Description of the various circuits' purposes and circuit breaker locations.
The convention I used was to number each circuit in the meter boxes and use those numbers elsewhere in the manual.

## Electricity outside diagram

Similar to [External connections diagram](#external-connections-diagram), with details of all the external electrical services, connections, etc.

This includes:
- Electricity meters.
- Battery energy storage system.
- External appliances (e.g., hot water service and HVAC), and their circuit breakers.
- Solar systems, inverters, circuit breakers.
 
## Electricity inside diagram

Location of each GPO (power point) and hard-wired appliance (such as cooktop, hot-water, oven), and which circuit they're on.
Add notes for special cases (e.g., GPO inside a cupboard, switches for a hard-wired appliance co-located in a GPO, etc.)

## Lights inside diagram

Similar to [Electricity inside diagram](#electricity-inside-diagram).

Location of each light fixture and its switch, and which circuit they're on. I also documented exhaust fans that are co-located with lights (share a switch or switch panel).

The convention I used to was to use a letter group for each collection of lights/fans and their switches. E.g. A switch labeled "A:1" means switch for light fixture A on circuit 1, and its light fixture was labeled "A".

## Smoke alarms

Description of smoke alarm(s) location, battery replacement interval, and any other relevant notes. 

## Solar PV system

Description of solar PV systems: external panel locations, inverter details, supplier details, and any other relevant notes.

| Item | Details |
| -- | -- |
| Inverter model |  |
| Inverter location | |
| Inverter capacity | |
| Inverter serial number | |
| Inverter warranty expiry | |
| Panel model and count |  |
| Panel location | |
| Panel capacity | |
| Panel warranty expiry | |
| Installation date | |
| Supplier | |


# Garage
## General

Overview of your garage (if any).

Subsections describing any relevant information such as:
- Roller door motor
- Remote monitoring


# Garden
## General

Overview of garden (if any), including watering system.

## Watering system

Description of watering system, including:
- controller
- zones
- cabling colour
- valve and solenoid locations

## Garden diagram

Similar to [External connections diagram](#external-connections-diagram), with details of the garden and watering system.


# Heating and cooling
## General

Overview of the heating and cooling systems, (double) glazing, insulation, etc.

## HVAC system

| Item | Details |
| -- | -- |
| Outdoor model |  |
| Outdoor location | |
| Outdoor serial number | |
| Indoor model | |
| Indoor location | |
| Indoor serial number | |
| Controller model | |
| Controller location | |
| Installation date | |
| Warranty expiry | |
| Supplier | |


# Internet of Things (IoT)
## General

Overview of your IoT setup (if any).

## *Per IoT technology*

| Item | Details |
| -- | -- |
| Model |  |
| Location | |
| Serial number | |
| MAC address (LAN) | |
| [Network port](#network-ports-diagram) | |
| [Network connection](#network-connections-diagram) | |
| Installation date | |
| Warranty expiry | |
| Supplier | |
| Phone application | |
| Password entry | |

## IoT diagram

Similar to [Electricity inside diagram](#electricity-inside-diagram).

I use a convention of a different colour scheme per IoT technology.


# Locks
## General

Overview of the locks and keys in the house.


# Network and internet
## General

Overview of the local area network (LAN) and internet connection.

## Internet retailer

| Item | Details |
| -- | -- |
| Provider | *name*, *url*, *phone* |
| Emergency phone | |
| Account # | |
| Customer # | |
| Modem model | |
| Modem location | |
| Password entry | |

## Network ports diagram

Similar to [Electricity inside diagram](#electricity-inside-diagram).

## Network connections diagram

Logical network design, from internet to all devices.

Details for each device could include:
- Logical name.
- Model.
- IP address(es), including WAN (internet) addresses
- [Network port](#network-ports-diagram).

I use a convention that labels a network connection with which device port is connected to which network port.


# Water and sewer
## General

Overview of your water and sewer setup.

## Water and sewer supplier

| Item | Details |
| -- | -- |
| Provider | *name*, *url*, *phone* |
| Emergency phone | |
| Account # | |
| Customer # | |
| Password entry | |

## Hot water service

| Item | Details |
| -- | -- |
| Model |  |
| Location | |
| Serial number | |
| Installation date | |
| Warranty expiry | |
| Supplier | |

## Toilets

I found it useful to document emergency water shutoff procedure for the toilets.

Our toilets also have soft-closing seats which occasionally need re-aligning to function correctly, and I documented the procedure that I determined for this.

## Water and sewer diagram

Similar to [External connections diagram](#external-connections-diagram), with details of the water and sewer connections.

Document the location of the underground water supply, sewer pipes and access pits, and storm water drains and access pits, even if only an approximation.


# Appliances

Document each appliance, especially those "hard-wired".

## *Per appliance*

| Item | Details |
| -- | -- |
| Description |  |
| Model |  |
| Location | |
| Serial number | |
| Installation date | |
| Warranty expiry | |
| Manufacturer contact | |
| Supplier | |
| Service contact | |
