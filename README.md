PagerSlidingTabStrip bindings for Xamarin.Android
-----
Created by loosely following the [Xamarin guide](http://docs.xamarin.com/guides/android/advanced_topics/java_integration_overview/binding_a_java_library_%28.jar%29/) for binding a Java library. However, you should probably use [PagerSlidingTabStrip.Net by LordZoltan](https://github.com/LordZoltan/PagerSlidingTabStrip.Net) instead.

Usage
-----
1. Add this project to your solution
2. Edit your project's references to include this project  
3. You'll probably have to add the 'Android Support Library v4' component to your project even though it's included in this one
4. Add a `com.astuetz.PagerSlidingTabStrip` XML element to your layout
5. Add a `using Com.Astuetz` directive in your code

Notes
-----
* Built using the AAR for [PagerSlidingTabStrip](http://search.maven.org/#search|ga|1|a%3A%22pagerslidingtabstrip%22) v1.0.1, build action set as 'LibraryProjectZip'
* Built using the JAR for the [v4 Android support library](http://search.maven.org/#search|ga|1|a%3A%22support-v4%22), build action set as 'ReferenceJar'
* For some reason the 'Android Support Library v4' component had to be included in this project (in addition to the JAR) to build without errors
* The project builds successfully but produces a few warnings (explained in `Metadata.xml`)