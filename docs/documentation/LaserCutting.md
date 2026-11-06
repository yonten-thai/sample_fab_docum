# 🎨 Phase 1: File Preparation in Inkscape


### Import Artwork

1.Open Inkscape 

2.Go to File ➔ Import (or drag and drop your image directly onto the canvas) 

# 2. 🔀 Vectorize Image (Trace Bitmap)

1.Select your artwork 

2.Go to Path ➔ Trace Bitmap (or right-click the image ➔ Trace Bitmap)

3.Select Brightness Cutoff 

4.Adjust the threshold slider until the preview outline looks sharp and crisp with no extra clutter 

5.Click Apply to generate vector paths 


# 3.Clean Canvas
Pick the standard selection tool(the main arrow cursor at the top-left toolbar)

Drag the newly created vector copy off to the side 

Click on the old, blurry original picture and hit Delete 


4.Create Outer Boundary
Pick the Rectangle Tool  (or Ellipse/Arc Tool ) to draw a cut border around your design 

(Optional) Grab the Edit Paths by Nodes Tool (F2)  to pull the rectangle corners and make them smooth/curved 


5.Set Fill & Stroke (Engrave vs. Cut)
Open the Fill and Stroke panel (Ctrl + Shift + F) :

# 🖼️ For Engraving (Raster):

Set Fill ➔ Flat Color (Black/RGB) 

Set Stroke ➔ No Paint 

Standard line widths (in mm or pt) burn/etch onto the surface without cutting through. 

# ✂️ For Cutting (Vector):

Set Fill ➔ No Paint 

Set Stroke Paint ➔ Flat Color (Solid Black/RGB) 

Set Stroke Style/Width ➔ Hairline (or 0.001 in / 0.025 mm) 

The laser driver recognizes hairline strokes specifically as paths to cut completely through.


6.Send to Driver
Press Ctrl + P to send your finished design file to the Epilog print driver

# ⚙️ Phase 2: Epilog Print Driver Settings
1.Material Placement
Lay your physical material flat onto the laser bed 🛏️

2.Configure Engrave (Raster) Settings
Select Engrave / Raster mode in the driver menu 

Load the preset material settings for your substrate:

Wood: Deep Engraving

Acrylic: Deep Engraving

3.Configure Cut (Vector) Settings
Select Vector mode 

Adjust your cutting parameters based on material thickness 

(Example: Speed = 7.0%, Frequency = 15%) 

4.Send Job
Click Print in the driver to transfer the job to the laser engraver's local memory 

# 🛠️ Phase 3: Epilog Laser Machine Setup & Execution
1.Set Home Position (Origin)
Press Jog on the machine control panel 

Use the joystick to move the laser carriage directly above your desired starting point on the material 

Press Set Home (or Done) to lock in your origin 

2.Calibrate Focal Length
Press Auto Focus on the control panel to auto-adjust the bed height relative to the lens. 

Press Park Axis (or Done) to finalize focus setup. 

3.Execute Job
Double-check that your exhaust fan and air assist pump are turned ON!

Press the big green GO / Start button on the control panel to start laser processing 

# ⚠️ Essential Safety Rules
1.Never leave the machine unattended: Stay right next to the laser while it’s running.

2.Keep hands clear: Do not reach inside while the carriage is moving.

3.Keep the lid closed: Leave the top cover closed whenever the beam is firing.

4.Run ventilation: Always run active exhaust ventilation and air assist to clear combustion fumes.

5.Wait before opening: Let the carriage stop moving entirely before lifting the lid.

6.Check your materials: Never cut toxic materials (like PVC or vinyl) that release dangerous chemical fumes!