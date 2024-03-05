
```
Write in-line equations with `\\( ... \\)` , like \\( x^n / y \\) . It's easy!
```

<br>

{{< youtube w7Ft2ymGmfc >}}

<br>



## Theme Custom Shortcodes



These shortcodes are not Hugo built-ins, but are provided by the theme.



### Responsive Images with Cloudinary



You can learn more about this [here](https://cloudinary.com/documentation/responsive_images).


Set the `cloudinary_cloud_name` parameter in your site config to use this shortcode.



```

{{</* dynamic-img src="/my/image/on/cloudinary" title="A title for the image" */>}}

```



Note that you do not include the file extension (e.g. `.png`) in the `src` parameter, as the shortcode will automatically determine the best quality and format for the user's device.



Optionally, you can customize the general CSS styles for the image:



```

{{</* dynamic-img src="/my/image/on/cloudinary" title="A title for the image" style="max-width:60%" */>}}

```