# Braker Lane Data

This repo contains information that the residents of Whisper Valley and its stakeholders may find interesting or useful. This data is provided as-is and I cannot guarantee its accuracy. I'm not a professional developer, so it's quite possible that any data analysis or conversion may contain errors, which is why I've also provided source data for those interested in checking my work. Additionally, I cannot guarantee that the radar sensor used to gather speed data was correctly calibrated or that the measurements are accurate. Anecdotally, the sensor provides a reading consistent with my vehicle speedometer but I haven't spent any time trying to characterize and validate the speed data.

That said, I do think this data is useful in that it provides a starting point to decide if further investigation is warranted using more accurate techniques as well as giving a qualitative overview of some traffic patterns.

## directory structure

General description of the directories in this repo. Visit the Wiki tab to see a detailed breakdown of what each type of file contains, the naming schemes, and other possibly useful information.

| directory name | directory/file description |
| :------------- | :------------------------- |
| `csv converted stalker data/` | Minimally processed data converted from binary source file to a CSV text file. |
| `csv speed data/` | Processed data containing speed, time, and record number in csv format. |
| `STALKER_ROADSIDE_LOGS/` | Raw binary data that must be processed to be read. |
| `summary graphs/` | Image/PDF files containing data analysis and graphs. |
| `all_exploded_speed_data.csv` | Single CSV file containing all _csv speed data_ for Braker Lane. |

## more information

See the Wiki for detailed explinations and notes on each type of data collected.
