# QSC Q-Sys Plugin for Genelec Smart IP speakers <!-- omit in toc -->

QSC Plugin for Genelec Smart IP Speakers

This Q-Sys module is written in LUA and saved in proper Q-sys Plugn-in format .qplug .
The module uses Genelec Smart IP API a REST style communication with a reduced set of HTTP/1.1 protocol.

Upon initialization the module gets parameters from speaker and syncs module with speaker settings.
Gain and Mute parameters can be controlled from module.

Every 10sec module syncs itself with speaker in case the speaker has been updated by another software like
Genelec Smart IP Manager for example.

<p align="center">
  <img src="https://github.com/Haek82/q-sys-plugin-Genelec-Smart-IP/blob/master/preview.png?raw=true">
</p>
