# home-assistant-no-dhcp-custom-component
Use default_config: without the dhcp integration 


This thing only exists since as of now (2021-02-03) it is impossible to customize the `default_config:` option of Home Assistant.
Therefore, the only way to get rid of the dhcp without manually adding everything added by `default_config` is to override the unwanted components.

This repository will be archived as soon as this changes.

The DHCP component is something new because it's worse for different reasons.
What could go wrong with constantly sniffing the whole network traffic?

You should be able to add this as a custom repository URL to HACS.
This will however not be added to the default HACS repository since it makes sense for regular users to not override the cloud and updater components.
If you really want to do this, you should be "advanced" enough to add a custom repository.

Also, feel free to check out

- [the cloud: counterpart](https://github.com/Hypfer/home-assistant-no-cloud-custom-component)
- [the updater: counterpart](https://github.com/Hypfer/home-assistant-no-updater-custom-component)