# MiSTercade V2 Mapping Updater
This database can be integrated in MiSTer FPGA by editing the `downloader.ini` file at the root of the SD.

## How to integrate the mappings into MiSTer Downloader
To integrate it in a MiSTer device, add the following section to the end of to the file `downloader.ini` that should be placed at the root of the SD (if it doesn't exist, you may create it for this purpose):
```ini
[misteraddons/mistercade_v2_mappings]
db_url = https://raw.githubusercontent.com/misteraddons/mistercade_v2_mappings/db/db.json.zip
```
After that, run *downloader* or *update_all* as usual. It will try to fetch the files from your newly created database. 

## Free-play Mapping Repository
If you want to try the `freeplay` mapping repository (start assigned to start and coin), go here: https://github.com/misteraddons/mistercade_v2_freeplay_mappings
