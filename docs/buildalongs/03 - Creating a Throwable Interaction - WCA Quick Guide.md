# Creating a Throwable Interaction in Meta Horizon Worlds Desktop Editor

## Related Links:
[Grabbable Entities On Mobile And Web](https://developers.meta.com/horizon-worlds/learn/documentation/create-for-web-and-mobile/grabbable-entities/create-grabbable-entities)

## When to use:
 When you want to design an interaction for mobile players that requires throwing a held item.

## Benefits:
It creates a fun interaction that is easy to implement and doesn’t require scripting.

## Steps:

1. From the Desktop Editor, go to the Build menu and select Empty Object \
![](media/03-Creating-a-Throwable_Interaction/image3.png)
2. This will add a container where we can place all the items that you want to include in the throwable, like visual effects and meshes \
![][image2]  
3. Add a shape to the world, from Build \> Shapes. We will be using a sphere for this example, by clicking on the shape and dragging it next to the empty \
![][image3]  
4. Using the hierarchy, place the shape inside the empty object\
![][image4]  
5. With the shape still selected, go to the properties (right panel), and change its positon to x: 0, y: 0, z: 0 \
![][image5]  
6. Select the Empty object from the hierarchy \
![][image6]
7. Go the the properties (right panel) and change the Motion to Interactive \
![][image7]  
8. Change the Interaction to Physics and Grabbable \
![][image8]  
9. Adjust the Scale to x:0.4, y:0.4, z:0.4 \
![][image9]  
10. Press the Play button to enter preview mode \
![][image10]  
11. Approach the sphere, and press E to grab it \
![][image11]  
12. While grabbing the sphere, press and hold the release button for 3 seconds to charge the throw \
![][image12]
13. Release the button and the avatar will throw the object \
![][image13]  
14. Press ESC twice on your keyboard to exit preview mode \
![][image14]  
15. Go to Build \> Gizmos \
![][image15]  
16. Search for Trail \
![][image16]  
17. Drag it into the scene, next to the throwable \
![][image17]  
18. With the gizmo select, go to the properties and change its scale to x: 0.2, y: 0.2, z: 0.2 \
![][image18]  
19. From the hierarchy, drag the gizmo inside the empty object \
![][image19]  
20. With the trail effect still selected, go to the properties, and change its position to x:0, y: 0, z: 0 \
![][image20]  
21. Enter preview mode again, and observe the trail effect that follows the object when in motion \
![][image21]