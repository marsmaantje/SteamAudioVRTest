# Steam Audio x SteamVR Test
This repository is a test for me to see how far I can get with SteamAudio and SteamVR with minimal coding.

### Audio Occlusion
In the sample scene I have a box setup with an audioSource inside, the box has a meshcollider and a steamAudioGeometry component. The audiosource has a steamAudioSource component added to it as well, and this allows the box to occlude the audio when it is in between the player and the audioSource.<br>
Additionally above the box there is a smaller box on a slider with a rigidbody setup so you can move it over the hole in the big boxcx and hear the audio get quieter.

### VR Physics
The Physics interaction in the scene is all handled automatically by SteamVR, the hands have rigidbodies and colliders and apply forces to whatever other object they touch.