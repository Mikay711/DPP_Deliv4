# Deliverable 4: Aggregation and Output Formatting

This repository contains code and aggregated outputs for Deliverable 4, demonstrating data aggregation and saving outputs in multiple formats. The datasets used are:
- **Spotify Most Streamed Songs 2023**

## Structure
- `Deliv_4.Rmd`: RMarkdown file used to generate the HTML version of the aggregation process.
- `Deliv_4.html`: [View the HTML version of the code](https://mikay711.github.io/DPP_Deliv4/Deliv_4.html).
- `finalOutput/`: Folder containing all processed outputs in **CSV**, **RDS**, and **Parquet** formats.

## Aggregation Summary
1. **One Group, One Function, One Input Variable**:
   - **Grouping Variable**: `stream_category`
   - **Function**: Mean of `energy_scaled`
   - **Output**: `output111` (e.g., mean energy for each stream category).

2. **Two Groups, Two Functions, One Input Variable**:
   - **Grouping Variables**: `stream_category`, `key`
   - **Functions**: Mean of `danceability_scaled`, Sum of `energy_scaled`
   - **Output**: `output221` (e.g., danceability and energy statistics by stream category and key).

3. **One Group, Two Input Variables, Different Functions**:
   - **Grouping Variable**: `stream_category`
   - **Functions**:
     - Median of `danceability_scaled`
     - Standard deviation of `energy_scaled`
   - **Output**: `output122` (e.g., danceability median and energy variability by stream category).

## How to Use
1. View the processing and aggregation steps in `Deliv_4.html`.
2. Access the processed output files in the `finalOutput/` folder:
   - `output111`, `output221`, `output122` saved as:
     - **CSV**
     - **RDS**
     - **Parquet**

