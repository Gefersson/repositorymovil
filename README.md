
dependencies {
	        implementation 'com.github.Gefersson:repositorymovil:Tag'
	}
  
  
  <dependency>
	    <groupId>com.github.Gefersson</groupId>
	    <artifactId>repositorymovil</artifactId>
	    <version>Tag</version>
	</dependency>
  
  libraryDependencies += "com.github.Gefersson" % "repositorymovil" % "Tag"
  
  :dependencies [[com.github.Gefersson/repositorymovil "Tag"]]	



Coloca tu Android SDK en algún lugar de tu directorio home o en algún sitio independiente de cualquier otra aplicación. Algunas distribuciones de IDEs incluyen el SDK en la instalación, y es posible que lo coloque en el mismo directorio donde se encuentra el IDE. Esto puede ser contraproducente cuando necesites actualizar (o reinstalar) el IDE, ya que podrías perder la instalación del SDK, y forzándote a un nuevo largo y tedioso proceso de descarga
  <!-- Base application theme. -->
  
  
    <style name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar">
        <!-- Customize your theme here. -->
        <item name="colorPrimary">@color/colorPrimary</item>
        <item name="colorPrimaryDark">@color/colorPrimaryDark</item>
        <item name="colorAccent">@color/colorAccent</item>

    </style>
    <style name="Base.theme.yellow" parent="AppTheme">
        <!-- Customize your theme here. -->
        <item name="colorPrimary">@color/md_yellow_700</item>
        <item name="colorPrimaryDark">@color/md_amber_50</item>
        <item name="colorAccent">@color/colorAccent</item>
        <item name="android:backgroundTint">@color/md_amber_600</item>
        <item name="android:textColor">@color/md_black_1000</item>
        <item name="android:textStyle">bold</item>
        <item name="android:buttonTint">@color/md_yellow_500</item>
        <item name="android:spinnerDropDownItemStyle">@style/mySpinnerItemStyle1</item>
    </style>
    <style name="mySpinnerItemStyle1" parent="Widget.AppCompat.Spinner">
        <!-- Customize your theme here. -->
        <item name="android:textColor">@color/md_blue_100</item>
        <item name="android:popupBackground">@color/md_red_300</item>
    </style>






