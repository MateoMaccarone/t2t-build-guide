# Time2Talk Bundle Guide

## Android:

* ### Build:
	1. Add version, **number**, **code** and **name**:
		* Version **number**: ```src/actions/constants/parameters.js```
		* Version **code** and **name**: ```android/app/build.grandle```
	2. ```cd android```
	3. ```./gradlew clean```
	4. ```cd ..```
	5. ```npx jetify```
	6. ```cd android```
	7. ```./gradlew bundleRelease```
	8. **app.abb** in:  ```android/app/build/outputs/bundle/release```
	
* ### Play Store:
	1. Internal test:
		* Upload **app.abb**
		* Upload version
		* Upload content
	2. Promote to production

## iOS:

* ### Build and Distribute:
1. Select project -> General
2. Add **version** and **build** number
3. Select **Any iOS Device**
4. Product -> Clean 	Build Folder
5. Product -> Archive
6. Distribute App 
