# RoRo_VoluntaryShift

Dataset of instances for the numerical experiments

Meaning of the txt title:

Instance set _ No. of instance _ Ship size _ Number of transportation orders _ Type of OD pairs

For example: "S1_1_Small_10_Uniform" refers to the first instance in set S1. It is configured with a small-sized ship, 10 transportation orders, and the uniform-distributed O-D type.

Meanings of each item in txt:

DeckNum: The total number of decks in the ship

MaxLength_each_deck: The maximal length of each deck (in metres)

SideLength_each_deck: The length for the port/starboard side of each deck (in metres)

MaxWidth_each_deck: The total breadth of each deck (in metres)

BowWidth_each_deck: The breadth for the bow side of each deck (in metres)

LaneNum_each_deck: The total number of lanes arranged on each deck

OrderNum_total: The total number of transportation orders

VehicleNum_total: The total number of transported vehicles in all groups

VehicleNum_each_order: The number of vehicles in each order

VehicleLength_each_order: The length of a vehicle in each order (in metres)

VehicleWidth_each_order: The width of a vehicle in each order (in metres)

Origin_each_order: The origin port of each order

Destination_each_order: The destination port of each order

PortNum_total: The total number of ports in the sailing route

PortNum_supply_region: The number of ports in the supply region
