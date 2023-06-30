<link rel="stylesheet" href="https://veli.ee/esphome/style.css">
<style>
	.markdown-body{
		border:0 !important;
	}
</style>

![pic](images/header.svg)

# Nest Thermostat clone on a Rotary Display running [ESPHome](https://esphome.io/)

> 👉 [**Home-assistant community thread for discussion**](https://community.home-assistant.io/t/esphome-nest-thermostat-clone-on-cheap-rotary-display/563296).

![pic](images/pic.jpeg)

## Installation

You can use the button below to install the pre-built firmware directly to your device via USB from the browser.

<esp-web-install-button manifest="./manifest.json"></esp-web-install-button>
<script type="module" src="https://unpkg.com/esp-web-tools@9.1.0/dist/web/install-button.js?module"></script>

<sup> It includes a GitHub workflow that will automatically build the configuration(s) and then deploys a simple 
website via GitHub pages that utilises [ESP Web Tools](https://esphome.github.io/esp-web-tools/) for users to 
easily install your project onto their device. </sup>


## Fun features
* Show a QR code if it’s not connected to wifi
	- Show another QR code to add it to HA if not connected to API
* Climate state, temperature, current_temperature, etc
* Icons, mapped to preset_mode and state
* Colored background like Nest if heating, text ECO if in eco preset_mode, etc

## Skin choices
### Nest
![google-nest](images/google-nest.png)
### Apple Home
![apple-home](images/apple-home.png)
### Google Home (App)
![google-home](images/google-home.png)

## Technical details

![tech](images/tech.png)

_________________

> 💖 If you find this useful, you can [![uwu](https://img.shields.io/github/sponsors/velijv?logo=githubsponsors&label=sponsor%20🫠%20me&style=flat-square&labelColor=rgba(0,0,0,0)&color=rgba(234,74,170,0.5) "for jsut 1 doolar you can lead a por man to fish")](https://github.com/sponsors/velijv) <br>
>  🤝 you can also send me more **ESP-based** or **Tuya** devices you want to see ported to ESPHome

###### All product names, logos, and brands are property of their respective owners. All company, product and service names used are for identification purposes only. Use of these names, logos, and brands does not imply endorsement.

<img alt="ESPHome" src="logos/made-for-esphome.svg" height="48">
<img src="https://veli.ee/northeast/logo?t=coded+in&c=808080&b=03A9F4&t2=%20📟" height="48" alt="Eesti">