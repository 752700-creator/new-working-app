<!DOCTYPE html>
<html>
<head>
  <title>Social Tracker</title>
  <style>
    body {
      font-family: Arial;
      padding: 20px;
      background: #f5f5f5;
    }
    .box {
      background: white;
      padding: 15px;
      margin: 10px 0;
      border-radius: 10px;
    }
    input {
      display: block;
      margin: 5px 0;
      padding: 8px;
      width: 100%;
    }
  </style>
</head>
<body>

<h1>Social Media Tracker</h1>

<div class="box">
  <h2>TikTok</h2>
  <input id="ttUser" placeholder="Username">
  <input id="ttFollowers" placeholder="Followers">
  <input id="ttViews" placeholder="Views">
  <input id="ttLikes" placeholder="Likes">
  <button onclick="loadTikTok()">Load TikTok Profile</button>
  <div id="tiktokEmbed"></div>
</div>

<div class="box">
  <h2>Instagram</h2>
  <input id="igUser" placeholder="Username">
  <input id="igFollowers" placeholder="Followers">
  <input id="igViews" placeholder="Views">
  <input id="igLikes" placeholder="Likes">
</div>

<div class="box">
  <h2>Combined Views</h2>
  <p id="totalViews">0</p>
</div>

<button onclick="save()">Save</button>

<script>
function updateTotal() {
  let ttv = Number(document.getElementById("ttViews").value) || 0;
  let igv = Number(document.getElementById("igViews").value) || 0;
  document.getElementById("totalViews").innerText = ttv + igv;
}

document.querySelectorAll("input").forEach(i => {
  i.addEventListener("input", updateTotal);
});

function save() {
  const data = {
    ttFollowers: ttFollowers.value,
    ttViews: ttViews.value,
    ttLikes: ttLikes.value,
    igFollowers: igFollowers.value,
    igViews: igViews.value,
    igLikes: igLikes.value
  };
  localStorage.setItem("stats", JSON.stringify(data));
  alert("Saved!");
}

function loadTikTok() {
  let user = document.getElementById("ttUser").value.replace("@", "");
  let url = "https://www.tiktok.com/@" + user;

  document.getElementById("tiktokEmbed").innerHTML = `
    <blockquote class="tiktok-embed" cite="${url}" data-unique-id="${user}" data-embed-type="creator"></blockquote>
  `;

  let script = document.createElement("script");
  script.src = "https://www.tiktok.com/embed.js";
  document.body.appendChild(script);
}
</script>

</body>
</html>
