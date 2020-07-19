# gradients_demos


As you can see on the screnshot below:

Works
```xml
    <gradient
        android:angle="90"
        android:endColor="?colorOnSurface"
        android:startColor="@android:color/transparent"
        />
```

Gradients that references attributes not work as expected:
(`colorOnSurface` is black)
```xml
    <gradient
        android:angle="90"
        android:endColor="@color/color_on_surface_no_alpha"
        android:startColor="@android:color/transparent" />
```

```xml
    <gradient
        android:angle="90"
        android:endColor="@color/color_on_surface_38"
        android:startColor="@android:color/transparent" />
```

API 29 | API 22 (21)
---|---
<img width="280" src="https://user-images.githubusercontent.com/887462/87879573-05809880-c9ec-11ea-87cf-59c23e790827.png" /> | <img width="280" src="https://user-images.githubusercontent.com/887462/87879592-2e089280-c9ec-11ea-8ea6-2731cb695981.png" />
