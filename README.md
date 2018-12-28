# General
API Blueprint format tutorial:
https://apiblueprint.org/documentation/tutorial.html

Tool for rendering html file:
https://github.com/danielgtaylor/aglio

Please run the following command inside root directory to render html file:
```console
aglio -i api/v1/documentation.apib -o api/v1/documentation.html
```
You can find current documentation file in api/v1/documentation.html
You can open it in browser.

# Notes
All URLs in resources are relative to api version.
For example, `/ingredients` stands for `https://smaki-maki.com/api/v1/ingredients`
