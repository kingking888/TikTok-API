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

Sample query generated: os_api=25&device_type=SM-G988N&app_name=musical_ly&version_name=22.0.5&channel=googleplay&device_platform=android&iid=7031934232164271877&version_code=220005&device_id=7031934173436052997&os_version=7.1.2&aid=1233




