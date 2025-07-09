# Discord-Enchanted
this repository containt some CSS code to enhance the discord expirience, Think of it as putting sharpness on a sword 
full list of what we changed:
- message search bar, now its less long and when you click it the bar will became longer again
- the user pannell now will not over the channel list
- categories and chat are now slightly more compact
- settings now don't have a big forehead anymore
- the apps authorization list is now more compact
- added roundy edges almost everywhere
- 
previews:
![immagine](https://github.com/user-attachments/assets/e58efb81-3e6a-4b72-9a3e-155c7880d95a)
[preview.webm](https://github.com/user-attachments/assets/a2b1e358-60e7-4860-a24a-8246ede7ce44) 

## Slop removed
as the name implies, this style sheet serves to remove certain clutter elements in the discord user interface, for example we removed all banners advertising nitro, discord is full of them!!!

full list of what we removed:
- personalizattion suggestions
- Nitro ads in the profile settings
- nitro preview
- 'Learn More' for nitro in the popout in the side of DM
- nitro icon in words count
- the "use app" option when you click the + near the text input
- "New member" tag
- gift button 🟥 🟦
- help button 🟥 🟦
- shop button in dms
- nitro button in dms
- title bar that tell you the server name 🟦
- removed nitro promotions

legend:
🟦 is broken/may break on chrorium browsers
🟥 will break if you don't use English or Italian language on discord 
-# thank you, discord developers, for making it annoying to work with ^3^
## enchanted ui
this one make the ui a little less cluttered and sleek

### known issues:
the server list could have problems on chrorium browsers

### why there are fetures that mayb brek if i don't use English or Italian?

this problem is due of discord developer using same classes and IDs for elements, and the only way to distinguish them is by using "aria-label" an element that is useful for blind people but we use it for distringuish an element from another if they have the same class and id, since aria-labels change for every language i decided to use englis, the most used lnguage and Italian, my native language;
if you want other launguages fork the repo, add it and then make a pull request so we can add the new languages, thanks
