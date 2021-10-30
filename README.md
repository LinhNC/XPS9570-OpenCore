![](https://raw.githubusercontent.com/LinhNC/XPS9570-OpenCore/main/Capture.png)
<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="XPS9570OpenCore_0"></a>XPS9570 OpenCore</h1>
<p class="has-line-data" data-line-start="1" data-line-end="3">XPS 9570 Hackintosh with OpenCore 0.7.4<br>
Monterey (12.0.1), BigSur (11.6.1), Catalina (10.15.7) on a Dell XPS 9570 with Touch 4k Screen</p>
<blockquote>
<p class="has-line-data" data-line-start="4" data-line-end="6">Monterey (12.0.1) <br> BigSur (11.6.1) <br> Catalina (10.15.7)</p>
</blockquote>

<h4 class="code-line" data-line-start=7 data-line-end=8 ><a id="Hardware_configuration_7"></a>Hardware configuration:</h4>
<p class="has-line-data" data-line-start="8" data-line-end="18">Dell XPS 9570<br>
CPU: Intel i7-8750H<br>
Memory: 32GB 2x SK Hynix HMA82GS6CJR8N-VK<br>
Display: Touch 4k Sharp<br>
SSD: Samsung 970 EVO Plus NVMe M.2 SSD 1TB<br>
Trackpad: Synaptics SYNA2393<br>
Touchscreen: Wacom WCOM488F<br>
Sound: Realtek ALC3266 (similar to ALC298)<br>
Wifi Card: replaced with DW 1560 - BCM94352Z<br>
Battery: Dell 6GTPY battery (11.4V, 8083mAh, 97Wh stated capacity, reports as 7488mAh)</p>
<h4 class="code-line" data-line-start=18 data-line-end=19 ><a id="Software_environment_18"></a>Software environment:</h4>
<p class="has-line-data" data-line-start="19" data-line-end="21">macOS dual-booting with Windows 10<br>
DELL BIOS: 1.21</p>
Specical Thanks To @xxxzc
<br>
<blockquote>
For 1080p Screen need to modify your config.plist:<br>
- Find uiscale and change its value to AQ== <br>
- Find dpcd-max-link-rate and change its value to CgAAAA==<br>
</blockquote>



