If you are a musician and delay is making it difficult to play in time, follow this tutorial to remove playback delay.

In order to share audio from your DAW with no latency, you will have to use the Muse Multi-Output device instead of Muse Audio Share.

1\. Select Muse Audio Share (System Audio) below or from Muse’s Overview or Audio settings. 

!!MuseSystemAudioDeviceButton



2\. Create Muse Multi-Output in Audio MIDI Setup

Open Audio MIDI Setup by clicking the link below or by navigating to the app in Finder > Applications > Utilities

!!MacAudioMidiSetup

![multi-output1-2](https://user-images.githubusercontent.com/7818811/138992897-22e45526-0b89-44d6-ac9b-4d33e4020506.gif)

If you don't see the list of audio devices, open the Audio Devices window and select Show Audio Devices from the Window drop down menu in Audio MIDI Setup.

![show audio midi](https://user-images.githubusercontent.com/7818811/139167960-84e56411-e325-4199-9426-ff6a2a2b3e97.png)

If you already see Muse Multi-Output in the list, skip to step 3. Configure Muse Multi-Output

If you don't see Muse Multi-Output in the list already, create a Multi-Output device by clicking the + icon at the bottom left of the window, then select Create Multi-Output Device.

![create multi output](https://user-images.githubusercontent.com/7818811/139167953-32362ba0-3b7c-40ee-a65b-6750172a67c0.png)

Once created, double click the name to rename it to "Muse Multi-Output"

![multi-output5](https://user-images.githubusercontent.com/7818811/138998699-abf02510-4136-4988-875a-32b8d9872875.png)

3\. Configure Muse Multi-Output

To properly configure Muse Multi-Output, it's important to follow these directions or it may not work properly.
- Select the Muse Multi-Output device in the list to the left
- Set the Master Device to be your computer's built-in output (sometimes called MacBook Pro Speakers or similar) and make sure it's at the top of the list. 
- Select Muse Audio Share and the other audio devices that you want to share audio to (such as your external speakers, an audio interface, etc.)
- Enable "Drift Correction" for Muse Audio Share. It's highly recommended that you enable Drift Correction for all devices except the Master Device/Clock Source

In the end, the Muse Multi-Output device should look like this:

![multi-output-configured](https://user-images.githubusercontent.com/7818811/139167935-64a9eea4-2e48-4833-9977-30be78ef2346.png)

NOTE: If you do NOT intend on playing audio through the computer's built-in output, click the built-in output from the list on the left, and select "Mute" on this device. Otherwise, audio will also play from your built-in speakers.

![mute speakers](https://user-images.githubusercontent.com/7818811/139167948-20688271-a7c6-4a1f-88c5-b4f5a67e34f8.png)


4\. Disable Local Loopback in Muse Audio Settings

Local Loopback should be DISABLED when using Muse Multi-Output. This will prevent an echo. You can do this in Muse's Audio Settings or by clicking the LB button next to your device so it turns grey.


![LOOPBACK-OFF](https://user-images.githubusercontent.com/7818811/152443179-696f0209-81e1-4b8e-9c04-8a72150af298.gif)


5\. Select Muse Multi-Output as your DAW's audio output 

![muse-daw-2](https://user-images.githubusercontent.com/7818811/139195540-389dfe9b-95dd-4eca-ab76-c1d9e2df15f3.gif)


Now everyone in the session should be able to hear your DAW, and you won’t hear an echo or playback delay

Need more help? [Contact us!](https://www.musesessions.co/contact)