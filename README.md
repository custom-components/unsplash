# camera.unsplash

A camera platform that give you random images from Unsplash presented as a camera feed.

To get an API key you need to register an account [here.](https://unsplash.com/developers)
  
To get started put `/custom_components/camera/unsplash.py` here:  
`<config directory>/custom_components/camera/unsplash.py`  
  
**Example configuration.yaml:**

```yaml
camera:
  platform: unsplash
  api_key: HFSD7843HHFUKLHSDF84HFLWF8S4HF8OFSLJ8W34FBLWS
  output_dir: /www/
```

**Configuration variables:**  

key | description  
:--- | :---  
**platform (Required)** | The camera platform name.  
**api_key (Required)** | Your Unsplash API key.
**output_dir (Required)** | This camera platform saves the image to a location on your host, this should be /www/  
**collection_id (Optional)** | Limit the picture to a collection.

**Sample overview:**
![sample](sample.png)