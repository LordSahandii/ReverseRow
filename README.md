# ReverseRow
[![](https://jitpack.io/v/LordSahandii/ReverseRow.svg)](https://jitpack.io/#LordSahandii/ReverseRow)

## What is it?

Reverse Row is an add-on to the Row in jetpack compose which lets you align the objects inside a Row such as texts, images, cards and etc. to the left or right.



## Installation

- First you need to add maven url inside the settings.gradle file.
```
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
- Then inside the project gradle.build add the maven url.
```
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```
- Finally, add the dependency inside the module gradle file.
```
dependencies {
  implementation 'com.github.LordSahandii:ReverseRow:Tag'
}
```
For more information about installations visit the [jitpack website](https://jitpack.io/#LordSahandii/ReverseRow/1.0.1)

## How To Use

=> To use this addon, just import it in the header of your file.

=> make a normal Row, and inside the properties search for word "reverse".

=> You can set it to true to reverse the orders of the contents to the left.

=> You can set it to false to keep the orders of the contents.

## Jitpack Link

https://jitpack.io/#LordSahandii/ReverseRow/1.0.1

## License

MIT

Free Open Source Library

