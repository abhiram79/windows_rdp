# windows RDP
Open a windows RDP server with Github Actions and Tailscale vpn
<p align="center">
  <img src="/image.png" />
</p>

# Disclaimer 
I am not responsible for any issue that happens to your github account for doing such things 
and also i am not promoting this kind of things this is just for educational purpose only

## instructions 
- Fork this repository
- Go to [login.tailscale.com](https://login.tailscale.com/) and create a account with your Github account
- Finish the setup. then go to the settings - Keys - and generate an auth key
- copy the key and add it as a secret in your forked repo as <b>TAILSCALE_AUTH_KEY</b>
- Then run the workflow
- Install Tailscale and the Windows app form playstore
- open Tailscale app and login with your same Github account the start the vpn connection
- open the windows app login with the creditinals ( Get the credentials from github Actions logs )

## Important 
- Your github account may get ban for doing this. use at your own risk
