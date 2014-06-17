python_images
=============

python image functions

<b>Base64FromUrl</b><br>
returns the base64 string of the image from the passed url

| param  | description
| ------ | ------------
| url    | the url of the image   

<i>return</i>: the base64 string of the image

=============

<b>CropResizeImg</b><br>
crops and resize the image to create the thumbnail

| param  | description
| ------ | ------------
| origFilePath    | the path of the file on the disc   
| destFilePath    | the destination file path on the disc   
| img_w    | the desired image width 
| img_h    | the desired image height  

<i>return</i>: void

=============

<b>CropResizeImg64</b><br>
crops and resize the image to create the thumbnail from a base64 string

| param  | description
| ------ | ------------
| orig64    | the base64 string of the image   
| img_w    | the desired image width 
| img_h    | the desired image height  

<i>return</i>: the resized/cropped base64 string of the image
