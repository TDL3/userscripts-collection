# Get All Links | 获取全部链接
## Description
Get all links from a website, change @match to the website to which you want to get links. 
获取网页中的全部链接，将 @match 改到你想获得链接的网站。  
## Screenshot
![table](table.png)

## Example
### Get all video watch links of a youutbe channel
1. change `@match` to `https://*.youtube.com/*`
2. change filter_results to true;
```javascript
const filter_results = true;
```
3. change regex to `watch`
```javascript
const filter_regex = new RegExp(/watch/g);
```
![youtube](youtube.png)