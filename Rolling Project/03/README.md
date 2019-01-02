<p><strong>Assignment 03 &ndash; Chat Tree Component</strong></p>
<p><span style="font-weight: 400;">During this assignment you are requested to develop a tree UI component using vanilla DOM/jQuery API. The tree component displays all users and groups inside the chat application. Later, we will integrate this component into a full Angular application.</span></p>
<p><span style="font-weight: 400;">Download the starter code for this assignment from our Github repository at </span><a href="https://github.com/Trainologic/JSBootcamp3/tree/master/assignments/Assignment%2003/src"><span style="font-weight: 400;">https://github.com/Trainologic/JSBootcamp3/tree/master/assignments/Assignment%2003/src</span></a></p>
<p><span style="font-weight: 400;">Once downloaded, you should execute </span><strong>npm install</strong><span style="font-weight: 400;"> followed by </span><strong>npm start</strong><span style="font-weight: 400;">. The following page will be displayed</span>
<p>
    <img src="1.jpg" />
</p>
</p>
<p><span style="font-weight: 400;">Inside the right pane there is a sample of a JSON structure that can be loaded into the tree using the </span><strong>load</strong><span style="font-weight: 400;"> method. Please explore the JSON and ensure you understand its structure</span></p>
<p><span style="font-weight: 400;"></span><span style="font-weight: 400;">Once clicking the </span><strong>Load</strong><span style="font-weight: 400;"> button, the JSON content is loaded into the tree component creating the following user interface</span></p>
<p>
    <img src="2.jpg" />
</p>
<p><span style="font-weight: 400;"></span></p>
<p><span style="font-weight: 400;">The end user can navigate through the user/group hierarchy. The following navigation commands are supported</span></p>
<h2>&nbsp;</h2>
<p><strong>Clicking a group/user</strong><span style="font-weight: 400;"> &ndash; Clicking a group or user node selects this node. A selection is displayed as a rectangular background around the node. For example, after clicking the </span><strong>Ori</strong><span style="font-weight: 400;"> node the tree looks like</span></p>
<p>
    <img src="3.jpg" />
</p>
<h2>&nbsp;</h2>
<p><strong>Double clicking a group node</strong><span style="font-weight: 400;"> &ndash; Double clicking a group node will make it expand or collapse. For example, double clicking the </span><strong>Friends</strong><span style="font-weight: 400;"> node above makes it expand and the tree will look like</span></p>
<p>
    <img src="4.jpg" />
</p>
<p><span style="font-weight: 400;">Double clicking it again will make it collapse again</span></p>
<p><span style="font-weight: 400;"></span><strong>Pressing down key</strong><span style="font-weight: 400;"> &ndash; Pressing the down key moves the selection one node below. Continue with the above screen shot, pressing the down key changes the selected node from </span><strong>Friends</strong><span style="font-weight: 400;"> to </span><strong>Best Friends</strong></p>
<p>
    <img src="5.jpg" />
</p>
<p><strong>Pressing up key</strong><span style="font-weight: 400;"> &ndash; Pressing the up key moves the selection one node above. </span></p>
<p><span style="font-weight: 400;"></span></p>
<p><strong>Pressing right key - </strong><span style="font-weight: 400;">Pressing the right key on a group node makes that group expand. Pressing the same key on a user node has no effect. Continue with our above screen shot, pressing the right key makes the </span><strong>Best Friends</strong><span style="font-weight: 400;"> group expand</span></p>
<p>
    <img src="6.jpg" />
</p>
<p><strong>Pressing left key</strong><span style="font-weight: 400;"> &ndash; Pressing a left key on a group node makes that group collapse. If the group is already collapsed than the selection moves to the parent node. For example, continue with above screen shot, pressing left key makes the </span><strong>Best Friends</strong><span style="font-weight: 400;"> node to collapse and pressing left key again makes the selection move to the </span><strong>Friends</strong><span style="font-weight: 400;"> node</span></p>
<p><strong>Pressing enter &ndash; </strong><span style="font-weight: 400;">Has no effect when pressed on a user node. However, when pressed on a group node it makes that group expand/collapse. If it is collapsed, it will be expanded and vice versa </span></p>
<h2><br /><br /></h2>