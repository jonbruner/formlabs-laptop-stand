# A supported laptop stand

This repo contains the files you'd need to fabricate this laptop stand, an angled surface supported by Formlabs lattices. If you just want to make one that's identical to mine, you only need the AI/EPS file for laser cutting and the FORM file for printing on your Form 2. If you want to modify the stand, you can do so by starting with the CAD file and generating your own 3D printing and laser files.

| | |
| :-: | :-: |
| :![Formlabs laptop stand](images/formlabs_laptop_stand_small.jpg): | :![Formlabs laptop stand side view](images/formlabs_laptop_stand_side_small.jpg): |

#### FORM file
* `legs.form` Open directly in [PreForm](https://formlabs.com/tools/preform/) and send straight to your Form 2. It's already got the supports you'll need to print in [Tough resin](https://formlabs.com/materials/engineering/#tough-overview).

#### Laser files
These were generated using [Slicer](https://apps.autodesk.com/FUSION/en/Detail/Index?id=8699194120463301363) and assume you're cutting 1/8"-thick, 24" x 36" plywood boards. I cut mine on an Epilog laser, which interprets 0.001" lines in Illustrator files as vector cuts. You may need to reconfigure line widths for your combination of software and laser.
* `laser-plans.ai` Illustrator file laid out for cutting from 1/8"-thick, 24" x 36" plywood
* `laser-plans.eps` EPS file for use in other vector-graphics software

#### CAD files
Open one of these in your favorite solid modeling software (I used Fusion 360). You can also get to the file directly through Fusion 360 here: https://a360.co/2pNZZCA
* `CAD-model.f3d` Fusion 360 archive file
* `CAD-model.step` For other solid modeling software
