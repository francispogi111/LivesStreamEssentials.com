<!DOCTYPE html>
<html lang="en">
<head>
  <title>Streaming</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body, h1, h2, h3, h4, p {
      font-family: 'Poppins', sans-serif;
      color: #333;
    }
    .w3-bar, .footer {
      background-color: #242424;
    }
    .w3-bar a {
      color: #f1f1f1;
    }
    .w3-bar a:hover {
      background-color: #575757;
    }
    h1, h2, h3, h4 {
      font-weight: 600;
      color: #000;
    }
    p {
      font-weight: 300;
      color: #666;
    }
    .band {
      padding: 50px;
      background-color: #f9f9f9;
    }
    .section {
      padding: 32px 16px;
    }
    .footer {
      padding: 64px;
      background-color: #242424;
      color: #fff;
      text-align: center;
    }
    img {
      max-width: 100%;
      height: auto;
    }
  </style>
</head>
<body>

<!-- Navbar -->
<div class="w3-bar w3-black w3-card">
  <a href="javascript:void(0)" class="w3-bar-item w3-button w3-wide" onclick="openTab(event, 'Home')">HOME</a>
  <div class="w3-right">
    <a href="javascript:void(0)" class="w3-bar-item w3-button" onclick="openTab(event, 'About')">About</a>
    <a href="javascript:void(0)" class="w3-bar-item w3-button" onclick="openTab(event, 'Types')">Types of Streaming</a>
    <a href="javascript:void(0)" class="w3-bar-item w3-button" onclick="openTab(event, 'Platforms')">Platforms</a>
    <a href="javascript:void(0)" class="w3-bar-item w3-button" onclick="openTab(event, 'Viewers')">Viewers Analysis</a>
  </div>
</div>

<!-- Home Section (Updated Welcome Message) -->
<div id="Home" class="w3-container w3-padding-64">
  <h1 class="w3-center">Welcome to the Group 1Ones Website</h1>
  <div class="w3-row-padding">
    <p>
      We are delighted to have you visit our streaming information hub. This site will provide you with insights into the world of streaming, 
      from live broadcasting to on-demand content. Explore the various types of streaming, learn about popular platforms, and dive into 
      viewer analysis to understand the current trends. Stay connected, stay informed, and enjoy the content we have curated just for you!
    </p>
    <p>
      Streaming has transformed the way we consume media, and our goal is to guide you through this dynamic industry. Whether you're new to streaming 
      or an experienced user, there's something here for everyone. Thank you for visiting, and we hope you enjoy your time on our website.
    </p>
  </div>
</div>

<!-- About Section -->
<div id="About" class="w3-container w3-padding-64" style="display:none">
  <h1 class="w3-center">About Streaming</h1>
  <div class="w3-row-padding">
    <p>
      Streaming refers to any media content – live or recorded – delivered to computers and mobile devices via the internet and played back in real time. 
      This includes podcasts, webcasts, movies, TV shows, and music videos. The concept of streaming has transformed how content is consumed globally, 
      enabling users to access their favorite shows, music, and even interactive events on-demand.
    </p>
  </div>
</div>

<!-- Types of Streaming Section -->
<div id="Types" class="w3-container w3-light-grey w3-padding-64" style="display:none">
  <h1 class="w3-center">Types of Streaming Content</h1>
  <div class="w3-row-padding">
    <div class="w3-col l4 m6 w3-margin-bottom">
      <h3>Podcasts</h3>
      <p>
        Podcasts deliver audio content on demand and are one of the most versatile and rapidly growing forms of media. They cover everything from news to comedy 
        and interviews, making them highly popular among passive listeners.
      </p>
    </div>
    <div class="w3-col l4 m6 w3-margin-bottom">
      <h3>Live Streaming</h3>
      <p>
        Live streaming allows real-time interaction with audiences. Platforms like Twitch and YouTube Live dominate this space, with streamers covering gaming, 
        interviews, and even live events like concerts.
      </p>
    </div>
    <div class="w3-col l4 m6 w3-margin-bottom">
      <h3>Webcasts</h3>
      <p>
        Webcasts combine video and audio, typically used for live events like webinars, corporate presentations, and educational seminars.
      </p>
    </div>
  </div>
</div>

<!-- Platforms Section -->
<div id="Platforms" class="w3-container w3-padding-64" style="display:none">
  <h1 class="w3-center">Platforms for Streaming</h1>
  <div class="w3-row-padding">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <h3>YouTube</h3>
      <p>YouTube is the largest video-sharing platform in the world, used for everything from vlogs and music videos to live streams and tutorials.</p>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <h3>Twitch</h3>
      <p>Twitch is focused primarily on gaming, but it's also a popular platform for live chat, interviews, and creative streams.</p>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <h3>Facebook</h3>
      <p>Facebook includes live streaming services, often used for events and community engagement.</p>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <h3>Netflix</h3>
      <p>Netflix is the leading subscription-based streaming platform for movies, TV shows, and documentaries.</p>
    </div>
  </div>
</div>

<!-- Viewers Analysis Section -->
<div id="Viewers" class="w3-container w3-light-grey w3-padding-64" style="display:none">
  <h1 class="w3-center">Viewers Analysis by Streaming Category</h1>
  <div class="w3-row-padding">
    <div class="w3-col l6 w3-margin-bottom">
      <h3>Interviews</h3>
      <p>
        Interviews on platforms like YouTube continue to draw large viewership, especially when featuring influencers or celebrities.
      </p>
    </div>
    <div class="w3-col l6 w3-margin-bottom">
      <h3>Live Streaming</h3>
      <p>
        Events like gaming competitions and live chats are huge draws. Influencers often pull in thousands of concurrent viewers during live streams.
      </p>
    </div>
    <div class="w3-col l6 w3-margin-bottom">
      <h3>Podcasts</h3>
      <p>
        The podcasting space continues to grow, with more than 62% of listeners tuning in to regular podcasts. The conversational nature of podcasts makes 
        them a hit with people seeking news and entertainment.
      </p>
    </div>
  </div>
</div>

<!-- Script for Tab Navigation -->
<script>
  function openTab(evt, tabName) {
    var i, x, tablinks;
    x = document.getElementsByClassName("w3-container");
    for (i = 0; i < x.length; i++) {
      x[i].style.display = "none";
    }
    document.getElementById(tabName).style.display = "block";
    
    // Remove the active highlight from all tab links
    tablinks = document.getElementsByClassName("w3-bar-item");
    for (i = 0; i < tablinks.length; i++) {
      tablinks[i].classList.remove("w3-black");
    }

    // Highlight the active tab
    evt.currentTarget.className += " w3-black";
  }

  // Default display on page load
  document.getElementById("Home").style.display = "block"; // Show Home section by default
</script>

</body>
</html>
