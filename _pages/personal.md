---
layout: personal
title: Personal
permalink: /personal/
profile:
  align: left
  image: per_uzh.jpg
  image_circular: false # crops the image to make it circular

news: false  # includes a list of news items
latest_posts: false # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page

nav: true
nav_order: 3
---

My integration into Swiss society includes hiking, skiing, and somewhat reluctant beginner-level climbing.

<div style="position:relative; margin: 1.5rem 0; border-radius: 6px; overflow:hidden; background:#000;">
  <img id="mtn-img" src="/webpage/assets/img/mountains/mountain_1.jpg" style="width:100%; max-height:480px; object-fit:cover; display:block;">
  <button onclick="mtnSlide(-1)" style="position:absolute; left:0; top:0; height:100%; width:48px; background:rgba(0,0,0,0.4); border:none; color:#fff; font-size:1.5rem; cursor:pointer;">&#8249;</button>
  <button onclick="mtnSlide(1)" style="position:absolute; right:0; top:0; height:100%; width:48px; background:rgba(0,0,0,0.4); border:none; color:#fff; font-size:1.5rem; cursor:pointer;">&#8250;</button>
  <div style="position:absolute; bottom:8px; width:100%; text-align:center; color:rgba(255,255,255,0.7); font-size:0.8rem;"><span id="mtn-counter">1 / 10</span></div>
</div>

<script>
var mtnPhotos = [
  "/webpage/assets/img/mountains/mountain_1.jpg",
  "/webpage/assets/img/mountains/mountain_2.jpg",
  "/webpage/assets/img/mountains/mountain_3.jpg",
  "/webpage/assets/img/mountains/mountain_4.jpg",
  "/webpage/assets/img/mountains/mountain_5.jpg",
  "/webpage/assets/img/mountains/mountain_6.jpg",
  "/webpage/assets/img/mountains/mountain_7.jpg",
  "/webpage/assets/img/mountains/mountain_8.jpg",
  "/webpage/assets/img/mountains/mountain_9.jpg",
  "/webpage/assets/img/mountains/mountain_10.jpg"
];
var mtnIdx = 0;
function mtnSlide(dir) {
  mtnIdx = (mtnIdx + dir + mtnPhotos.length) % mtnPhotos.length;
  document.getElementById("mtn-img").src = mtnPhotos[mtnIdx];
  document.getElementById("mtn-counter").textContent = (mtnIdx + 1) + " / " + mtnPhotos.length;
}
</script>

Current dependents:

<div class="row mt-3 mb-3">
  <div class="col-sm-6">
    <img src="/webpage/assets/img/dog_sunset.jpg" class="img-fluid rounded z-depth-1" alt="Dog watching the sunset">
  </div>
  <div class="col-sm-6">
    <img src="/webpage/assets/img/dog_peak.jpg" class="img-fluid rounded z-depth-1" alt="Dog on mountain peak">
  </div>
</div>

<div class="clearfix"></div>

Coauthors: [Jiyuan Huang](https://huang-justin.com/), [Thomas Richter](https://www.zhaw.ch/de/ueber-uns/person/rico), [Yuanyuan Gao](https://www.df.uzh.ch/en/people/phd-candidates/yuanyuan-gao.html), [Hans Hvide](https://sites.google.com/site/hanshvide/home), [Andriy Bodnaruk](https://business.uic.edu/profiles/andriy-bodnaruk/)
