### How To Use

-----------------------------------------------



#### xml

```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:clipChildren="false"
    tools:context=".MainActivity">

    <com.ssong_develop.selectableshadowpositionview.SelectableShadowPositionView
        android:layout_width="200dp"
        android:layout_height="200dp"
        app:shadow_top_offset="1dp"
        app:shadow_bottom_offset="1dp"
        app:shadow_start_offset="1dp"
        app:shadow_end_offset="1dp"
        app:shadow_color="@color/black"
        app:shadow_stroke_width="8dp"
        app:corner_radius="16dp"
        app:blur_radius="16dp"
        app:border_color="@color/gray"
        app:card_background_color="@color/white"
        app:enable_shadow_top="false"
        app:enable_shadow_start="true"
        app:enable_shadow_end="true"
        app:enable_shadow_bottom="true"
        app:enable_border="false"
        app:enable_shadow="true"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintBottom_toBottomOf="parent">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textColor="@color/black"
            android:textSize="12sp"
            android:text="SelectableShadowPositionView"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintBottom_toBottomOf="parent"/>
    </com.ssong_develop.selectableshadowpositionview.SelectableShadowPositionView>
</androidx.constraintlayout.widget.ConstraintLayout>
```

-----------------------------------------------------------------------------------------------------------------------------------------------------------

### sample

<div>
<img src="https://github.com/SSong-develop/SelectableShadowPositionsView/blob/master/sample_default.png" width="300" height="650" /> 
<img src="https://github.com/SSong-develop/SelectableShadowPositionsView/blob/master/sample_no_bottom.png" width="300" height="650" /> 
<img src="https://github.com/SSong-develop/SelectableShadowPositionsView/blob/master/sample_no_end.png" width="300" height="650" /> 
<img src="https://github.com/SSong-develop/SelectableShadowPositionsView/blob/master/sample_no_start.png" width="300" height="650" /> 

</div>



-------------------------------------------------------------



### Download

- MinSDK = 26

------------------------------------------------------------------------------------------------------------------------



### Project-level build.gradle

```groovy
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

### Module-level build.gradle

```
	dependencies {
	        implementation 'com.github.SSong-develop:SelectableShadowPositionsView:1.0.5'
	}
```

