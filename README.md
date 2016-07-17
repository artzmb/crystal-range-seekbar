# Crystal Range Seekbar

An extended version of seekbar and range seekbar with basic and advanced customization.

![alt tag](https://drive.google.com/uc?export=view&id=0B9bDENyIABT6cnh3MXY3TWstQWM)

# Usage
Add a dependency to your `build.gradle`:
```groovy
dependencies {
    compile 'com.crystal:crystalrangeseekbar:1.0.0'
}
```

# Features
- Customize with xml using custom handy attributes.
- Customize in your activity, fragment or dialog.
- Styling with your own widget.
- Creating newly widget from activity, fragment or dialog.

# Sample usage
Default style using xml.

![alt tag](https://drive.google.com/uc?export=view&id=0B9bDENyIABT6eFZkcFZKbWUxY1E)

```groovy
<com.crystal.crystalrangeseekbar.widgets.CrystalSeekbar
    android:id="@+id/rangeSeekbar1"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"/>

```

Styling with bubble animation using custom widget `BubbleThumbSeekbar`.

![alt tag](https://drive.google.com/uc?export=view&id=0B9bDENyIABT6Snk1Q21TbjhkWjQ)

```groovy
<com.crystal.crystalrangeseekbar.widgets.BubbleThumbSeekbar
    android:id="@+id/rangeSeekbar2"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:corner_radius="10"
    app:min_value="50"
    app:max_value="150"
    app:bar_color="#C69E89"
    app:bar_highlight_color="#A54B17"
    app:left_thumb_color="#775E4F"
    app:left_thumb_color_pressed="#4C2D1A"
    app:data_type="_integer"/>
```
Styling with bubble animation with drawable using custom widget `BubbleThumbSeekbar`.
```groovy
<com.crystal.crystalrangeseekbar.widgets.BubbleThumbSeekbar
    android:id="@+id/rangeSeekbar3"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:corner_radius="10"
    app:min_value="0"
    app:max_value="100"
    app:steps="5"
    app:bar_color="#F7BB88"
    app:bar_highlight_color="#E07416"
    app:left_thumb_image="@drawable/thumb"
    app:left_thumb_image_pressed="@drawable/thumb_pressed"
    app:data_type="_integer"/>
```                    
