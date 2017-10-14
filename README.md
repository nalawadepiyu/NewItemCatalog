<h1> Item Catalog </h1>

<h2> About </h2>
<p>
  The Item Catalog project consists of developing an application that provides a list of items within a variety of categories, as well as provide a user registration and authentication system.
</p>
<br>
<h2>Files</h2>
<ul>
  <li>database_setup.py: conatains schema</li>
  <li>details.py: conatains data needs to be filled up in database </li>
  <li>catalogproject.py : contains methods for login, logout, create, edit update, delete item in categories
  <br> Also, contains respective routes for every methods  </li>
 </ul>
 <br>
 <h2>Dependencies</h2>
 <ul>
 <li>Vagrant 1.8.5</li>
 <li>Virtual box 5.1.28</li>
 <li>Vagrantfile</li>
 </ul>
<br>
<h2>Steps: </h2>
<ul>
  <li>Install virtual box and vagrant mentioned versions </li>
  <li>Add settings in vagrant file to install required packages</li>
  <li>Run vagrant up</li>
  <li>Run vagrant ssh</li>
  <li>Run database_setup.py file </li>
  <li>Run details.py file</li>
  <li>Run catalogproject.py so that application will run on localhost:8000</li>
  <li>Use Google Login </li>
</ul>
<br>
<h2>JSON Endpoints</h2>
<ul>
  <li>allcategoriesJSON : Displays all categories </li>
  <li>categoryMenuJSON : Displays all items with respect to that category</li>
  <li>itemsMenuJSON : Displays description of items </li>
</ul>
