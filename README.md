# ppeoptimizationtool

In response to the COVID-19 pandemic, states are providing cities and counties the needed Personal Protective Equipment (PPE) to distribute among healthcare and other facilities within each jurisdiction. These central distribution facilities are tasked with assigning allocations of boxes of each equipment to the needed facilities. However, these boxes come packed with varying amounts of the specific equipment that don't necessarily lend well to allocating the exact amount for each facility. Public Health managers would like to have a solution that quickly optimizes for the following:
1. Each facility gets some % of their allocation (ideally 50-75%)
2. Minimize the deviation from allocation assignment

Current State:
Piloted an Excel-based optimization tool using Linear Programming via Solver with a sample scenario for a subset of equipment and facilities. Tool takes manual input for the variables - box amounts, number of boxes with each amount, and assigned allocation for each facility. It's a fast solution that will meet the need for a small set of users, but it does not provide the right scaleable solution that can be introduced to manage allocation for all types of equipment for numerous facilities. 

Future State:
Create a simple tool as a MVP that consolidates all needed inputs from the user, applies a base optimization algorithm, and displays the box/item allocation for all facilities. The tool should be able to handle varying amounts of data (not big data) and quickly generate results to enable each Public Health manager. Other items on the roadmap post-MVP can include automatic ingestion of data from Inventory Management systems and more rigorous optimization algorithms. 

Using the PPE Allocation Optimization tool, Public Health managers within various jurisdictions in WA (and hopefully nationally) can efficiently work to ensure the right amount of the right equipment is reaching front-line health care workers.
