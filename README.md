# Android Farsi String Converter
An Android library to fix Farsi discrete characters problem

#Add to dependency

##Gradle:

Step 1. Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.Sdghasemi:AndroidFarsiStringConverter:1.0'
	}
  
  
##Maven:
  
Step 1. Add the JitPack repository to your build file

	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
Step 2. Add the dependency

	<dependency>
	    <groupId>com.github.Sdghasemi</groupId>
	    <artifactId>AndroidFarsiStringConverter</artifactId>
	    <version>1.0</version>
	</dependency>
  
  
#How to Use

Here is an example:
  
	String fixedString = Farsi.convert(getString(R.string.my_string));
  
The returned string is continious.

#Note

This library works for both Farsi and English strings. So DO NOT worry about the string, it'll processes it as light :)
