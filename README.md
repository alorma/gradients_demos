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


<img width="500" alt="Gradients demo" src="https://user-images.githubusercontent.com/887462/87879482-5e036600-c9eb-11ea-9d58-674d1695b6cb.png">
