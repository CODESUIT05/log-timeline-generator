# log-timeline-generator
Objective:

This day focuses on parsing .vlog files, generating event timelines, and visualizing event frequency to aid digital forensic investigations and pattern detection.

Features:

-Parses structured .vlog files to extract:

Event ID

Timestamp

Event Type

Relevant Data Fields:

-Generates a clean, sorted timeline (timeline.csv) for rapid event correlation during investigations.

-Creates a line plot (event_frequency.png) displaying event frequency over time to visually detect spikes, drops, or unusual patterns.

-Handles multiple .vlog files together for unified analysis.

Outputs:
timeline.csv: A CSV file with a chronological list of events with extracted fields for further analysis.

event_frequency.png: A visual plot showing the frequency of events per minute.

Usage
1️) Place your .vlog files in a designated logs folder within your project.
2️) Run:

log_timeline.py
3️)Check the reports folder for:  timeline.csv
                                event_frequency.png

Dependencies
Ensure the following Python libraries are installed:
pip install pandas matplotlib
Why It Matters
- Transforms raw logs into structured, analyzable timelines.
- Quickly visualizes anomalies and spikes for threat detection.
- Builds a foundation for correlation analysis and advanced anomaly detection in later stages of your digital forensics workflow.
