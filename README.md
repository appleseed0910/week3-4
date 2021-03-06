# Week3-4 Checkpoint

DGM6410 Game Design Tech Lab

This repository contains:

<ul>
  <li>Updated Game file(.html page)</li>
  <li>Media files(sound, img)</li>
 
<li>Supplementary docmentations:<ol>
<li>Inquiry</li>
<li>ResearchPlan</li>
<li>Solution</li>
<li>Expectation</li>
</ol></li>

</ul>

Among these two weeks, for practicing more practical small functions in Twine, I temporarily gave up making changes on the original entire big story.
<br>Instead, I created some new <em>'sand box'</em> as my experiment mice.

<h3>Inquiry</h3>
Practice multiple usages provided internal Twine. It contains:
<ul style="p{line-height:90%;}">
  <li>Examine choices types</li>
  <li>Using Variables</li>
  <li>Inventory</li>
  <li>Adding Images</li>
  </ul>
  
<h3>ResearchPlan</h3>
I bought the book <a href="https://smile.amazon.com/gp/product/0789756641/ref=oh_aui_detailpage_o02_s00?ie=UTF8&psc=1">Writing Interactive Fiction with Twine</a>
<br>My research plan would start oriented on this book, simultaneously supported by online tutorials documentation and videos.

<h3>Solution</h3>
Here are some tutorials and solutions I found for each inquiry.
<br><br>
<ol>


<br><li><b>Exmaine choices types</b>
 <br><em>Book chapter 2 Using Choice to Create Agency</em>
<br>In this chapter, the author demonstrates different types and usages of choice, which is the main tool for users to explore a Twine story. I made a choice type exclusive practice file in Twine.
<br>In this sandbox, I tried to create Preference Choices(the first node), Value Choices(Burger), Adventure Choices(Chinese food), Ethical Choices(Pizza), and Exploratory Choices(Salad).
Below Burger branch, I also added some detailed information choices about two burger shops separately.
</li>

<br><li><b>Using Variables</b>
  <br><em>Book chapter 5 Building Objects with Variables</em>
  <br>This part is not quite difficult to start and memorize. 
  <br>Here are some notes that I took:
  <ol>
    <li>Create variables: (set: $variableName to "string"/number/boolean)</li>
  <li>Print varibales: (pring: $variableName)</li>
  <li>Variables calculating: (set $variableName to $variableName +/-/*/ value)</li>
  <li>Conditional Statement: (if $variableName is "string"/number/boolean) (else:)</li>
  <li>Elseif conditional statement: (if $variableName is "string"/number/boolean) (elseif: $variableName is "string"/number/boolean)</li>
  <li>History: (history:) This one prints out all the passges that the player has ever been, which is a little odd to use.</li>
  </ol>
  <br><strong>To sum up:</strong> to make variables more useful and practically engaged with the story itself, it requires a completed story to hold these variables and endow meanings to them.
  <br>Also, I think to make a list to sort out all the variables and their corresponding level would be very helpful.
 </li>
 
<br><li><b>Inventory</b>
 <br><em>Book chapter 9 Maintaining an Inventory</em>
  <br>This chapter is a little more difficult than others for me. Though how to write the commands is clear enough.
  <br>Set up an inventory: (set: $inventoryName to (array:))
  <br>Add elements to the inventory: (set: $inventoryName to $inventoryName + (array:"element"))
  <br>Drop elements to the inventory: (set: $inventoryName to $inventoryName - (array:"element"))
  <br>But it seems I met some problems when I tried to connect links with add/drop functions. And also, there're some more statements need to pay attention such as "join".
  <br>Basically, Twine uses array concept to control the inventory, I think it's more suitable to make the items inside the player's inventory become 'triggers' to other events instead more further complicated usages.
</li>
  
<br><li><b>Adding Images</b>
 <br><em>Book chapter 16 Adding Images in a New Format</em>
  <br>In this chapter, the author explains how to add images under SugarCube story format, and mentions several supplementary functions of images as well. 
  <br>Such as to attach different choices with different images(setter links):[img["link"][Checkout][$variableName to "imageContent"]]
  <br>Make mouseover information on images: [img["additional information"|"image link"]]
</li>




  </ol>

<h3>Expectation</h3>
Here are some potential inquiries for the next week.
<br><em>Book chapter 12 Making a Role-Playing Game</em>
<br><em>Book chapter 13 Combat and Consequences in Role-Playing Games</em>
<b>Examine the story structure</b>
  <br><em>Book chapter 6 Stasis, Catalyst, and Climax: Understanding Story Arc</em>
  <br><em>Book chapter 7 Exploring Interactive Fiction Genres</em>
  <br><em>Book chapter 14 Wiggling Words: Changing the Text Appearance</em>
  <br><em>Book chapter 15 Story Style: Changing the Game Appearance in Harlowe</em>
<br>
