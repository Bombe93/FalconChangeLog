# FalconChangeLog
FalconChangeLog is an Android library to manage and show a changelog in your Android app.

"Inscription" was taken as the basis of the project.

[This is the link of the repository.](https://github.com/MartinvanZ/Inscription)

The goal is to improve and add functionality to the project.

<br>

Demo app on Google Play: 
```groovy
	To do soon
```

## How to include it in your project(Gradle):

```groovy
	compile 'com.github.bombe93:falconchangelog:1.0.1'
```


## How to use it:

- create a file under "rootProject/app/src/main/res/xml/changelog.xml" called "changelog.xml" and formatted like this:
```groovy
	<?xml version="1.0" encoding="utf-8"?>
	<changelog>
	    <release version="1.0" versioncode="2">
		<change>Small layout change in the view item screen</change>
		<change>Minor tweaks</change>
	    </release>
	</changelog>
```

- In the activity where you want to use it make the import:
 ```groovy
 	import com.github.bombe93.falconchangelog.FalconChangeLog; 
 ```
- Instantiate the class:
 ```groovy
 	FalconChangeLog changelog;
        changelog = new FalconChangeLog(YourActivity.this);
 ```
- And when you want to make the changelog look just to call the method like this:
 ```groovy
	changelog.show();
 ```




## Contribute

You can contribute without any problems.
