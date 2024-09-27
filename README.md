# Kanban Implementation for Kitting Department


![Screenshot 2024-08-30 151647](https://github.com/user-attachments/assets/c0c03cf2-b904-458a-b49a-3b241271fbac)

# Overview
This project documents the Kanban System Implementation for the Kitting Department at Bosch, aimed at optimizing material flow and improving production efficiency. The primary goal of the Kanban system is to control inventory flow, minimize excess stock, and synchronize the material supply chain with production needs.

By standardizing the production process and limiting the buildup of excess inventory, this Kanban implementation increases productivity and promotes a lean production environment.

# Key Objectives
* Inventory Control: Reduce excess material buildup and ensure smooth material flow to prevent delays and inefficiencies on the production line.
* Standardization: Create standardized material handling processes to ensure a rhythmic and predictable production cycle.
* Productivity Boost: Increase production efficiency by ensuring that the right materials are available at the right time, reducing downtime and improving output.

# Kanban Implementation Process
# 1. Observation and Classification
* Current Workflow Analysis: The existing workflow was studied, and the material flow process was documented.
*Kit Types Classification: Materials used in the department were categorized into various types:
  * Hand Primer Kitting
  * OH Kitting
  * PF Kitting
  *Component Kitting
* Materials were further classified into "runners" and "exotics" based on demand to optimize supply.
# 2. Coverage Calculation
* The material coverage was calculated based on production shift hours. For example, the coverage for the Hand Primer kit was estimated for 7.25 hours of operation, ensuring that the supply meets production requirements without overstocking.
* An example calculation for Hand Primer material is as follows:
  * Target/Shift per person: 800 pcs
  * Cycle time: 34 seconds per unit
  *Minimum and Maximum Kanban levels were calculated for one shift to ensure optimal material flow.
# 3. Kanban Card Creation
* Kanban cards were developed for different kits to signal material replenishment needs. The following Kanban cards were created:
  * Hand Primer Kit: 15 Kanban cards (3 cards per shift for 5 shifts)
  * PF Kit: 8 Kanban cards
  * Component Kit: 13 Kanban cards

# Results and Achievements
* Standardization: Materials and kits were standardized for easy identification and efficient handling.
* Material Flow Optimization: Kanban cards helped streamline material replenishment, reducing delays and ensuring materials were available when needed.
* Location Identification: A supermarket system was established for material storage, ensuring easy access to required items in the production line.

# Future Improvements
* RFID Integration: Hardware for RFID will be installed to further automate and improve tracking of material flow.
* Training: Associates will be trained on the Kanban system to ensure they fully understand how to use it for efficient material management.
* Milk Run Optimization: The milk run system will be optimized to support the newly implemented Kanban process.

# Conclusion
The Kanban Implementation for the Kitting Department has already shown promising results by reducing excess inventory and improving production efficiency. With planned future enhancements like RFID tracking and staff training, this project will further optimize material handling and streamline the production process.

# Project Details
* Date: September 2019
* Company: Bosch Limited
* Department: WW7700 Kitting Department
* Authors: Pradyumna Heddur Nagendra
