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


<b>Author:</b><br>
  name:   Antonio Tari<br>
  email:  antonio.tari@digiflare.com<br>
  web:    www.antoniotari.com<br>
  
  <img src="https://dl.dropboxusercontent.com/u/47015400/2013-04-12%2000.43.49-1.jpg" alt="Antonio Tari" border="2" width="444" height="333">
  <br>
  
