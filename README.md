# ATS ARTTECH 4135-001: Virtual Reality
## Assignment03 - *VR user and interactions* 
## Due date: 09/28/2018 at 11:59pm

In this assignment you will start with the github classroom link, create your own assignment repository, clone it on to your computer, make modifications to the unity project, commit the changes, and push back the updated repository to github.

## Potential Resources:
> For this assginment, is higliy recommended looking into  VRTK-Master, Example 005 - Interactions.

- [VRTK - Virtual Reality Toolkit Website](https://vrtoolkit.readme.io)
- [VRTK - Virtual Reality Toolkit Documentation](https://vrtoolkit.readme.io/docs)
- [VRTK - Virtual Reality Toolkit YouTube Channel](https://www.youtube.com/channel/UCWRk-LEMUNoZxUmY1wO7DBQ)

- [VRTK - Pointers, Teleporting, and Object Interactions](https://youtu.be/sW9lxEUXfe8)
- [VRTK - Teleporting Tutorial(s)] (https://youtu.be/2IWAwFDhX2M) - There are multiple videos in series.
- [VRTK- Locomotion Tutorial(s)] (https://youtu.be/1rtXMzc2mfI) - There are multiple videos in series.

You should also feel free to watch anything else you find helpful, post to slack if you find good videos/tutorials/websites.

## Learning Outcomes
- In assignment02 you were able to move your user within the simulator by using the AWSD keys and teleporting.
- You will learn the ability to grab objects and move them within your scene.

## Directions
In order to receive full credit for the assignment you must do at minimum the steps outlined below, you may do more and explore other features within Unity and VRTK, in fact you are encouraged to do so as it will better prepare you for the two projects coming up in the second half of the semester.

### Required Steps
1. Clone the github repository to your desktop.
2. Modify the scene **assignment03**:
	- Addnavigation, either to move in the direction the user is looking when a button is pressed, or by using a teleporter.
	- Add elements to the environment, like a floor, models, lights, skyboxes, etc.
	- Add a `Box Collider` to the table so user and objects don't go through it.
	- Add a `Rigidbody` component to the Volleyball.
	- Add a `Sphere Collider` to the Volleyball.
	- Make an object grabbable, by adding a `VRTK_InteractableObject` script to the Volleyball object, and check the `Is Grabbable` checkbox.
	- Change the `Touch Highlight Color` to something the user can easily identify.
	- Add a '[VRTK_BodyPhysics](https://vrtoolkit.readme.io/docs/vrtk_bodyphysics)' component to the CameraRig (VRSimulator and SteamVR)so the player doesn't pass through objects.
3. Commit changes to repository, remember to add a useful commit message(s).
4. Push committed changes to github.


### Bonus point
* add an avatar hand
* modify ligthing & customize the skybox 
* Commit changes to repository, remember to add a useful commit message.
* Push committed changes to GitHub.
