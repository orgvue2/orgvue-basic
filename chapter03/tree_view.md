# Tree View

##Expand to level

Navigate to Tree View. We can’t see much detail in the current View. So let’s start off making things more manageable by filtering to Level 3.

![](3-001.treeviewfilter.png)

Now it is much manageable. The ‘Expand to level’ dropdown lets you expand and collapse the tree to the selected Depth.

![](3-002.TVexpandlevel.png)

#Colour by

1. Apply colouring using the Color Control (colour by “Department”)

  ![](3-003.colourcontrol.png)

  **The colour scheme you apply in the Side Panel applies to all views.**

2. Hovering over a department in the Side Panel will highlight that department in the Tree

![](3-004.TVdepartment.png)

##Summary Card

1. Open up the Card Panel in the Side Panel and choose the card type depending on the type of data you want to highlight. In this example, ‘Summary’ card has been selected. Summary card is useful when you want to display multiple properties for each node. (NB ‘Icon’ is the default card type)

2. Choose ‘Title’, ‘Subtitle’ and other properties you want to show on cards

![](3-005.summarycard.png)

##Scaled Card

1. Now choose ‘Scaled’ card from the dropdown list

2. Choose a ‘Title’, ‘Subtitle’ and ‘Size by’ to configure the Scaled card as you want. Scaled card helps to give a sense of proportion within the familiar org chart picture

![](3-006.scaledcard.png)

##Tree layout

OrgVue helps you represent hierarchical structures in your data in efficient and beautiful ways. Try different layouts using ‘Tree layout’ dropdown.

![](3-007.treelayout.png)

##Zoom in & out

OrgVue makes it easy to see as much detail as you need.

* 

You can also move the Tree vertically and horizontally by left-clicking the screen and dragging anywhere in the canvas

* You can also zoom in or out using the mouse wheel

![](3-008.zoom.png)



##Change reporting structure using Drag-and-Drop

Simply Drag and Drop a node or group of nodes to make changes to your tree. 

Executive Assistant currently reports to CEO. Now you want to make Executive Assistant and all their descendants report to CFO.

1. Drag the Executive Assistant and drop onto CFO (waiting until the red ‘x’ by the cursor is gone)

  ![](3-009.dragdrop1.png)

2. When the ‘Confirm’ Dialogue appears, click ‘OK’ to make Executive Assistant (and their descendants) a child of CFO

  ![](3-010.dragdrop2.png)

3. Now Executive Assistant (and their reports) reports up through the CFO

![](3-011.dragdrop3.png)

##Drill through hierarchies in Tree View
1. Expand to just Level 1

2. When you hover the mouse over a node 5 icons will appear underneath it

3. Drill down the hierarchy 1 level by clicking ![](3-012.droparrow.png)

![](3-013.hierarchy.png)

|Button|Function|
|---|---|
| ![](3-014A.arrow1.png) | Roll back all descendants, only the CEO node will be shown|
| ![](3-014B.arrow2.png) | Roll up one level at a time in the tree|
| ![](3-014C.arrow3.png) | Roll down one level at a time in the tree|
| ![](3-014D.arrow4.png) | The entire organisation will be shown (full tree expansion) |
| ![](3-014E.arrow5.png) | Clicking this will bring up ‘New Node’ Dialogue|


##Exercise 1: Create the visuals described below in Tree Vie

1. In Tree View, set your data to ‘Level 3’. Then, create a view that shows the organisation **Scaled by**: 
  
  a) “Total Payroll Cost”

  then

  b) “Span of control” (select *“Outgoing Count”*)

2. Show the whole of your organisation as a **Sunburst** coloured by “Performance Ranking”

3. Show the top 2 Levels of the organisation with a **Summary card** with the following properties (in the same order), and coloured by “Absence Days”

* Title: “Role”

* 
Subtitle: “Department” 

* 
Other Properties: “Full name”, “Gender”, “Grade”, “Current Salary”, “Performance ranking”

##Answer 1.1:

**Hint**: Level 3, Tree layout, Scaled card, Size by “Total Payroll cost” and then after by “Outgoing count”

![](3-015.answer1.11.png)
![](3-016.answer1.12.png)
##Answer 1.2:


**Hint**: Level 9, Sunburst layout, Colour by ‘Measure’ and “Performance ranking”, select a palette showing RAG status

![](3-017.answer1.2.png)

##Answer 1.3


**Hint**: Level 2, Tree layout, Summary card, display “Role” as title, “Department” as subtitle, tick “Full name”, “Gender”, “Grade”, “Current Salary”, “Performance ranking” from the list. Colour by “Absence days”

![](3-018.answer1.3.png)


##Exercise 2: Make corrections to the reporting structure

1. Set Tree View to only look at the first 3 Levels and view as a ‘Compact’ tree (don’t forget to Refresh the data if necessary)

2. Set the Card to ‘Icon’ and the subtitle to “Role”

3. Colour the nodes by the Dimension “Department”

4. Do you notice anything not quite right in the reporting structure? Re-order or re-parent any irregularities observed

##Answer 2:

Notice that COO incorrectly reports to the Executive Assistant – Make COO report to CEO by Drag-and-Drop.

![](3-019.answer21.png)

Now COO reports to CEO.

![](3-020.answer22.png)








