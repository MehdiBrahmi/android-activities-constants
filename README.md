# android-activities-constants
Generates a static object that includes a list of all activities declared in all manifest files of your project.



## How to use ?

1. Added [activities-constants.gradle](https://raw.githubusercontent.com/MehdiBrahmi/android-activities-constants/master/activities-constants.gradle) in the module where you want to generate the object ``ActivitiesConstants.kt``

2. Include the gradle file to your build.gradle ``apply from: 'activities-constants.gradle'``

3. Build your project and use it !

    ActivitiesConstants is located in ``${applicationId}``.ActivitiesConstants
