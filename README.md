# Flight Delay Patterns

## Project Objective
Analyze and visualize flight delay patterns during peak hours.

## Group Members
- **Jaival Kansara** - ku2407u862  
- **Sameer Chauhan** - ku2407u759
- **Milap Dorawala** - ku2407u671
- **Kadiwala Kasimali** - ku2407u676
- **Mokshil Shah** - ku2407u707 

## Tools & Libraries

### Tools and Libraries Used
1. **Python**: Primary programming language used for scripting, data analysis, and visualization.

2. **Libraries**:
    - **Pandas**:
        - **Purpose**: Data manipulation and analysis.
        - **Usage**: Creating and managing a dataset (DataFrame), filtering, and sorting data to identify peak traffic hours.
        - **Installation**: `pip install pandas`
    - **Matplotlib**:
        - **Purpose**: Data visualization.
        - **Usage**: Plotting traffic data (line graph) and highlighting peak traffic hours using vertical lines.
        - **Installation**: `pip install matplotlib`

## Data Source
Data Source Details

1. Synthetic Data:

Currently, the project uses a synthetic dataset created for demonstration purposes.

This dataset simulates flight delay patterns throughout a typical day, including peak hours.



2. Using Real Data Sources:

For real-world flight delay analysis, the following data sources can be utilized:

City Airport Departments:

Publicly available datasets on flight patterns.

Examples: Open Data portals for urban planning or regional airport authorities.

### Current Dataset
- Synthetic data created for demonstration purposes.

### Using Real Data
- **Flight Data Sources**:
  - City Airport Departments (e.g., Open Data portals for urban planning).
  - Flight APIs such as:
    - Google Maps Traffic API
    - Now Flights API
  - IoT Sensors (e.g., plane status, smart sensors, or GPS devices).


## Execution Steps

1. **Install Python and Required Libraries**:
   - Ensure Python is installed on your system.
   - Install the required libraries using:
     ```bash
     pip install pandas matplotlib
     ```

2. **Save the Python Script**:
   - Copy the code provided and save it as `Airlines_Delay_Pattern.py`.

3. **Run the Script**:
   - Execute the script in your terminal or command prompt:
     ```bash
     python Airlines_Delay_Pattern.py
     ```
   - The script will generate the following outputs:
     - **Console Output**: Peak morning and evening flight delays details.
     - **Graph**: Visualization of delay patterns during the day.
     - **CSV File**: `Airlines_Delay_Pattern.py` containing the delay data.

## Summary of Results

- **Cause of Traffic**:
  - Peak hour delay is mainly due to bad weather, plane damage, cockpit issue, pilot problems, staff error etc.
  
- **Graph Visualization**:
  - The graph visualizes flight delay patterns during peak hours.
  - **Green Dashed Line**: Represents the morning peak hour (9 AM).
  - **Red Dashed Line**: Represents the evening peak hour (6 PM).



## Outputs
- **Generated Files**:
  - `Airlines_Delay_Pattern.csv`
- **Graph**:
  - A visualization showcasing the traffic trends during the day (peak hour).

## Challenges faced
- **Collection data**
- **Running code**
