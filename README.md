# rancher
for run rancher 


download last version of burmilla.is from the link below:
https://github.com/burmilla/os/releases/

run rancher by burmilla.iso

on the other linux server ssh to rancher
1. touch config.yml like https://github.com/soheilagolshan/rancher/blob/main/config.yaml
2. RUN ros install -d /dev/sda -c config.yml (-d for storage device and -c cloud-config yml file - needed for SSH authorized keys)

----------------------------------------------------------------------------------------------------------------
If you want change config: 
1. set config on config.yaml like changeconfig.yml
2. RUN ros config validate -i yamlfile
3. ros config merge -i yamlfile
4. ros config export



