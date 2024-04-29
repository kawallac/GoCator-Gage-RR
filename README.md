# GoCator-Gage-RR
Project Description:
Take the output from an optical measruement system and conduct gage r&r calculations.

The opitcal measurement system collects variable data on two distinct parts, jobs '1' and '2'.
-Job '1' has 33 characterisictics that are being measured. So for a 10x3x3 gage rr study, the output file has 2790 rows.
  -It takes ~3.5 hours to convert the output csv to a useable format for minitab
  -It takes ~4 hours to conduct miniTab calculations and tabulate the reports

Work Breakdown:
-First, convert the output to a format that miniTab can use.
-Secondly, automatically conduct all the calculations and visualizations within Jupyter 

Updates:
04-28-24
-Basic function is there to convert output to miniTab format
  -Improvement:
    -Gage RR size is fixed at 10x3x3, for future utility have the conversion expand and contract with gage rr size
    -Write in tests for data integrity
