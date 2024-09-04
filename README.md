# Speed Check Project

**Overview:**

The Speed Check Project is an automated system designed to monitor and enforce speed limits on highways without requiring police surveillance. The project consists of two main components:

Data Collection Points: The system includes two data collection points placed along a highway. These points record the information of vehicles as they pass through. The information collected includes the vehicle’s unique identifier and the timestamp of the data collection.

Speed Calculation and Ticket Issuance: At the second collection point, the system calculates the average speed of the vehicle by comparing the time and distance between the two points. If the calculated average speed exceeds the predefined speed limit, the system automatically generates a speeding ticket for the vehicle owner. This process eliminates the need for manual police intervention and ensures consistent enforcement of speed regulations.

**Features:**

Automated Data Collection: Efficiently gathers vehicle information at two separate points along a highway.

Speed Calculation: Computes the average speed of a vehicle based on time and distance between the collection points.

Speed Limit Enforcement: Automatically issues a speeding ticket if the vehicle’s average speed exceeds the set speed limit.

No Police Intervention Required: Operates independently of police presence, streamlining speed enforcement on highways.

**How It Works:**

First Collection Point: Records vehicle information and timestamp as it passes through.

Second Collection Point: Captures the vehicle information and timestamp again.

Speed Computation: Calculates the average speed of the vehicle using the timestamps and distance between the two points.

Ticket Generation: Compares the average speed with the speed limit. If the limit is exceeded, an automatic ticket is issued to the vehicle owner.
