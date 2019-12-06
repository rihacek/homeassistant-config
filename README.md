# Home Assistant Configuration

Here's my [Home Assistant](https://home-assistant.io/) configuration. My setup is running in Docker within a CentOS 7.6 vm on ESXi. This and a bunch of other containers and vms live in an old loaded up Dell PowerEdge r610. My goal with this project is as much learning and hobby-work as convenience. Walking over and turning on a light is fine, but there's something fun to having your reading lamp turn on just before sunset or knowing that the garage door wont accidently stay open all night. I'm also big into data/analytics, so the time-series and measurement stuff is a lot of fun too. I hope to add some fun vis to my home page in the future.

We mitigate privacy and security concerns via DNS sinkholing phone-home devices and avoiding cloud IoT solutions for the most part. I also try to build and root devices where I can and stay current on updates and firmware where I can't. Thanks so much for checking this out!

## Run Commands
### Windows 
```docker run --init -d --name="home-assistant" -v c:\workspace\homeassistant:/config -p 8123:8123 homeassistant/home-assistant:stable```

### Linux
```sudo docker run --init -d --name="home-assistant" -v ~/homeassistant:/config -p 8123:8123 homeassistant/home-assistant:stable```
