# ScratchCardExample
Scratch Card Example for point 
To get a Git project into your build:


Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

	allprojects {
	
		repositories {
			
			maven { url 'https://jitpack.io' }
		}
		
	}
	
  
  Step 2. Add the dependency
  
 dependencies {
 
	        implementation 'com.github.codeplayon:ScratchCardExample:ScratchCardView'
		
	}


Also Read On https://www.codeplayon.com/2022/12/scratch-card-view-like-google-pay/
