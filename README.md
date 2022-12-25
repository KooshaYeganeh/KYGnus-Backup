
# KYGnus_Backup


## INFO

This app Create Backup in Certain Times and Comapre with Previous Version.I Know I can Make Changes with Tar -u switch But for Update Versions
Bu I prefer Doing Like This.

in Scan part I use ClamAV and Rkhunter For Files Scanning for Malicious Files.


## Install

```
wget https://github.com/KooshaYeganeh/KYGnus-Backup/archive/refs/heads/main.zip
```

```
unzip main.zip
```

```
cd KYGnus-Backup-main
```

```
sudo cp KYGnus_Backup /usr/bin
```

-> add cron for This Script like this :

 * */3 * * * <path of app>

 This cron cause app Run in Forth a day

Note: I Write This code sand set This For my intent You can change it for own works



## Remove

