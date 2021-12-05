# TikTok-API
An API that allows you to get full information about TikTok videos without using any third party sources and only the TikTok API.

This API was created by me.

This API was last tested and worked on Dec 1, 2021.

# More
V0.0.9 for Python 3.x.x

This API uses the script from here: https://github.com/frogc0de/TikTok-Algorithm

This API requires the requests lib https://docs.python-requests.org/en/latest/

# Usage
First step would be to obtain a url the tiktok application sends to get/post to it's api.

The url should contain things like device parameters and account id's.

To obtain the dictionary of needed parameters use: getDeviceParams("The url")

To set the API parameters use: setDeviceParams(theDictionary)

After this is done use getVideoByUrl("Tiktok video url") or getVideoById("Tiktok video id") to get the information about the video

The information contains the following: Unwatermarked video url, watermarked video url, music info, avatars, covers, author info, video statistics and etc.


If you are unable to extract the needed parameters from your account use the parameters located in the sampleParams file, they currently work, but may stop working at any time which is why it is recommended to use your own account for this. Usage: .deviceParamsQuery="Sample params"

Example replit: https://replit.com/@FrogCode/TikTokAPI
