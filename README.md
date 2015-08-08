# ankfindmusic

standalone java app- console app!

Functionality :
- lets user search for the music
- offers them to choose from variety of scrapped results ( only the filename and size not the website)
- download/save it to the default/preferred location

Tech:
- querry google with randomly configured parameters 
- UI the captcha if google detects any abnormality and redirect this captcha to google, retry, also close the captcha if done
- ask for the prefered location if not, save it in the default one.

Modules:
- Main -> Calls out the below modules:
	- querryG ( handle the captcha) -> gives out list of sites
	- scrapper -> gives out file name and size
	- downloader -> downloads/ save the file
