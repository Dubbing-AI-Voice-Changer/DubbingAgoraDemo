# Dubbing AI Voice Changer
***
### Android

Preparation
* Download the required resources from this link: https://dvi.dubbing.tech/vc-plug/resources.zip
* Obtain your Agora appId, userId, Agora token, and room id, and fill in the corresponding variables of MainActivity.
* Run the demo, and an application directory will be generated on the device.
* Through the DeviceFileExplorer of Android Studio, find the data/data/com.gerzz.demo/files directory, and create a new vc_model directory under this directory.
* Get your license file, voice file, model file. Put these files into the folder created in the previous step.
* Use another device to enter the room.

Interface Operation
1. Click to enter the room. After entering successfully, another device will hear your voice.
2. Click `Strat voice changing` to start changing the voice, and the voice changing engine will be initialized at this time, and the voice will start to change after success. Note: Only the original sound can be heard at this time.
3. Click `Choose voice` to set the voice, and the voice list will appear. Click on a voice, and after setting the voice successfully, another device can hear the sound after voice conversion.
4. Click `Stop voice changing`, you will hear the original voice.
5. Click `Disable plugin`, you will hear the original voice.
6. After disabling the plug-in, if you need to enable it again, you need to click `Enable plugin` first, and then start from step 2.
