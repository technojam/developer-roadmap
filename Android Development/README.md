# Android Developer Roadmap

![Img](https://cdn.wccftech.com/wp-content/uploads/2020/02/android-developers.png)


## Getting Started
* Language
	* __Java/Kotlin__ (Any 1)
	* __XML__
	* __TypeScript/ JavaScript__ (Only if you want to write some backend, PS: getting the gist of it would really help you)
* Environment
	* __Compiler__
		* JDK
		* SDK
	* [__Android Studio__](https://developer.android.com/studio/?gclid=Cj0KCQjwhtT1BRCiARIsAGlY51IcXgCpjJnjYojvJFGVoLd6DBwK-HNWxs2rFdYoO9ZagvD2DPPPlvsaApB5EALw_wcB&gclsrc=aw.ds)
		* [Build your first app](https://developer.android.com/training/basics/firstapp)
		* Explore IDE
		* SettingUp AVD
	* __Project Structure__
		* Getting familier with different components of android project
		* Java/Kotlin, XML
		* [AndroidManifest.xml](https://developer.android.com/guide/topics/manifest/manifest-intro)
		* .gradle files
	* __Bonus__
		* What is VCS?
		* What is github?
		* [Basics of github](https://guides.github.com)
		* Setup vcs for your project.
		
## Let's code <>
* Android Components
	* __Activity( Logic + UI )__
		* [Lifecycle](https://developer.android.com/guide/components/activities/activity-lifecycle)
		*  Services
		* Broadcast Receiver
		* Content Provider
	* __Fragments__
		* Fragment Lifecycle
		* Fragment Manager
* UI( Make it beautiful )
	* __Static Components__
		* View
			* ImageView, TextView, Button, EditText
		* ViewGroup
			* LinearLayout, RelativeLayout
			* ConstraintLayout, CoordinatorLayout
			* RadioGroup, TextInputLayout
	* __Dynamic Components__
		* RecylerView, ListView
		* ViewPager
		* Spinner
	* __Resources__
		* Drawables 
		* Strings, Font, Colors, Style
		* App Icon, Vector Icon, Images
* Logic( Do the right way )
	* __Ineracting with UI__
		* findViewById()
		* View class
		* Methods and their working
		* Working with I/O 
	* __Code some logic__
		* Using Java/Kotlin and get your task done
		* Importing external dependency
		* Working with API
		* What is Maven, jcenter, classpath?
	* __Share the App__
		* Cleaning project
		* Generating bundle and signed apks


___
# --------- Take a break ---------
Learning android development continuosly can sometimes be a overwhelming task, and in this type of situations its totally fine to take a break.
Meanwhile here are some of the project ideas which will personally help you assessing yourself and getting the basics clear.

* __TODO__
	* A simple todo app which allow users to create task and can update it later if its completed or not. 
	* _Bonus: Try to implement notification feature which will notify user if he scheduled any task for any particular time/date._
	
* __CALCULATOR__
	* Try creating your version of calculator

* __Quake Report__
	* This app will keep user upto date with the recent earthquakes and will notify him if its near him.
	* [USGS](https://earthquake.usgs.gov/fdsnws/event/1/) has some great apis for geographical data
	
___

## Basics to Advance


*   Firebase
    -   __FCM__
    -   __Analytics__
    - __Crashlytics__
    -   __Dynamic Link__
    -  __App Indexing__
    - __Remote Config__
*   Architecture
    - __MVVM__
    -   __MVI__
    -   __MVP__
* Custom Views
	* __Canvas, Bitmap, Paint__
* Support UI
	* __ProgressBar__
	* __Dialog__
	* __Toas & Snackbar__
* Storage
	* __SharedPrefrences__
	* __FileSystem__
	* __RoomDB__
* Debugging
	* __Memory profiling__
	* __Logging__
	* __Systrace__
	* __Exceptions__	
	* __Error Handling__
* 3rd Party Libraries
	* __Image Loading__
	    *  __Glide__
	    *  __Picasso__
	-   __Dependency Injection__
	    -   Dagger
	-   __Networking__
	    -   Fast Android Networking Library
	    -   Retrofit
	-   __MultiThreading__
	    -   RxJava
	    -   Coroutines
*   Unit Testing
    -   __Local Unit Testing__
    -   __Instrumentation Testing__
* Android Jetpack
	-   __[Jetpack Compose](https://developer.android.com/jetpack/compose)__
	-   __Foundation Components__
		-   Android KTX
	    -   AppCompat
	    -   Multidex
	-   __Architecture Components__
		-  Work Manager
	    -   DataBinding
	    -   ViewModel
	    -    Navigation
	    -   LiveData
	    -   Paging
	-   __Behaviour Components__
	    -   Slice
	    -   Sharing
		-   Preference
		- Permissions
		- Notification
		- Media Playback
		- Download Manager
		
___

# Getting V1

Now its high time to get the version 1 of your app. Below are some of the rources and guidline which will surely help you getting your app to the playstore.

* Discovery & wireframing—Establish a blueprint of your app’s content that hinges on excellent UX and user interface (UI) design.
*	Design & software planning—Using Android Studio, a developer could create the Android User Interface with the [Material Design guidelines](https://material.io/design/guidelines-overview/). At the same time, they’ll create a cohesive plan for the software architecture of your app.
*	Coding & integration—With your app’s front-end architectures coded, next any back-end components (a database, APIs, middleware, etc.) are integrated.
*	Testing—Unit testing, integration testing, and debugging save time and can prevent extensive rewrites to fix buggy code.
*	Preparation & publishing— Your app gets prepped as a release-ready APK, uploaded to the Developer Console, then published to Google Play, [DOC](https://developer.android.com/studio/publish)



# Online Resources

* __Udacity__
	* [Basic User Interface](https://in.udacity.com/course/android-basics-user-interface--ud834)
	* [Basic User Input](https://in.udacity.com/course/android-basics-user-input--ud836) 
	 * [Multi Screen App](https://in.udacity.com/course/android-basics-multiscreen-apps--ud839)  
	* [Networking](https://in.udacity.com/course/android-basics-networking--ud843)  
	* [Data Storage](https://in.udacity.com/course/android-basics-data-storage--ud845)  
	* [Firebase in a Weekend](https://in.udacity.com/course/firebase-in-a-weekend-by-google-android--ud0352)
* __[JetPack Compose Tutorial](https://developer.android.com/jetpack/compose/tutorial)__






