This is designed to be hosted on a distro of linux with a DE and firefox in kiosk mode for digital signage or menus via http://localhost:2015/ 
i used linuxLite on 2 of our old digital signage screens that havent been updated since ubuntu 14.4 ish and i didnt have the Root login so i created this to be used on them they have intel celeron dualcores from 2015 2 gigs of ram and 60 gigs of ssd which only has a 15 gig part this runs after login using systemd services to launch caddy using the caddyfile and to launch firefox in --kiosk mode on boot this may be a stupid way of making digital signage but its what i made in a few hours and deployed next day for my dad at his gas station


built using 
	<a href="https://caddyserver.com"><img src="https://user-images.githubusercontent.com/1128849/36338535-05fb646a-136f-11e8-987b-e6901e717d5a.png" alt="Caddy" width="100"></a>
