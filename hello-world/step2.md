Click on the _Hello World Application_ tab.

Enter credentials of your choice - these values correspond to `userId` and `userAuth` parameters provided to JSSDK function [enrollUser()](https://api.ionic.com/jssdk/latest/Docs/ISAgent.html#enrollUser).

> NOTE: these credentials are different from the authentication credentials used during enrollment.
See [Profile Info](https://api.ionic.com/jssdk/latest/Docs/global.html#ProfileInfo) for more information.

Upon successful completion of the enrollment process, these parameters are used to store the encrypted enrollment profile in LocalStorage.

A new tab will open when you click the _Enroll_ button to initiate [device enrollment](https://dev.ionic.com/platform/enrollment). Complete the enrollment process then return to the tutorial.
