# CSS-Flexboxes

display: block;
----------------
Here display is the property and block is the value.
When we have to to arrange the boxes in block mode, we will use display: block;
![image](https://user-images.githubusercontent.com/48117959/223181815-37ac1cfb-8972-485e-afa0-d91b2746a4f7.png)


display:flex;
--------------
When we have to arrange the boxes in horizontal manner then we will use the display: flex; Here the boxes will take the maximum height among the three boxes.
![image](https://user-images.githubusercontent.com/48117959/223182483-e10936e3-f3fe-4feb-b818-b75604a3082d.png)


There are two axes that comes into picture, when we justifying horizontally and aligning vertically. There are "Main Axis"(horizontally) & "Cross Axis"(Vertically). Still the view will be considered as 1D only.


# Justify-content: When aligning the items horizontally we will use justify property with repect to display:flex;

justify-content: flex-start;
-----------------------------
Using this property, will align all the boxes horizontally at the start of the page.
![image](https://user-images.githubusercontent.com/48117959/223186725-d70263b7-e18a-4771-a2e9-151f37c9924d.png)


justify-content: flex-end;
--------------------------
Using this property, will align all the boxes horizontally at the end of the page.
![image](https://user-images.githubusercontent.com/48117959/223187235-8c3fcae8-d9b6-43fa-a48b-3260d9923b47.png)


justify-content: center;
-------------------------
Using this property, will align all the boxes horizontally at the center of the page.
![image](https://user-images.githubusercontent.com/48117959/223187710-5fe97b0f-b2fa-4c89-9755-a49714f50ff8.png)

justify-content: space-around;
-------------------------------
Using this property, will align all the boxes will leave the half the space to the sides as in between the space between the  elements i.e., containers.
![image](https://user-images.githubusercontent.com/48117959/235298961-b9c76da0-57b0-4e8a-a1fb-66b8b6533e7a.png)

justify-content: space-between:
-------------------------------
Using this property, will align all the boxes will leave the spaces towards the sides,it's just padding of the container.
![image](https://user-images.githubusercontent.com/48117959/235299115-5c240d56-4680-4487-aaf0-82844448cddb.png)

justify-content: flex-evenly:
-----------------------------
Using this property, will align all the boxes with equal amount of spaces in between them.
![image](https://user-images.githubusercontent.com/48117959/235299222-a9761b59-44e7-4d0b-ac45-425515734464.png)

# Align-Items: Property used to align the elements along the cross axis i.e, vertical axis.
Note: By-default align-items property will take the values of stretch i.e, align-items: stretch;

align-items: stretch:
----------------------
Property used to stretch the items along y-axis.We can observe no change in the output here.
![image](https://user-images.githubusercontent.com/48117959/235299370-81c8ee21-02a4-4456-bb49-03344a101262.png)

align-items: flex-start:
------------------------
Property used to stretch the items from the starting point of the y-axis.
![image](https://user-images.githubusercontent.com/48117959/235299420-3419f91f-c135-42b3-a363-75edb423fda5.png)

align-items: flex-end:
----------------------
Property used to stretch the items from the ending point of the y-axis.
![image](https://user-images.githubusercontent.com/48117959/235299483-3ce117a8-b992-4c47-90d1-30ed43401f00.png)

order:
-------
We can also change the order of the elements using order:1 but the drawback we can't change the dom of the particular element accordingly.
If we want to travel from one element to another  using tab it will consider the order of DOM rather than arrangements of elements in CSS & We have to keep in mind about the screen readers too as accessibility is missing here. 

![image](https://user-images.githubusercontent.com/48117959/235300165-fe47a170-9a76-4b8d-84d3-def56d40518e.png)

align-content:
--------------
align-content property sets the distribution of space between and around content items along a flexbox's cross-axis or a grid's block axis.

align-content: start; /* Pack items from the start */
![image](https://user-images.githubusercontent.com/48117959/235300476-98f21966-f656-48bb-b889-e491536b328e.png)

align-content: center; /* Pack items around the center */
align-content: end; /* Pack items from the end */
align-content: flex-start; /* Pack flex items from the start */
align-content: flex-end; /* Pack flex items from the end */

flex-wrap:
---------
As the web page shrinks, the elements start missing their original width. So inorder to make it sustain , we can use flex-wrap property.
The flex items break into multiple lines. 
The cross-start is either equivalent to start or before depending flex-direction value and the cross-end is the opposite of the specified cross-start.
![image](https://user-images.githubusercontent.com/48117959/235300563-749658fc-b2e8-4faa-9831-947c1b3a43fa.png)

flex-nowrap:
------------
The flex items are laid out in a single line which may cause the flex container to overflow. 
The cross-start is either equivalent to start or before depending on the flex-direction value. This is the default value.
![image](https://user-images.githubusercontent.com/48117959/235300631-e7bc88c1-6317-4e79-953e-9223b2e07971.png)

flex-reverse:
-------------
Behaves the same as wrap but cross-start and cross-end are permuted.
![image](https://user-images.githubusercontent.com/48117959/235300947-f2717c52-aed3-4ca8-925a-091f8e2b023a.png)











