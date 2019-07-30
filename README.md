# camera.unsplash

A camera platform that give you random images from Unsplash presented as a camera feed.

To get an API key you need to register an account [here.](https://unsplash.com/developers)
  
To get started put `/custom_components/unsplash/camera.py` here:  
`<config directory>/custom_components/unsplash/camera.py`  
  
**Example configuration.yaml:**

```yaml
camera:
  platform: unsplash
  api_key: HFSD7843HHFUKLHSDF84HFLWF8S4HF8OFSLJ8W34FBLWS
```

**Configuration variables:**  

key | description  
:--- | :---  
**platform (Required)** | The camera platform name.  
**api_key (Required)** | Your Unsplash access key.
**collection_id (Optional)** | Limit the picture to a collection.
**name (Optional)** | Set the a custom name for the platform entity.
**interval (Optional)** | The interval in minutes to fetch new imgages, defaults to `10`, due to API limits this should never be less then `2`.

**NB!** It is the `Access Key` and **not** the `Secret key` you need to use.

**Sample overview:**\
![example](example.png)

***

[buymeacoffee.com](https://www.buymeacoffee.com/ludeeus)