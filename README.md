This is a complete Android Studio project with everything needed to build an andengine project which links to the Box2d Extension. Note, there is an added file in the /app directory called "lib.jar". This contains the object code that the project must link to in order to run on arm and x86 android processors. The build.gradle file in that directory has the line "compile files('lib.jar')" added in the dependencies section.

The instructions for setting that dependency up are here : http://geq-i.blogspot.com/2014/02/how-to-setup-andengine-in-android-studio.html under Fixing java.lang.UnsatisfiedLinkError

