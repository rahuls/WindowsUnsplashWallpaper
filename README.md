# Unsplash wallpapers for Windows 

A python script which sets the wallpaper for Windows desktop using Unsplash API. 

## Usage
The program accepts arguments and then it fetches an image that is relevant to the given arguments
```bash
python app.py black cars
```

The above command sets a wallpaper of car with black color.
```bash
python app.py
```
The above command sets a random wallpaper from unsplash. If no argument is passed, then a random wallpaper is choosen.

## Note
* The wallpaper is saved as 'wall.png' and is located at where app.py is executed.
* This program can be scheduled in Windows using Task Scheduler. For scheduling follow [this](https://www.esri.com/arcgis-blog/products/product/analytics/scheduling-a-python-script-or-model-to-run-at-a-prescribed-time/).
