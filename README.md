# Fully Automated Youtube Channel

Code to run a fully automated youtube that can scrape content, edit a compilation, and upload to youtube daily. \
Read about it here: https://medium.com/@nathan_149/making-a-fully-automated-youtube-channel-20f2fa57e469

# Instructions

1. [Download](https://github.com/nathan-149/automated_youtube_channel/archive/main.zip) the Github Repository

2. Download and install [Python3](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installing/)

3. Install libraries with `pip3 install -r requirements.txt` or `python3 -m pip install -r requirements.txt`

4. Get setup and create a Project with the Youtube API: https://developers.google.com/youtube/v3/quickstart/python
Be sure to follow it carefully, as it won't work if you don't do this part right.
Download your OATH file as "googleAPI.json" in your project folder.

6. Create an instagram account and follow accounts you want to scrape from

7. Open main.py in a text editor and fill in necessary information

8. Run `python3 main.py` You have to sign in to your Youtube Account through the link the script will give you.

9. Enjoy your fully automated youtube channel! :) Note that for uploading public videos, you have to complete an audit for the Youtube API. See the note in the [Google Documentation](https://developers.google.com/youtube/v3/docs/videos/insert)
