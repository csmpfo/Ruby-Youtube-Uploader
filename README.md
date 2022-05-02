**Youtube Uploader for Ruby**

I couldn't find a good example for uploading videos to youtube using google's api, so I created my own. 


**Quickstart**

install the google api client

`gem install google-api-client`

download your client secret from gcp, then put it into client_secret.json

on line 61, replace upload source with the path to your video.

when starting it for the first time, it will ask you to click a link. this link redirects you to the google login page where you can authenticate your google account, and select the account you want to upload the video to. after clicking your account, you will be redirected to a blank page. go up to the adderess bar, and copy the key. paste this key into the terminal and click enter. 
your video should begin uploading!


