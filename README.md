# UrlEmbed

[![Build status](https://ci.appveyor.com/api/projects/status/3iq2q3wkx2k81wan/branch/master?svg=true)](https://ci.appveyor.com/project/xingh/urlembed/branch/master)


- Rahul 


* UrlEmbed gets information to show in a visual summary of a link. 
* This project is forked and is going through a revamping.
* Gets basic information such as title, description and thumbnail images
* Can be used for a link sharing application, or in our case to store more information of items in a search index
* It uses [FastImage](https://github.com/ynrajasekhar/FastImage) to get width, height of Images, and returns images if height >=50 && width >= 100 or width >= 50 &&  height >= 100 



### Example

    UrlInfo urlInfo = UrlEmbed.UrlEmbed.GetUrlInfo(url);

## Licence

MIT, see file ["MIT-LICENSE"](MIT-LICENSE)

