# Welcome inside my sick Brain

Take your time ([Time relativity](https://en.wikipedia.org/wiki/Theory_of_relativity)) exploring.

## Live Stream

 <!-- Tab links -->
<div class="tab">
  <button class="tablinks" onclick="openTabs(event, 'LiveStream')">Live Stream</button>
  <button class="tablinks" onclick="openTabs(event, 'LastCreation')">Last Creation</button>
  <button class="tablinks" onclick="openTabs(event, 'FTO_Update')">FTO Update</button>
</div>

<!-- Tab content -->
<div id="LiveStream" class="tabcontent">
  <iframe
    src="https://player.twitch.tv/?channel=wabteytv&parent=streamernews.example.com&muted=true"
    height="560"
    width="315"
    allowfullscreen>
  </iframe>
</div>

<div id="LastCreation" class="tabcontent">
  <iframe
    width="560"
    height="315"
    src="https://www.youtube.com/embed/M5qiXRKrXBc"
    title="YouTube video player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

<div id="FTO_Update" class="tabcontent">

  <p>It's' going well.</p>
  
</div>

## Fake Art

[![Drawing pad][1]][2]
[![Edit pad][3]][4]

[![Code pad][5]][6]
[![Pixel Art pad][7]][8]
[![Mystery pad][9]][10]

[1]:  https://user-images.githubusercontent.com/73140258/180214756-c8391d73-da8a-48bb-ae6b-b9ae5f8dcda6.png
[2]:  https://wabtey.github.io/Draw_Experiment/Draw "Danger Zone"
[3]:  https://user-images.githubusercontent.com/73140258/179639651-6ca67660-110d-4319-a36e-91632a15d096.png
[4]:  https://wabtey.github.io/EDIT/Edit "Do you mind be a viewer ?"
[5]:  https://user-images.githubusercontent.com/73140258/179639657-ad0df4d8-4844-4e22-a888-d025db2b7231.png
[6]:  https://wabtey.github.io/code "That's where I fake my way out"
[7]:  https://user-images.githubusercontent.com/73140258/179639645-61153ce7-00df-401d-82ff-bbf6c7698593.png
[8]:  https://fabinistere.github.io/ "The first step of ... kind of artists"
[9]:  https://user-images.githubusercontent.com/73140258/179639637-39cd1b27-807c-4c99-81fa-1fcd0acbb6ff.png
[10]: https://wabtey.github.io "Mystery pad"

<style>
/*
Style the buttons that are used to open the tab content
*/
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
}

/*
Change background color of buttons on hover
*/
.tab button:hover {
  background-color: #ddd;
}

/*
Create an active/current tablink class
*/
.tab button.active {
  background-color: #ccc;
}

/*
Style the tab content
*/
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>

<script>
function openTabs(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>