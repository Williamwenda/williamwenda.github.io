---
layout: default
title: Videos & Robots
---

<!-- Lightbox overlay -->
<div id="lightbox" onclick="this.style.display='none'" style="
  display:none;
  position:fixed;
  inset:0;
  background:rgba(0,0,0,0.85);
  z-index:9999;
  cursor:zoom-out;
  align-items:center;
  justify-content:center;
">
  <img id="lightbox-img" src="" alt="" style="
    max-width:90vw;
    max-height:90vh;
    border-radius:6px;
    box-shadow:0 8px 40px rgba(0,0,0,0.6);
    object-fit:contain;
  ">
  <span style="position:absolute;top:18px;right:28px;color:#fff;font-size:2em;font-weight:300;line-height:1;cursor:pointer;" onclick="document.getElementById('lightbox').style.display='none'">&times;</span>
</div>

<style>
  .zoomable {
    cursor: zoom-in;
    transition: transform 0.2s, box-shadow 0.2s;
    border-radius: 4px;
    display: block;
  }
  .zoomable:hover {
    transform: scale(1.03);
    box-shadow: 0 4px 16px rgba(0,0,0,0.2);
  }
</style>

<script>
function openLightbox(src, alt) {
  var lb = document.getElementById('lightbox');
  var img = document.getElementById('lightbox-img');
  img.src = src;
  img.alt = alt;
  lb.style.display = 'flex';
}
document.addEventListener('keydown', function(e) {
  if (e.key === 'Escape') document.getElementById('lightbox').style.display = 'none';
});
</script>

## Interesting Videos

<table style="border:none;border-collapse:collapse;">
<tr style="border:none;">
<td style="border:none;padding:8px;vertical-align:top;width:50%;">
  <strong>Autonomous Drone Racing Competition</strong><br>
  <a href="https://youtu.be/8a0MNig_Kc8" title="Autonomous Drone Racing">
    <img src="/utadr.jpeg" alt="Autonomous Drone Racing" style="width:100%;max-width:340px;">
  </a>
</td>
<td style="border:none;padding:8px;vertical-align:top;width:50%;">
  <strong>UWB-Inertial Pedestrian Tracking</strong><br>
  <a href="http://tiny.cc/uwb_tdoa_sys" title="UWB-Inertial Tracking">
    <img src="/uwb_tracking.jpg" alt="UWB-Inertial Tracking" style="width:100%;max-width:340px;">
  </a>
</td>
</tr>
<tr style="border:none;">
<td style="border:none;padding:8px;vertical-align:top;width:50%;">
  <strong>Christmas Video (2020)</strong><br>
  <a href="https://www.youtube.com/watch?v=54fA6etaOFo" title="Christmas Video (2020)">
    <img src="/xmas_20.png" alt="Christmas Video (2020)" style="width:100%;max-width:340px;">
  </a>
</td>
<td style="border:none;padding:8px;vertical-align:top;width:50%;">
  <strong>Welcome to the Dynamic Systems Lab (2018)</strong><br>
  <a href="https://www.youtube.com/watch?v=KzGW4S400gU" title="Welcome (2018)">
    <img src="/utias_welcome.png" alt="Welcome (2018)" style="width:100%;max-width:340px;">
  </a>
</td>
</tr>
</table>

---

## Robot Platforms I Have Worked With

<table style="border:none;border-collapse:collapse;">
<tr style="border:none;">
<td style="border:none;padding:8px;vertical-align:top;width:50%;">
  <strong>Lidar-based drone platform</strong><br>
  <img class="zoomable" src="/lidar_drone.jpg" alt="Lidar drone" style="width:100%;max-width:340px;" onclick="openLightbox(this.src, this.alt)">
</td>
<td style="border:none;padding:8px;vertical-align:top;width:50%;">
  <strong>Visual-inertial drone racing platform</strong><br>
  <img class="zoomable" src="/vision_drone.jpeg" alt="Vision drone" style="width:100%;max-width:340px;" onclick="openLightbox(this.src, this.alt)">
</td>
</tr>
<tr style="border:none;">
<td style="border:none;padding:8px;vertical-align:top;width:50%;">
  <strong>Lidar sensing platform (Sense Cube)</strong><br>
  <img class="zoomable" src="/sense_cube.jpg" alt="Sense Cube" style="width:100%;max-width:340px;" onclick="openLightbox(this.src, this.alt)">
</td>
<td style="border:none;padding:8px;vertical-align:top;width:50%;">
  <strong>a Clearpath Warthog UGV for outdoor autonomous navigation</strong><br>
  <img class="zoomable" src="/warthog_yzd.jpg" alt="Warthog UGV" style="width:100%;max-width:340px;" onclick="openLightbox(this.src, this.alt)">
</td>
</tr>
<tr style="border:none;">
<td style="border:none;padding:8px;vertical-align:top;width:50%;">
  <strong>A fleet of customized drones with CF-Bolt flight controller</strong><br>
  <img class="zoomable" src="/drone_fleet.jpg" alt="Drone fleet" style="width:100%;max-width:340px;" onclick="openLightbox(this.src, this.alt)">
</td>
<td style="border:none;padding:8px;vertical-align:top;width:50%;">
  <strong>UWB-Inertial handheld device with Raspberry Pi 4B</strong><br>
  <img class="zoomable" src="/uwb_tracking_sys.jpeg" alt="UWB tracking system" style="width:100%;max-width:340px;" onclick="openLightbox(this.src, this.alt)">
</td>
</tr>
</table>

<p>&nbsp;</p>
