<div align="center">
  <h1>w3m0d-pr0-unl0ck3r - CLI</h1>
  <h4>This program patches the w3m0d app to think you're a pro subscriber.</h4>
  <!-- <img src="https://img.shields.io/github/v/release/delabarra/w3m0d-pr0-unl0ck3r.svg" alt="Latest version">
  <img src="https://img.shields.io/github/downloads/delabarra/w3m0d-pr0-unl0ck3r/total?label=GitHub%20Downloads" alt="Downloads on GitHub"> -->
  <img src="https://img.shields.io/github/license/delabarra/w3m0d-pr0-unl0ck3r" alt="License"> 
  <img src="https://img.shields.io/badge/rust-2021-orange?logo=rust" alt="Rust 2021">
  <img src="https://img.shields.io/github/languages/code-size/delabarra/w3m0d-pr0-unl0ck3r?color=yellow" alt="Code Size"><br/><br/>
  <img width="256" src="https://user-images.githubusercontent.com/110846042/204567385-4df3007c-7a63-40fd-9feb-f9f36aa43030.png" alt="w3m0d Pro Unlocker Logo">
</div>

#### [Back to the main page](../README.md)

<br/>

## ❗ Note

*Version 9.0.2 introduced "ASAR Integrity Check". To remove download following file and check the README.md file to apply.*<br/>
*- [Patched ASAR Integrity Check](https://shorturl.at/8PZA8) (by Sak32009).*

## ⬇️ Run / Build
<!-- 1. Install it using cargo: ```cargo install w3m0d-pro-unlocker``` -->
1. Use ```cargo``` to ```run``` or ```build``` from source.

<br/>

## ⚙️ Configuration
| Argument                  	| Description                                                                                                                           	| Example
|---------------------------	|---------------------------------------------------------------------------------------------------------------------------------------	|----------------------------------
| --wemod-dir <dir>         	 	 	 	 	 	 	          	  | Path to your w3m0d dir. By default, this is "%localappdata%/WeMod".                                         	| C:\WeMod
| --wemod-version <version> 	 	 	 	 	 	 	          	  | The version to patch. By default, this will be the latest version installed. 	                                | 8.3.6
| --account <json>            	 	 	 	              	  | Overwrites the account data. You can find all available options by searching for /v3/account in the dev tools | username:'myaccount',email:'test'
| -no-update / -offline            	 	              	  | Doesn't check for/install updates                                                                             | ---
| -v                          	 	 	 	 	            	  | Prints out the version info. Will cancel everything else                                                      | ---

<br/>
