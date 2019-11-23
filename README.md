# Home Assistant Configuration

Here's my [Home Assistant](https://home-assistant.io/) configuration. Placeholder: describe HA environment (docker on centos on esxi on dell). Placeholder: approach to home automation/privacy.

## Run Commands
### Windows 
todo: figure out mounting for config

```docker run --init -d --name="home-assistant" -v c:\workspace\homeassistant:/config -p 8123:8123 homeassistant/home-assistant:stable```

### CentOS
```sudo docker run --init -d --name="home-assistant" -v ~/homeassistant:/config -p 8123:8123 homeassistant/home-assistant:stable```
