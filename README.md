### Multi-Monitor XP vs. W7

using 3 monitors: </br>
2x FullHD + 1x 4K TV at [QXGA 2048x1536](https://en.wikipedia.org/wiki/Graphics_display_resolution#QXGA) </br>
dual GPU. </br>
AMD Radeon HD6570 works ok 4K in XP, FullHD on W7x32, driver 13.12 or 14.4 the latest, </br>
NVIDIA GT 740 works FullHD in XP, 4K in W7x32  </br>
board Asus P5W DH, chipset: 975x, socket lga775, CPU Q6600 </br>

software available for Win & Mac in that era 2000 - 2010, </br>
was done with OpenGL Video drivers, for easy code porting / compatibility. </br>
but...</br>
XP was designed for DirectX 9.0c, Not OpenGL </br>
XP does Not work in Multi-Monitor using OpenGL </br>
DirectX drivers work Ok in XP, OpenGL only works 1x GPU, or AMD or NVIDIA </br>
depends whats the Default Monitor selected. </br>

GT 740 is a bit better in 3D vs. HD6570 </br>
testing with [Unigine Tropics v1.0 2008 v1.3 2010](https://benchmark.unigine.com/tropics) </br>
Not Full Screen, windowed 1340x768,
Tropics allows to select video driver: OpenGL vs. DirectX9 </br>
and move the 3D window to all monitors </br>
when drivers are ok, all windows have fluid graphics. </br>
when Not, 3D gets frozen. </br>

if want multi-monitor, and software only has OpenGL drivers, </br>
the only option is Windows 7x32 with those video cards </br>

dxcpl DirectX configuration wont do much, and similar for OpenGL only tests 1 card in XP. </br>
board 975x, Q6600 CPU </br>
information here may Not work in other systems. </br>
X58 boards, and different brands had strange changes in [ACPI](https://en.wikipedia.org/wiki/ACPI), many issues with [APIC](https://en.wikipedia.org/wiki/Advanced_Programmable_Interrupt_Controller#Issues), [MPS Tables](https://en.wikipedia.org/wiki/MultiProcessor_Specification) </br>

