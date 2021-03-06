<p align="center">
  <img src="https://github.com/kioko/paybill-manager/blob/master/app/src/main/ic_launcher_web.png?raw=true" alt="Paybill-Manager"/>
</p>


PayBill Manager
-------------------
Paybill manger is a simple app that consumes [Eugine Mutai's](https://developers.google.com/experts/people/eugene-mutai) 
amazing Restful Mpesa API - [ProjectMula](https://github.com/kn9ts/project-mulla)

<p align="center">
  <img src="https://github.com/kioko/paybill-manager/blob/master/art/develop/Collection.png?raw=true" alt="Paybill-Manager"/>
</p>


## Requirements
* JDK Version 1.7 & above
* [Android SDK.](http://developer.android.com/sdk/index.html)
* Android SDK Tools
* Android SDK Build tools 23.0.2
* Android Support Repository
* Android Support library


## Project Setup

This project is built with Gradle, the [Android Gradle plugin](http://tools.android.com/tech-docs/new-build-system/user-guide) Clone this repository inside your working folder. Import the `settings.gradle` file in the root folder into e.g. Android Studio. (You can also have a look at the `build.gradle` files on how the projects depend on another.)

* Start Android Studio
* Select "Open Project" and select the generated root Project folder
* You may be prompted with "Unlinked gradle project" -> Select "Import gradle project" and select 
the option to use the gradle wrapper
* You may also be prompted to change to the appropriate SDK folder for your local machine
* Once the project has compiled -> run the project!

### NB: (Instant Run)
If you have Instant Run enabled, you'll need to disable it. [SugarOrm](https://github.com/satyan/sugar) does not play nice with Instant Run.


Contributing
============

#### Would you like to contribute code?

1. [Fork Paybill Manager](https://github.com/kioko/paybill-manager).
2. Create a new branch ([using GitHub](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/)) or the command `git checkout -b branch-name dev`).
3. [Start a pull request](https://github.com/kioko/paybill-manager/compare). Reference [existing issues](https://github.com/kioko/paybill-manager/issues) when possible.

#### No code!
* You can [discuss a bug](https://github.com/kioko/paybill-manager/issues) or if it was not reported yet [submit a bug](https://github.com/kioko/paybill-manager/issues/new).


Libraries Used
============
1. [SugarOrm](https://github.com/satyan/sugar) 
2. [Retrofit](http://square.github.io/retrofit/)
3. [ButterKnife](http://jakewharton.github.io/butterknife/)
5. [Glide](https://github.com/bumptech/glide)
6. [MaterialView Pager](https://github.com/florent37/MaterialViewPager)
7. [MoneyTextView](http://android-arsenal.com/details/1/3835)

License
-------

    Copyright 2016 Thomas Kioko

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

