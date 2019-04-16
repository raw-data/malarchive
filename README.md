# Malarchive
Malware samples - mostly `commodity ones` - observed in the wild from time to time.

Storing samples in this way just **fits my workflow**, if you are looking for a real _Malware Zoo_, well ... this is the wong place for you.

There are a bunch of great _platforms_ and _communities_ out there that are doing an amazing job ... Google is your friend ;)

Repository structure
```
# Single folder samples
(root) malware-type
        |
        \--> malware-family
            |
            \--> (gathering) date
                    |
                    \--> samples

# Multi stage samples
(root) malware-type
        |
        \--> malware-family
            |
            \--> (gathering) date
                    |
                    |--> 1st_stage
                    |       |
                    |       \--> samples
                    |
                    |--> 2nd_stage
                    |       |
                    |       \--> samples
                    |
                    |--> 3rd_stage
                    |       |
                    |       \--> samples
                    |
                    \--> N_stage
                            |
                            \--> samples
```

All samples are:
 - **7z** compressed 
 - **password** protected _(with a common word used in the malware research sector for sharing samples_)

# The repository might be interesting to you if
You are looking for:
- A - small - inventorized set of malware families
- Download samples straightaway
- Test your sandbox / AV / NIDS / ETP / ? with already classified threats
- Binary diffing samples from the same family observed in a given timeframe (spotting unpacking config code?)
- Testing YARA / ClamAV ruless
- Multi stage payloads
- add here ...


# Malware families
_Note_: some samples might fall into multiple categories, but just one is chosen and used in the table.

| Family | Type | Link |
|:---:| :---:|:---:|
|hawkeye|keylogger|[samples](keylogger/hawkeye)
|avemaria|rat|[samples](rat/avemaria)
|xperrat|rat|[samples](rat/xperrat)
|njrat|rat|[samples](rat/njrat)
|adwind|rat|[samples](rat/adwind)
|netwire|rat|[samples](rat/netwire)
|flawedammyy|rat|[samples](rat/flawedammyy)
|imminentrat|rat|[samples](rat/imminentrat)
|nanocorerat|rat|[samples](rat/nanocorerat)
|backnet|rat|[samples](rat/backnet)
|remcosrat|rat|[samples](rat/remcosrat)
|tvrat|rat|[samples](rat/tvrat)
|azorult|stealer|[samples](stealer/azorult)
|lokibot|stealer|[samples](stealer/lokibot)
|kpot|stealer|[samples](stealer/kpot)
|predator|stealer|[samples](stealer/predator)
|formbook|stealer|[samples](stealer/formbook)
|arkei|stealer|[samples](stealer/arkei)
|gandcrab|ransomware|[samples](ransomware/gandcrab)
|mylobot|downloader-dropper|[samples](downloader-dropper/mylobot)
|artra|downloader-dropper|[samples](downloader-dropper/artra)
|amadey|downloader-dropper|[samples](downloader-dropper/amadey)
|kardonstealer|downloader-dropper|[samples](downloader-dropper/kardonstealer)
|ascentorloader|downloader-dropper|[samples](downloader-dropper/ascentorloader)
|agenttesla|spyware|[samples](spyware/agenttesla)
|gootkit|banker|[samples](banker/gootkit)
|danabot|banker|[samples](banker/danabot)
|ramnit|banker|[samples](banker/ramnit)
|nymaim|banker|[samples](banker/nymaim)

# Disclaimer
- **All files in this repository are malware!**
- **Any malicious content within this repository is intended for research / educational purposes**
- **DO NOT run these files unless you know what you are doing**
- **Files are uploaded password protected but I cannot ensure mistakes will not happen! Be wise and protect yourself when fetching these  specimen**
- **The materials here shared are provided on an 'as is' basis. I don not take any responsibility and I am not liable for any damage caused through use of these files, be it indirect, special incidental or consequential damages  (including but not limited to damages for loss of business, loss of profits, interruption or the like).**
