# hydrate_bot
Integrating nightbot with obs studio
## TODO:
- [ ] Get update whenever !hydrate gets called
- [ ] Play hydrate webm on obs

## How to run
On first setup:
```
pip install -r requirement.text
```

To run the script:
```
python main.py
```

Notes to self:
nightbot does not send triggers whenever a command is called
https://api-docs.nightbot.tv/#get-custom-commands
polling? get count amount if higher than last. call trigger 'play video'

curl -X GET "https://api.nightbot.tv/1/commands" \
  -H "Authorization: Bearer 875b2ad404f5dded27f4dcb75a368813"
