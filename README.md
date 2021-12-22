# simple-chart
Simple chart written with JavaScript and you even don't need to add any css files. 
I didn't use any CDN links or JavaScript libraries, so you don't have to add any files or links execpt what you download from here.

just download and use.

## How to use
Doanload the files and put chart.js or chart.min.js and data.json(which will be your personal API) in your project folder.
Add this following script to your file:
```html
<script type="text/javascript" src="chart.min.js"></script>
```
Then just add these HTML tags to your HTML file:
```html
<div class="container">
    <div class="chart">
        <div class="label-x"></div>
        <div class="label-y"></div>
    </div>
    <div class="info">
        <h2>-</h2>
        <p>-</p>
        <pre>-</pre>
    </div>
</div>
```
**Notice that you can ADD new classes to the elements but you can't change the main classes.**
### JSON file
The json file which the information read from that called data.json that has some contents for example.

**The structure of json file is like this:**
```json
{
  "labels": {
    "x": "Horizontal axis content",
    "y": "Vertical axis content"
  },
  "activeColor": "Active column color",
  "items": [
    {
      "title": "Title of each content",
      "description": "...",
      "color": "Color of the column",
      "value": "A number (with intiger type NOT string)"
    }
  ]
}
```
**Note that you can just change the content of API not the names of each list. You can't change the names like items, activeColor, ..etc**
## demo
I put a folder called **demo** in the files you download to specify how to use the files there.

Your HTML file should looks like this:

![chart](https://user-images.githubusercontent.com/91287064/147079351-338cd4e5-ef5d-43c5-a503-7190268e4010.png)

You can change the content by using arrow keys(right and left) and also hover the column that you want to see its contents.
## Avoid error
***You may see an error or white screen while opening the files normally in the browser.***

***Use this syntax for this purpose:***
```
python -m http.server
```
**You can also use apps like** ***Wampserver*** **or** ***Xampp*** **to run mentioned file.**
## Author
**Atena Dadkhah**

- [My GitHub Link](https://github.com/Atenad86/)

 
