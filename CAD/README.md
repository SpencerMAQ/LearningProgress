# LearningProgress in CAD, etc.


## Table of Contents
- [Rhino-based](#rhino-based)
  - [Mathematics](#mathematics)
  - [Grasshopper](#grasshopper)
  - [Rhino](#rhino)
  - [Python](#python)
  - [C#](#c)

- [Revit-based](#revit-based)
  - [Revit](#revit)
  - [Dynamo](#dynamo)
  - [Dynamo Python](#dynamo-python)
  - [Dynamo Packages](#dynamo-packages)
  - [Revit API](#revit-api)

- [VCS](#vcs)
  - [Github](#github)

Helpful Sites:  
http://buildz.blogspot.com/  
http://www.designalyze.com/software/revit  
http://www.theprovingground.org/  
https://www.modelab.is/  
https://vimeo.com/exlab/videos  
http://www.formfollowsperformance.com/  
https://github.com/modelab  
http://archi-lab.net/  
https://www.evolvebim.com/  
https://thinkparametric.com/  
https://flux.io/  
https://blackspectacles.com/ (paid?)  
https://parametricmonkey.com (10/10)  
http://parametrically.com/ (good)  
https://wowad.in/top-3-computational-bim-workflows-for-architects/ (Comp BIM Workflows, Interoperability)  
http://chris-malcolm.com/projects/malcstools/  
http://darenatwork.blogspot.com/  (API)  
https://boostyourbim.wordpress.com/  

http://www.co-de-it.com/wordpress/code/grasshopper-code
https://www.paragroup.org/code
http://www.pearltrees.com/u/11387487-grasshopper-code
https://codeofspace.com/tutorials/

Free books:
http://icd.uni-stuttgart.de/?page_id=17764

Important: Dynamo/Python  
https://github.com/architecture-building-systems/revitpythonshell (Revit Python Shell)  
https://github.com/dannysbentley/pyDynamo/blob/master/ModifyColor.py (Python sample code)  
https://github.com/gtalarico/revitpythonwrapper (Very Important!)  
https://github.com/gtalarico/python-revit-resources (VI!)  



## Rhino-based


### Mathematics
Ongoing | Completed | Total
:-- | :-- | :--
01 | 00 | 01


Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
:-- | :-- | :-- | :-- | :-- | :-- | :--
 ⏳ [Essential Mathematics for Computational Design, Third Ed.](http://www.rhino3d.com/download/rhino/5.0/EssentialMathematicsThirdEdition/) | Rajaa Issa / Mcneel | 01 | 79 | | 2018 | Red Cover, Review the Math behind NURBS, [second ed. mirror](http://www.grasshopper3d.com/profiles/blogs/essential-mathematics-second) // 01-24: Easy Vector Math // 28-35: Matrices as Transformations (already done with 3b1b's Linear Algebra)



### Grasshopper
Ongoing | Completed | Total
:-- | :-- | :--
04 | 14 | 57


Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
:-- | :-- | :-- | :-- | :-- | :-- | :--
 [Developing Your Own Grasshopper Plugin](http://designalyze.com/course/developing-your-own-grasshopper-plugin) | designalyze, Z. Downey | 00 | 03 | | |
 Utilizing Algorithms to Design a Parametric Skyscraper in Grasshopper | Digital Tutors | 00 | 25 | 4h5m | | Priority
 ✔ InfiniteSkills - Visual Programming in Rhino3D with Grasshopper Training | IS | 69 | 69 | 5h51m | 2016 |
 ✔ [Develop Parametric Architecture with Grasshopper](https://www.udemy.com/develop-parametric-architecture-with-grasshopper/) | UD | 36 | 36 | | 2016 | Twisting Tower, Galapagos
 ✔ [Exlab Video Tut Series](https://vimeo.com/album/2282897) | Gwyllim Jahn / EXLAB | 10.03 | 10.03 | 11 hrs | Start: 2016, Finished: 2018 | `8.9/10`,  [How'd this become an 'attack site'?](http://exlab.org/2011/09/grasshopper-resources/), http://www.grasshopper3d.com/page/tutorials-1, https://vimeo.com/exlab, Notes to self regarding the solution presented to the Traveling Salesman in this series: `>` The solution was assuming that the shortest path would be the points connected by the next closest point which might not be the case (the solution is probably naive) `>` See [this](https://media.wired.com/photos/59338957d80dd005b42b29d5/master/w_660,c_limit/tsp_map.jpg), the points were probably not the next closest but created the shortest path due to lack of overlap // skipped 06.04: unrolling driftwood (`Review though, USES PYTHON!`) // 06.05: understand why gradient descent is equal to pulling point down then doing `Surface Closest Point`.. // skipped 06.06: Fractals. // Kangaroo is DOPE // 07.04: Too Much Planarization = Messy Chaotic Weirdness... // 07.06: Voussoir Cloud (https://iwamotoscott.com/projects/voussoir-cloud) // 07.11: http://robertstuart-smith.com/filter/projects (Anemone) // 7.12: L-Systems, Hoopsnake // http://erase.net/projects/l-systems/ // Anemone is more complex than Hoopsnake accdg to this // anemone - useful for large amounts of iterations (e.g. gradient descent) // Hoopsnake - finite control, stepping into loop/ // Interesting but skipped: 07.13: OpenStreetMap / Elk Plugin / Open source, great API // Skipped: 07.14 - Firefly, Live Data Feed using webcams // 07.15: [millipede website](http://www.sawapan.eu/) // Skpped 09.01 (easy): just laying out a triangulated mesh of the voussoir cloud for CNC, diff is using list length and square root // 10.01: Soumaya Museum // Viewed half of it - 11.03: review as needed (PV using Archsim)
 ✔ [Intermediate Grasshopper](https://www.youtube.com/watch?v=kNYe_f4ux4w&list=PLGV167zE8gnV-mffyzD3mDhOrSM-CXaYW7) | MODELAB | 21 | 21 | 2h22m | 2016 |
 [Advanced Grasshopper](https://www.youtube.com/watch?v=kL8tAdl3q6M&list=PLGV167zE8gnVRrzCCWvdlHYh3XQWTXFDo) | MODELAB | 0 | 12 | 2h26m | | AKA Advanced Data Trees
 ✔ [Parametric Pleating](https://www.youtube.com/watch?v=IpRw97HruSo&list=PLGV167zE8gnUl7Zj1bLzsEbn2CWqBsYQH) | MODELAB | 15 | 15 | 2h20m | 2018 | [Other tuts](https://www.youtube.com/channel/UCFwIL20fwOmTUkxJgOPk5Jg/playlists), http://www.laurenceking.com/us/folding-techniques-for-designers-from-sheet-to-form/, Origami Simulation -> http://tsg.ne.jp/TT/software/index.html (i.e. visualizing 2D motifs to 3D), Ideas/Inspiration -> Keyword: Parametric Origami
 [Intro to Simulation](https://www.youtube.com/playlist?list=PLGV167zE8gnXSLj6cf5YI8a88SN-13UlP) | MODELAB | 00 | 13 | 2h24m  | | Kangaroo
 ✔ [Paneling Surfaces](https://www.youtube.com/playlist?list=PLGV167zE8gnU5X0R81fJedKl9zsKsOLeI) | MODELAB | 12 | 12 | 2h37m | 2018 | Lunchbox?
 ✔ [Subdivision Modeling](https://www.youtube.com/playlist?list=PLGV167zE8gnXCEzS3jUC7mrnumdf8qCu-) | MODELAB / Mode Collective(on fb) | 17 | 17 | 2h27m | 2018 | Mesh, Weaverbird, 16: 3D Printing, https://www.shapeways.com/
 ✔ Algorithmic Design | MODELAB | 14 | 14 | 2h28m | 2018 | 8.65/10 // Slightly confusing at first, Good // Algorithmic != Parametric // 3b1b is a god among men
 Computing Form | MODELAB | 00 | 13 | 2h25m | | Form-finding using Grasshopper
 ✔ Dynamic Patterning | MODELAB | 12 | 12 | 2h35m | 2018 | Very Interesting, Vector Fields
 Organic Modeling | MODELAB | 00 | 08 | 1h55m | | T-Splines, With Rhino Tutorials?
 |  |  |  |  | |  |
 |  |  |  |  | |  |
 [GRASSHOPPER ESSENTIALS](http://www.rese-arch.org/bundle/essentials) | rese-arch | 00 | 05 | 13:04 | | Excellent
 [GRASSHOPPER ARCHITECTURAL](http://www.rese-arch.org/bundle/architectural) | rese-arch | 00 | 04 | 8:25 | |
 [GRASSHOPPER ADVANCED](http://www.rese-arch.org/bundle/advanced) | rese-arch | 00 | 03 | 11:12 | | Mesh, Paneling, Kangaroo
 [GRASSHOPPER ITERATIVE](http://www.rese-arch.org/bundle/iterative) | rese-arch | 00 | 10 | 12:06 | | Loops and Motion, Recursion and Trees, Growth, L Systems and Sierpinski Triangle, Flocking
 [Extending Grasshopper](https://www.youtube.com/playlist?list=PLXekJiZsSipBKDtaSB6iHfCaUotzY3jFq) | Daniel Christev | 00 | 07 | 3 hrs| | Kangaroo, VERY HIGH QUALITY
 [Advanced Grasshopper](https://www.youtube.com/playlist?list=PLXekJiZsSipBKDtaSB6iHfCaUotzY3jFq) | Daniel Christev | 00 | 07 | 7h 5m| | VERY HIGH QUALITY
 |  |  |  |  | |  |
 |  |  |  |  | |  |
 Anemone 101 - Using Loops in Grasshopper | ThinkParametric | 0 | 9 | | |
 Grasshopper 102 - Data Lists and Tree Structures | ThinkParametric | 0 | 8 | | |
 Creating Models for Development Analysis with Grasshopper | ThinkParametric | 0 | 5 | | | Based on site plan, Zoning
 View Optimization Using Galapagos For Grasshopper | ThinkParametric | 00 | 10 | 2h10m | | High PRIORITY
 Creating a Smart Sketch Tool with Grasshopper | ThinkParametric | 00 | 6 | | | Geom Pipeline
 Kangaroo 101: Physics Engine & Form-Finding | ThinkParametric | 00 | 6 | 1hr 49 | | Kangaroo 2, Good
 Deconstructing the Serpentine Pavilion | ThinkParametric | 00 | 12 | 2hr58m | | HIGH PRIORITY
 Grasshopper Essential Training | Lynda | 00 | 49 | | | PRIRITY, with LB/HB Tutorials
 [Grasshopper: Architectural Prototyping](https://www.lynda.com/tutorial/667360) | Lynda | 00 | 30 | | |
 [Computation Practice Spring 2015](https://www.youtube.com/watch?v=JxKBGVIig7U&list=PLsDYCyUR8mCSJBMl5trSBkt1L4HDgDe7k) | Jeremy Roh | 00 | 48 | | | Comprehensive, GH+Dynamo+Revit, Priority
 ✔ [Parametric Design of Aqua Tower, Chicago, IT. from Junfei Chen](http://chenjunfei0707.blogspot.com/2014/11/project-1-parametric-design-of-aqua.html) | Junfei Chen 陈骏飞 | 02 | 02 | | 2017 | [Part 2](http://chenjunfei0707.blogspot.com/2014/12/project-2-improvement-of-project-1.html), [video](https://www.youtube.com/watch?v=fPWn1JzZY8g), Surprisingly extremely easy, Not only is the Aqua Tower a giant radiator fin, it's also too basic by GH standards
 ⏳ [SFDUG Jan 2018 - Machine Learning and Computational Design Adoption](https://www.youtube.com/watch?v=tTUGVeeNs9U&t=1612s) | San Francisco Dynamo User Group | 00:00 | 01:12 | |
 ⏳ [GrasshopperChallenges](https://github.com/dantaeyoung/GrasshopperChallenges) | dantaeyoung | 00 | ?? | |
 [The Geometry of Bending Blospot](http://thegeometryofbending.blogspot.com.au/) | Mårten Nettelbladt | 00 | ?? | | Kangaroo, Physics, Math, Curvature, [vimeo](https://vimeo.com/m3rten)
 |  |  |  |  | |  |
 | [Space Planning](http://www.grasshopper3d.com/group/space-syntax) |  |  |  |  |  |
 |  |  |  |  | |  |
 ✔ [Designing with Space Syntax](https://www.researchgate.net/publication/283311205_Designing_with_Space_Syntax_A_configurative_approach_to_architectural_layout_proposing_a_computa-_tional_methodology) | Pirouz Nourian | 11 | 11 | | 2018 | Brilliant, [check these out](https://www.youtube.com/watch?v=z5Xox9BYxos&list=PLEO2booj-uVW5NYmQcBwXdU-TlkPaV213&index=5), http://www.franobazalo.com/, http://www.franobazalo.com/grasshopper.html, How to use Graph reader to output a sketchpad with Nominal N-S-E-W (check journal pg.5), How to triangulate and Quadrangulate?
 [A SYNTACTIC ARCHITECTURAL DESIGN METHODOLOGY](https://www.researchgate.net/publication/283311082_A_SYNTACTIC_ARCHITECTURAL_DESIGN_METHODOLOGY_Integrating_real-time_Space_Syntax_analysis_in_a_configurative_architectural_design_process) | Pirouz Nourian | 00 | 16 | | | SS
 [Introduction to PanelingTools for Rhinoceros 5](https://vimeo.com/112434511) | Rhino Tutorials | 00:00 | 01:47 | | |
 |  |  |  |  | |  |
 | Other Plugins |  |  |  |  |  |
 |  |  |  |  | |  |
✔ [Mantis Shrimp](https://www.youtube.com/watch?v=G7XGOX34yHk) | Konrad Sobon | 03 | 03 | | 2018 | Vastly Underrated plugin // Installation, GH to Dynamo, Dynamo to GH, [github](https://github.com/ksobon/MantisShrimp), [tutorial series from archi-lab](http://archi-lab.net/mantis-shrimp-tutorial-series/), Data Tree vs Nested Lists // Export Data removed?, probably superseded by bumblebee? (excel)
 [Crystallon](http://www.food4rhino.com/app/crystallon) | fequalsf | 00 | ?? | | | [repo](https://github.com/fequalsf/Crystallon)
 [Axolotl](http://www.food4rhino.com/app/axolotl) | worbit | 00 | ?? | | | [repo](https://github.com/dbt-ethz/Axolotl)
 [GH_CPython](https://github.com/MahmoudAbdelRahman/GH_CPython) | MahmoudAbdelRahman | 00 | ?? | | |
 [GhPlotLib](https://github.com/MahmoudAbdelRahman/GhPlotLib) | MahmoudAbdelRahman | 00 | ?? | | |
 [ANT](https://github.com/MahmoudAbdelRahman/ANT) | MahmoudAbdelRahman | 00 | ?? | | |
 [FlexHopper Workshop](https://www.youtube.com/playlist?list=PLw7gQzl_I29Z8oHCrPGXgNdwnULjqzUcz) | Benjamin Felbrich | 00 | 07 | | | [github repo](https://github.com/HeinzBenjamin/FlexCLI), physics, looks more logical than kangaroo but idk
 |  |  |  |  | |  |
 | Books |  |  |  |  |  |
 |  |  |  |  | |  |
 Algorithmic Sketchbook  | Mitchell Su / Studio Air / Exlab | 00 | 38 | | |
 Algorithmic Sketchbook | Matthew Tibballs / Studio Air / Exlab | 00 | 31 | | |
 Final Journal | Tania Putri Kanadi / Studio Air / Exlab | 000 | 130 | | | From the author: `I have done other design studios in previous semesters, and in all of them, my designs were mostly developed through the more traditional hand-drawn methods. I have limited experience with CAD programs, however, I know its significance in the architecture industry is growing and as such, to learn it is necessary.` // University of Melbourne
 Generative Algorithms using Grasshopper | Zubin Khabazi | 000 | 141 | | |
 Grasshopper Workshop | Woo Jae Sung | 00 | 13 | | |
 ⏳ Millepede 2014 Release | [Panagiotis Michalatos](https://www.grasshopper3d.com/group/millipede) | 01 | 86 | | 2018 |
 |  |  |  |  | |  |
 | [All GH Components](https://rhino.github.io/) |  |  |  |  |  |
 |  |  |  |  | |  |
 ✔ Params | McNeel | util.gene_pool | util.gene_pool | | 2018 | study in top to bottom, left to right order, Interesting: Cherry Picker, Jump // Review: [Fitness Landscape](http://www.grasshopper3d.com/photo/fitness-landscape) (probably for viewing the selection process as a graph), [vid](http://www.grasshopper3d.com/video/fitness-landscape-topology), How to use Color Wheel
 ✔ Maths | McNeel | util.create_complex | util.create_complex | | 2018 | Can't Think of a need for `Consecutive Domains` // Find Domain: Find Domain that contains a specific value from a list of domains // [logic gates](https://en.wikipedia.org/wiki/Logic_gate) // Circumcentre: creates a point @ the center of the perpendicular bisectors of a triangle // Incentre: from angle bisectors // Unk: SMOOTH NUMBERS (what the hell does this do)
 ⏳ Sets | McNeel | Tree.Split_Tree | Tree.Replace Paths | | 2018 | Skipped: Pick n Choose // Combine Data // MATCH TREE // SPLIT TREE    ___ Can't think of usages yet for: Find Similar Member, Delete Consecutive, Key/Value Search
 ⏳ Vector | McNeel | Plane.Adjust_Plane | Vector.Vector Length | | 2018 |
 Curve | McNeel | Analysis.Control Points | Util.Smooth Polyline | | |
 Surface | McNeel | Analysis.Box Corners | Util.Offset Loose | | |
 Mesh | McNeel | Analysis.Deconstruct Face | Util.Occlusion | | |
 Intersect | McNeel | Mathematical.Brep-Line | Shape.Region Slits | | |
 Transform | McNeel | Affine.Scale | Util.Split Group | | |
 Display | McNeel | Colour.ColourCMYK | Vector.Display Ex | | |


### Rhino
Ongoing | Completed | Total
:-- | :-- | :--
01 | 00 | 03


Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
:-- | :-- | :-- | :-- | :-- | :-- | :--
 ⏳ Lynda - Rhino 5 Essential Training | Dave Schultze | 13.04 | 15.00 | | 2018 | 11.01: Curve from object Toolbar: GetIsoLine // 12.03: Offset Surface, Curve from cross section profiles // Drafting Tab for dimensioning
 Creating Conceptual Architectural Diagrams | ThinkParametric | 00 | 10 | | | V-ray, Photoshop, Massing Diagrams, Very Good
 Recreate the Villa Savoye using Rhino 3D | ThinkParametric | 00 | 21 | 3h28m | |
 Learn how to design an organic shaped building envelope (Heydar Aliyev centre) | ThinkParametric | 00 | 20 | 3h23m | |


### Python
Ongoing | Completed | Total
:-- | :-- | :--
02 | 02 | 12


Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
:-- | :-- | :-- | :-- | :-- | :-- | :--
 ⏳ ["Nature Of Code" Tutorials for Python in Grasshopper](https://www.youtube.com/watch?v=Kyi_K85Gsm4&list=PL5Up_u-XkWgP7nB7XIevMTyBCZ7pvLBGP) | Jake Hebbert | 07 | 24 | | 2016 | Apparently based on NOC
 [Nature of Code: Forces (chapter 2) Python](https://www.youtube.com/watch?v=TrKXbfTwIvE&list=PL5Up_u-XkWgPgebtPEAfck3UEPZPHBB1D) | Jake Hebbert | 00 | 13 | | |
 [Nature of Code: Oscillation(chapter 3) translation to Python](https://www.youtube.com/watch?v=QIdK4yv8nsY&list=PL5Up_u-XkWgMsZpYk8GW9TpGk0GvC6DzR) | Jake Hebbert | 00 | 25 | | |
 [Nature of Code: Particle Systems (chapter 4).](https://www.youtube.com/watch?v=nWkyLMm_Fdw&list=PL5Up_u-XkWgNk6l5V1bS26hpbhsUSohF2) | Jake Hebbert | 00 | 12 | | |
 [Nature of Code: Autonomous Agents (chapter 6) translated](https://www.youtube.com/watch?v=mk4lc9Zy5jc&list=PL5Up_u-XkWgPw4wRmEgtfKLPZ2TTW3341) | Jake Hebbert | 00 | 18 | | |
 ✔ [RHINO PYTHON](https://www.youtube.com/watch?v=wdY1T0XLzkE&list=PL594EB4471E93F2DA) | Jose Sanchez | 17 | 17 | | 2016 | [Mirror Link](https://www.plethora-project.com/education/2017/5/31/rhino-python-programming)
 ✔ [PYTHON in Grasshopper for Rhino3D](https://www.youtube.com/watch?v=3Z4YVCOk02k&list=PLj1JeZhReAqeTnh6b0uL58C2aQlykPzce) | Jose Sanchez | 02 | 02 | | 2016 | Review Recursive Aggr.
 [Intro to Scripting with Python for Rhino](http://designalyze.com/course/intro-scripting-python-rhino) | designalyze, Z. Downey | 00 | 24 | | | Vimeo
 [Automate Grasshopper with Python](http://designalyze.com/course/automate-grasshopper-python) | designalyze, Z. Downey | 00 | 05 | | |
 ✔ [Intro to Python Scripting](https://www.youtube.com/watch?v=J84DC-cMS6A&list=PLGV167zE8gnVhurBT46afZ1RlK9RzAsLx) | MODELAB | 14 | 14 | | 2016 | Easy for the most part
 Creating a Waffle Structure with Grasshopper and Rhinoscript | ThinkParametric | 00 | 09 | 1hr19m | | `rhinoscripsyntax`
 [Developing Python Components](https://www.youtube.com/watch?v=rgo-5jbDPuE&list=PLGV167zE8gnXrDhOGv6XGc1H6-hWMnvjc) | Lynda | 03 | 15 | | | Incl. Data Trees
 [Grasshopper and Rhino: Python Scripting](https://www.lynda.com/course-tutorials/Grasshopper-Rhino-Python-Scripting/728385-2.html) | Lynda | 0.00 | 05.00 | 5h12m | |
 |  |  |  |  | |  |
 | [GH Developer Docs](http://developer.rhino3d.com/) |  |  |  |  |  |
 |  |  |  |  | |  |
 [API References](http://developer.rhino3d.com/api/) | McNeel | ?? | ?? | | |
 [RhinoCommon](http://developer.rhino3d.com/guides/rhinocommon/) | McNeel | ?? | ?? | | |


### C#
Ongoing | Completed | Total
:-- | :-- | :--
00 | 00 | 08


Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
:-- | :-- | :-- | :-- | :-- | :-- | :--
 [C#_1_Intro to C# Scripting in Grasshopper](http://designalyze.com/course/intro-c-scripting-grasshopper) | designalyze, Z. Downey | 0 | 10 | |  |
 [C#_2_Intermediate C# Scripting in Grasshopper](http://designalyze.com/course/intermediate-c-scripting-grasshopper) | designalyze, Z. Downey | 0 | 1 | |  |
 [C#_3_Advanced C# Scripting in Grasshopper](http://designalyze.com/course/advanced-c-scripting-grasshopper) | designalyze, Z. Downey | 0 | 2 | |  |
 [C# Scripting and Plugin Development for Rhinoceros and Grasshopper - Long Nguyen - Day 1 Part 1](https://vimeo.com/247048808) | [Rhino Tutorials](https://vimeo.com/rhino) / ICD / [Long Nguyen](https://www.linkedin.com/in/longnguyenp/) | 00 | 03:03 | | | [full developer playlist](https://vimeo.com/album/1932355)
 [C# Scripting and Plugin Development for Rhinoceros and Grasshopper - Long Nguyen - Day 1 Part 2](https://vimeo.com/247050074) | [Rhino Tutorials](https://vimeo.com/rhino) / ICD / [Long Nguyen](https://www.linkedin.com/in/longnguyenp/) | 00 | 02:09 | | |
 [C# Scripting and Plugin Development for Rhinoceros and Grasshopper - Long Nguyen - Day 2 Part 1](https://vimeo.com/247050938) | [Rhino Tutorials](https://vimeo.com/rhino) / ICD / [Long Nguyen](https://www.linkedin.com/in/longnguyenp/) | 00 | 02:39 | | |
 [C# Scripting and Plugin Development for Rhinoceros and Grasshopper - Long Nguyen - Day 2 Part 2](https://vimeo.com/247051786) | [Rhino Tutorials](https://vimeo.com/rhino) / ICD / [Long Nguyen](https://www.linkedin.com/in/longnguyenp/) | 00 | 02:59 | | |
 [C# Scripting and Plugin Development for Rhinoceros and Grasshopper - Long Nguyen - Day 3](https://vimeo.com/247052840) | [Rhino Tutorials](https://vimeo.com/rhino) / ICD / [Long Nguyen](https://www.linkedin.com/in/longnguyenp/) | 00 | 02:26 | | | UBER COMPREHENSIVE, University of Stuttgart ICT, ITECH Master Program
 |  |  |  |  | |  |
 [C# Scripting and Plugin Development for Grasshopper: Day1 Morning Session ](https://www.youtube.com/watch?v=p7BIC75q0RY) | ICD / [Long Nguyen](https://www.linkedin.com/in/longnguyenp/) | 00 | 03:50 | | | 2018 Series, University of Stuttgart ICT, ITECH Master Program, [ICD link](http://icd.uni-stuttgart.de/?p=22773)
 [C# Scripting and Plugin Development for Grasshopper: Day1 Afternoon Session 1](https://www.youtube.com/watch?v=GOYdLih8SlU) | ICD / [Long Nguyen](https://www.linkedin.com/in/longnguyenp/) | 00 | 02:12 | | |
 [C# Scripting and Plugin Development for Grasshopper: Day1 Afternoon Session 2](https://www.youtube.com/watch?v=7-w_O9aJzxE) | ICD / [Long Nguyen](https://www.linkedin.com/in/longnguyenp/) | 00 | 01:27 | | |
 [C# Scripting and Plugin Development for Grasshopper: Day2 Morning Session](https://www.youtube.com/watch?v=7-w_O9aJzxE) | ICD / [Long Nguyen](https://www.linkedin.com/in/longnguyenp/) | 00 | 03:27 | | |

 ----


 ## Revit-based
 Ongoing | Completed | Total
 :-- | :-- | :--
 05 | 13 | 44


 ### Revit
Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
:-- | :-- | :-- | :-- | :-- | :-- | :--
 ✔ Revit 2017 Essential Training for Architecture (Metric) | Lynda | 103 | 103 | | 2017 | Very Good
 ⏳ Revit 2017 Essential Training for MEP (Metric) | Lynda | 51 | 59 | | 2017 |
 Revit Worksharing Collaboration for Revit (C4R) | Lynda | 00 | 22 | | | Priority
 Advanced Modelling in Revit | Lynda | 00 | 09 | | | 9 Chapters
 ⏳ Architectural Families in Revit | Lynda | 00 | 36 | | | Priority
 ⏳ Revit Architecture The Family Editor | Lynda | 00 | 63 | | | Priority
 ⏳ Lynda - Revit Families Workshop | Lynda | 00 | 04 | | | chapters
 Revit Structure 2016 Essential | Lynda | 00 | 12 | | | 12 Chap
 Creating Revit Templates, Views and Sheets  | Lynda | 00 | 04 | | | 4 Chap
 Sprinkler Design with Revit  | Lynda | 00 | 04 | | | Priority, 6 Chaps
 Revit for Interior Design Space Planning  | Lynda/Ed Cotey | 00 | 36 | | | 7 Chaps, G3
 ⏳ [Learning Autodesk Revit Architecture 2015](https://www.safaribooksonline.com/library/view/learning-autodesk-revit/9781771372268/) | O'Reilly | 21 | 21 | | 2016 | Need to REVIEW!
 ✔ Massing With Revit | InfiniteSkills/Ed Cotey | 06.01 | 06.01 | | 2017 | 31 Videos, Conceptual Mass // Masses off by default, will not print or export unless on in VG, Mass types - Mass Family (built-in, place mass, primitive), In-place, Conceptual family mass (from family editor, drawn in fam editor then loaded into project), You can do sched fields that are results of calculations // Order of felxibility: library forms, in-place mass, from fam editor // Mass Revolve - profile and axis (axis drawn on ref plane), Sweep (can be two profiles on each end, use point to create perp frame) // blend = composed of 2 or more 2d profiles connected by a common path // surfaces(extruded lines), loft (2 or more profiles) // 3D control (Edit in place) // X-ray mode (select edge > Modify > Form Element > X-ray) // Edit Profile (Edit in place > Select edge > Edit Profile > Pick edge, workplane viewer) // Adding edges/profiles (click edge > Form Element), then use x-ray for more control // Divide Surface + apply pattern-based curtain panels, adjust UV rotation // Modify > Geom split surface to apply diff materials to same wall // Wall or Roof by face, System // Update to Face // Add edge to new wall // Properties > Identity > Usage // 0503: You can duplicate Default Mass floor, apply color to floors using paint // 0504 (Schedule for analysis): Use Properties > 'Mark' to indicate the level of a floor for use in schedules, you could also use Conditional formatting to identify numbers that don't pass a certain criteria you make
 [Advanced Revit Architecture 2015](https://www.safaribooksonline.com/library/view/advanced-revit-architecture/9781771372275/) | InfiniteSkills | 0 | 26 | | | 26 Chapters
 ✔ [Learning Revit Structure 2015](https://www.safaribooksonline.com/library/view/learning-revit-structure/9781771372657/) | O'Reilly/InfiniteSkills | 18.01 | 18.01 | | 2018 | Very Comprehensive (prioritize over Lynda - Revit Structure), same as [this](http://shop.oreilly.com/product/0636920041443.do) // advanced to: 0906 to 1013, 1101- 1204 // skipped 1012 // Insert > Insert from File > Insert Views from FIle (importing drafting views from another revit file)// WORKSAHING!!!!
 Revit - Stairs And Railings | InfiniteSkills | 0.0 | 12.4 | | | Very Comprehensive, Priority
 Revit Architecture - Roof Design Training Video | InfiniteSkills | 0 | 7.4 | | | Priority
 Learning Autodesk Revit Architecture 2016 | O'Reilly | 0 | 143 | | | Very Comprehensive
 ✔ Revit Landscape An Introduction to Revit and Site Modeling | Udemy | 5.4 | 5.4 | | 2017 | 5 Chaps, 7/10, A lot of unexplained things I don't understand
 Creating a Custom Staircase in Revit | Digital Tutors | 0 | 08 | | |
 Creating Intelligent Families in Revit | Digital Tutors | 0 | 13 | | |
 Modeling Roof Formations Structures and Materials in Revit | Digital Tutors | 0 | 11 | | |
 ✔ Modeling Trusses in Revit | Digital Tutors | 6 | 6 | | 2017 | Good
 ✔ Creating a Wood Frame Model in Revit | Digital Tutors | 11 | 11 | | 2017 | Timber Structural Framing, Summary: Sill - Beam, Studs - Columns, use actual size not nominal, C. Joist = offset due to rafters, 50% of the time = copying. Coping not covered, Truss not covered. Timber extension Tool
 ✔ Working with Design Options in Revit | Digital Tutors | 05 | 05 | 1 day | 2017 | easy \\ to create two 3D views with diff design options: VV > Design Options > Design Option from Automatic to the design option you want
 Modeling Plumbing Systems in Revit MEP | Digital Tutors | 0 | 06 | | | Priority
 ✔ Work Planes and Reference Planes in Revit | Digital Tutors | 05 | 05 | | 2017 | Should be taught in basic courses
 ✔ Creating Detail Drawings in Revit | Digital Tutors | 08 | 08 | 2+ hrs | 2017 | 6.5/10, Use Object Styles, View>Cut Profile, Ref Planes
 ✔ Modeling a Steel Structure in Revit | Digital Tutors | 10 | 10 | 2+ hrs | 2018 | for KA Quad, I hate imperial units
 ✔ Storefront, Curtain Walls, and Curtain Systems in Revi | Pluralsight  | 21 | 21 | 1 day | 2017 | Good, Corner Mullions, Pattern-based C. Walls, Select on Gridline, Custom C. wall panels, uncommon uses - rail, cabinet
 Revit Essentials Design Development Techniques for Interiors | Pluralsight  | 00 | 53 | | | Priority, High Quality
 [BIM Methods Spring 2012](https://www.youtube.com/watch?v=HBbrRjKknlw&list=PLsDYCyUR8mCQzckm6KsqGpvN9UoI3v2_Q) | Jeremy Roh  | 00 | 26 | | | [Full Archive](http://jrohdesign.com/revit//authorized_users/archives/), Low pririty // This semester covered the making of parametric bridges with complex forms and adaptive components; as well as, the methods of developing skyscrapers for New York City.
 [Solar Decathlon Workshops Summer 2012](https://www.youtube.com/watch?v=uwSDETu_uTc&index=11&list=PLsDYCyUR8mCRjZuJRG_kSMY_VjtGuMNth) | Jeremy Roh  | 00 | 11 | | | Designed to cover an overview of modeling in all parts of the Revit Project, Family, and Conceptual Design environments; as well as, teach documentation per the Solar Decathlon and Professional Office Standards.
 [BIM Methods Fall 2012](https://www.youtube.com/watch?v=JxH1EqbSh_s&list=PLsDYCyUR8mCRZE9rnFP9z2j8oAuDgsN3I) | Jeremy Roh  | 00 | 26 | | | This semester class taught the making, detailing, and rendering of transit and tower components; as well as, this class covered the advanced modeling skills associated with parametric towers, adaptive components, curtain panel pattern-based families, double-curtain wall systems, and using tools beyond their original intent.
 [Toyo Ito: Sendai Mediatheque in Revit](https://www.youtube.com/watch?v=D6ME-s0g8MU&list=PLsDYCyUR8mCSKYmtYGGJ8_ss5AKLUBdHK) | Jeremy Roh  | 00 | 07 | | | HIGH PRIORITY // The various parts of this tutorial portrays a method for developing the vertical structural tube elements within Toyo Ito's Sendai Mediatheque project and also covers methods for creating the double curtain wall system for the South Facade.
 [BIM Methods Spring 2013](http://jrohdesign.com/revit//authorized_users/classes_2013s/) | Jeremy Roh  | 00 | 30 | | | Priority, Each vid with A and B parts, [mirror](https://www.youtube.com/watch?v=oHU-8BRfAZQ&list=PLsDYCyUR8mCQ0WQqzdQNbHTVKt4TSU9ht) // This semester class taught the making, detailing, and rendering of housing components; as well as, this class covered the advanced modeling skills associated with parametric pathways, adaptive components, curtain panel pattern-based families, and parametric profiles.
 [BIM Methods Fall 2013](https://www.youtube.com/watch?v=4jrZve-b-7Y&list=PLsDYCyUR8mCRBhR63W0rjtHBlQyG2FUAF) | Jeremy Roh  | 00 | 28 | | | This semester class taught the making and detailing of family components and essential project environment modeling while reading and understanding Condo Construction Documents; as well as, this class covered advanced curtain wall and adaptive component modeling.
 [BIM Methods Spring 2014](https://www.youtube.com/watch?v=CumZcEOHly0&list=PLADA26644D29AA0CB) | Jeremy Roh  | 00 | 27 | | | This semester class taught a crash course in the essentials of the Revit Project Environment and then went into depth on detailed methods of how to model complex forms and tectonic structures through various case studies using the Revit Conceptual Design Environment and Dynamo (a graphical algorithm editor for Revit).
 [BIM Methods Fall 2014](https://www.youtube.com/watch?v=SPr9riX-hOw&list=PLsDYCyUR8mCQSmiO6NomVFQvGc05UImZL) | Jeremy Roh  | 00 | 27 | | | The first half of this semester went into depth on how to model complex forms, tectonic structures, and kinetic panels using the Revit Conceptual Design Environment and Dynamo (a scripting interface for Revit similar to Rhinoceros 3D's Grasshopper). The second half of the semester went through techniques in modeling within the Revit Project Environment for Programming, Schematic Design, and Development of Model Details for a Condo Project. Additional bonus tutorials and workshops are also included in this semester geared towards the [5th Year Studio](https://www.youtube.com/playlist?list=PLsDYCyUR8mCRgSRGDi85KaeEsNA-FvIs6) Projects.
 ✔ [Building Parametric Masses in Autodesk Revit Architecture](https://www.youtube.com/watch?v=qFmJfEdQ1rs&t=402s) | Autodesk Building Solutions | 01 | 01 | 12min | 2017 | Parametric Masses (Prelude to Advanced Computational BIM)
 ✔ [Repeat and Divide (Curtain System, Adaptive Components)](https://www.youtube.com/playlist?list=PLGdDXXEHnr4V3bEEJaI7m5EbR6Of7HodQ) | zach kron | 04 | 04 | 1 day | 2017 | High Quality 10/10, Note to Adaptive Components, When creating offsets then ref lines along the offset Ref Points, also draw them in order!, I can't believe I'm saying this but Revit is way more flexible that SKP despite its reputation as difficult to learn // Double attractor in Revit - two distance parameters, 3 adaptive pts, radius by formula
 [Parametric Patterns (Adaptive Components)](https://www.youtube.com/playlist?list=PLGdDXXEHnr4WfBVzeBkfrcmnrCgRUOsB4) | zach kron | 00 | 21 | | | Adaptive
 [buildz.info (Adaptive Components)](https://www.youtube.com/playlist?list=PLGdDXXEHnr4VtDTx-C3BLeeogqX2B1a1Z) | zach kron | 00 | 29 | | | Adaptive, also check out his Dynamo Tutorials, [website](http://buildz.blogspot.com/)


 ### Dynamo
 Ongoing | Completed | Total
 :-- | :-- | :--
 01 | 11 | 33


Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
:-- | :-- | :-- | :-- | :-- | :-- | :--
 An Introduction to Dynamo for Daily Use Within Revit | Pluralsight | 0 | 25 | | |
 ✔ Visual Programming Introduction with Dynamo and Revit | Pluralsight | 04.02 | 04.02 | | 2017 | Kevin Griendling, Boom-Mast example, Good, Basic
 ✔ [Dynamo for Grasshopper users](https://parametricmonkey.files.wordpress.com/2016/01/dynamo-for-grasshopper-users.pdf) | Paul Wintour (Param Monkey) | 15 | 15 | | 2017 | PDF
 Dynamo 101 - Fundamentals | ThinkParametric | 0 | 16 | | | Basic
 Create Custom View Filters using Dynamo | ThinkParametric | 0 | 7 | | | Very Revit-Specific, Priority
 Dynamo Essential Training | Lynda | 00 | 29 | | | Easy
 Dynamo for Revit Project Setup | Lynda | 00 | 23 | | | Uses List@Level
 ✔ Paneling With Dynamo for Revit | Lynda | 27 | 27 | 2h51m | 2018 | Good, 8.6/10 // Clockwork, LunchBox, Ampersand, Quads from Rectangular Grid, Spring Nodes // Ch1: 01-08 // 13: Very Good Excercise -- Key Lessons: need to explode solids to get surfaces for `ClosestPointTo` node -- be wary of `shifting` multi-level lists, be sure you operate on the list of the items // Options for importing geom to Revit -- ImportInstance on the project file, ImportInstance inside a FAMILY doc (both are not recommended) // Form.ByGeometry (from `Springs` pacakge) -- Imports as Generic Models, good method, materials can be applied // DirectShape.ByGeometry - may convert extruded geom into meshes (not so good) // Best - Adaptive Components // Vid No. 20 - can be used for List.GroupByKey -- Interesting // 24: Regular Patterns // 25: Random patterns // 26: Mapping Images
 ✔ Dynamo for Revit Workflow | Lynda | 23 | 23 | | 2017 | Easy // Review Key Schedules from Revit Essentials (Lynda) // Idea: with x-product lacing, calculating the distance between power outlets and chairs, List.MinimumItem, then using Element.OverrideColorInView to highlight elements which are too far/close
 ✔ [01 Computational Design for BIM with Dynamo](https://www.youtube.com/watch?v=tjSVxWw19ew&list=PLAQfn-QKbiAlBV8_ciUa4USacSITkLCt9) | Autodesk Education | 10 | 10 | | 2017 |  [Dataset](http://www.dynamobim.org/wp-content/links/Introductory_Datasets_092.zip), I would bet that majority of people would find this confusing unless they know GH, [Mirror](https://academy.autodesk.com/curriculum/bim-computational-design)
 [02 AEC Education Channel: Dynamo: Computation Design for BIM](https://www.youtube.com/watch?v=QIwTtHBD-FU&list=PLAQfn-QKbiAkYnQoxuk7AdT8ZQjmNyGXr&index=1) | Autodesk Education | 0 | 10 | | | Priority(Old), Basically same as 01 except for maybe 2 videos
 ✔ [03 Advanced Computational Design for BIM](https://www.youtube.com/watch?v=g4-TZngbtL8&list=PLAQfn-QKbiAnAHH2_WCO402q-PmQzaTnT) | Autodesk Education | 30 | 30 | 2 days| 2017 | Basic,  [Dataset](http://dynamobim.org/wp-content/links/AdvancedCurricullum.zip), [Mirror](https://academy.autodesk.com/curriculum/bim-advanced-computational-design) // SetParameter.ByName to flex parametric masses, create lists for many parameters // dscript cond.: if(cond, return_true, return_false) i.e. same as GH // StructuralFraming.BeamByCurve, StructuralType.Beam // Intersect with plane for creating adaptive components // Waffle = Bounding Box, Surface.GetIsoLine, Curve.PlaneAtParameter, Intersect with srf // USE FUNCTIONS inside DesignScript!!!
 ✔ [04 Dynamo](https://www.youtube.com/watch?v=QETG7HaaaaI&list=PLY-ggSrSwbZo0vCNJOFhzEQW_nbEfBKo8) | Autodesk Building Solutions | 29 | 29 | | 2017 | Priority (Watch after Advanced Revit), Last 10 vids = same as 01, Order: Dynamo Tutorials, Vignette, Medical Center // Dynamo Tutorials - bad 'tutorials' // They basically repeated the same tutorials over and over // Vignette = exactly the same as 01, 3/10
 ✔ [Accelerated Dynamo for Grasshopper Users](https://parametricmonkey.com/2016/01/19/dynamo-for-grasshopper-users/) | Andrew Heumann | 59 | 59 mins | | 2017 | [Vimeo](https://vimeo.com/116702007), Dynamo Data Structures are more intuitive to me than GH Data Trees, good job Autodesk, and List.Map() is an excellent feature similar to Python's map. Mind Blown @55:51 (List.Map)
 ✔ [Introducing List@Level: Working with Lists Made Easier](http://dynamobim.org/introducing-listlevel-working-with-lists-made-easier/) | Racel Williams | 01 pg | 01 pg | | 2017 | Point.ByCoordinates(t1@@-2, t2, t3)
 ✔ [Lacing in Code blocks](http://dynamobim.org/forums/topic/code-blocks-and-lacing/) | Forum Post | 00 pg | 01 pg | | 2018 | `<1> <2>` (Default Cross Product Lacing) -> Pairs First Value with all the other values in the second list
 [Github Dynamo wiki](https://github.com/DynamoDS/Dynamo/wiki) | | 00 pg | 61 pg | | |
 ✔ [Dynamo Language Guide v1](http://dynamobim.org/wp-content/uploads/forum-assets/colin-mccroneautodesk-com/07/10/Dynamo_language_guide_version_1.pdf) | | 57 pg | 57 pg | | 2017 | [Full list of resources](http://dynamoprimer.com/en/Appendix/A-1_resources.html), Good, No explanation for Imperative blocks, Replication guides // rank = num dimensions of the matrix
 [DesignScript Documentation (Draft)](http://dynamobim.org/help-center/) | | 00 pg | 37 pg | | | Very C#-like, read explanation of Imperative, Associative
 [DesignScript Guide](http://dynamobim.org/help-center/) | | 00 pg | 82 pg | | | PRIORITY!!
 ✔ [Dynamo Primer](http://dynamoprimer.com/en/) | Matt Jezyk | 13.04 | 13.04 | 5 days | 2017 | High Quality // Best Explanation of List.Combine, Basically, Last.Map is the same as python's Map, List.Combine, the same except accepts more than 1 arguments // I think the list data structure of dynamo is better than the Data Tree of GH, but that's me // DesignScript is so dope, esp. Node to Code, so dope // Using logical operators in DesignScript (same as nodes, except for 'not' which is '!') // eggshell vector addition example // 9.5next // Zero-Touch Importing A-FORGE, Importing .dll files into Dynamo // Only skimmed: 11. Web exp // Review example for Gradient Descent (also on GH exlab) //
 [Dynamo for Space Planning](http://dynamobim.org/home_usecases/use-case-1/) | | 00 ch | 13 ch | | | Very advanced, iteration, pollination, MV optimization
 [Dynamo Developer Resources](http://dynamobim.org/developer/index.html) | | 00 pg | 01 pg | | | advanced
 [Dynamo Mesh Toolkit](https://github.com/DynamoDS/Dynamo/wiki/Dynamo-Mesh-Toolkit) | Dynamo Team | 00 pg | 01 pg | | | plugin developed by the Dynamo Team
 [SFDUG August 2016: RTC 2016: Space Plan Generator](https://www.youtube.com/watch?v=ujG2Kans1UA) | San Francisco Dynamo User Group | 00:00 | 02:08 | | |
 [Help with Space Planning - Subhajit’s Code](https://forum.dynamobim.com/t/help-with-space-planning-subhajits-code/10773) | Dynamo Forum | 01 | 01 | | |
 |  |  |  |  | |  |
 | Study of Core Dynamo Nodes[Dynamo Dict](http://dictionary.dynamobim.com/) |  |  |  | |  |
 |  |  |  |  | |  |
 [Analyze](http://dictionary.dynamobim.com/#/Analyze) | Dynamo dictionary | 00.00 | 04.10 | | |
 [BuiltIn](http://dictionary.dynamobim.com/#/BuiltIn) | Dynamo dictionary | 00 | 41 | | |
 ⏳ [Core](http://dictionary.dynamobim.com/#/Core) | Dynamo dictionary | 09.01 | 20.07 | | 2018 | 8 = list
 [Display](http://dictionary.dynamobim.com/#/Display) | Dynamo dictionary | 00.00 | 02.01 | | |
 [Geometry](http://dictionary.dynamobim.com/#/Geometry) | Dynamo dictionary | A.00 | T.03 | | | A = Arc, T = Tessellation
 [Revit](http://dictionary.dynamobim.com/#/Revit) | Dynamo dictionary | S.00 | V.V3D | | | S = Selection, V = Views
 |  |  |  |  | |  |
 | Dynamo Packages |  |  |  | |  |
 |  |  |  |  | |  |
 [Dynashape](https://www.youtube.com/watch?v=h8DUVX6EpAY&list=PLapoQ_9M-ujcIKw0UmGY5pHhcoeWGJA2-) | Long Nguyen | 00 | 05 | | | [installation instructions at github](https://github.com/LongNguyenP/DynaShape), Open Source Physics engine for Dynamo similar to Kangaroo


 ### Dynamo Python
 Ongoing | Completed | Total
 :-- | :-- | :--
 05 | 03 | 15


Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
:-- | :-- | :-- | :-- | :-- | :-- | :--
 ⏳ [DynamoBIM Python Beginner's Guide](https://www.youtube.com/watch?v=GQaeIwIOIXs&list=PLlyMZ5IcKccjERFZwQgagGYFvitBKxVnu) | Danny Bentley | 09 | 17 | | 2018 | Watch Videos in Order, Skipped: 04: WindowsForms // `clr.AddReference(System.Windows.Forms)`, `from System.Windows.Forms import *`, similar to PyQT // Skipped 05: Read Excel // Skipped 06: Write Excel  // Already know 07: get-set parameters `param = get_Parameter(BuiltInParameter.<>) -> param.Set(<value>)` // 08: `doc.Create.NewFloor` // Known 09: FilteredElementCollector
 [DynamoBIM C# ZeroTouch Getting Started](https://www.youtube.com/watch?v=IBQBNAx1S8w&list=PLlyMZ5IcKcchm9hVskKtc9NXpy2QPYCC1) | Danny Bentley | 00 | 02 | | | C#, High quality
 [Intro to Zero Touch 101](https://www.youtube.com/playlist?list=PLGdDXXEHnr4WjwRKzIA1wPD1MhIRY-M2I) | Simply Complex Podcast | 00 | 05 | | | C#, In-Depth?
 [Revit API & python relations](https://forum.dynamobim.com/t/revit-api-python-relations/9188) | Forum Post | 0 | 1 | | | Understanding the default code of Dynamo Python Nodes and other caveats
 [Accessing the Entire Revit API Using Dynamo and Python](https://graitec.co.uk/blog/entry/accessing-the-entire-revit-api-using-dynamo-and-python) | Graitec Blog Post | 0 | 1 | | | Explanation of how to access the Revit API from Dynamo
 [Python 0.6.3 to 0.7.x Migration](https://github.com/DynamoDS/Dynamo/wiki/Python-0.6.3-to-0.7.x-Migration) | DynamoDS | 0 | 1 | | | Explanation of how the Dynamo Library wraps the RevitAPI
 ⏳ [Revit API Code Samples - Python](http://www.revitapidocs.com/code/Python) | Gui Talarico | 04 | ?? | | | [mirror](https://github.com/gtalarico/revitapidocs.code/tree/master/0-python-code), [full list of resources](https://github.com/gtalarico/python-revit-resources), esp [this](https://daren-thomas.gitbooks.io/scripting-autodesk-revit-with-revitpythonshell/content/where_to_learn_revit_api.html), and [this](http://help.autodesk.com/view/RVT/2017/ENU/?guid=GUID-8EB25D2A-3CAF-486A-BA8E-C2BEF3DB68F6) // Skipped 01: CreateWorksetSetting
 ✔ Dynamo for Revit Python Scripting | Lynda/Jeremy Graham | 32 | 32 | | 2017 | Basic, Very Good quality // 30 - DOPE example
 ⏳ [http://learndynamo.com/](http://learndynamo.com/) | Jeremy Graham | 01 | 15 | | 2018 | 01: Get room bounded by a ceiling //
 [SFDUG Sept 2017: Beginner's Guide to Python for Dynamo Users](https://www.youtube.com/watch?v=2e6tKofKsSo) | San Francisco Dynamo User Group/Danny Bentley | 00:00 | 01:13 | | | Alexa blew my mind
 ✔ [Dynamically Changed view to specified view](https://forum.dynamobim.com/t/call-view-to-open/17903/8) | Dynamo Forum | 01 | 01 | | 2018 | Can be used to see the changes your code do to speicfic views @ real time, key = `uiapp.ActiveUIDocument.RequestViewChange(myView)`
 Try viewing Dynamo DLL libraries inside VS  | Me | 01 | 01 | | | Maybe it contains something about [this?](http://dynamods.github.io/DynamoAPI/)
 ⏳ [Scripting Autodesk with RPS](https://daren-thomas.gitbooks.io/scripting-autodesk-revit-with-revitpythonshell/) | Daren Thomas | 01 | ?? | | | RevitAPI
 ⏳ [Python Nodes Basics](https://forum.dynamobim.com/t/python-nodes-basics/15872) | Dynamo Forum / Yna_Db | 02 | ?? | | | compilation of python resources for dynamo // dynamoPrimer: Recursion not available in ZeroTouch?, REVIEW AGENTS! // `DSCoreNodes`: Color, ColoRange2D, etc.. `Tessellation`, `DSOffice` // Review Unmanaged objects (disposing)
 ✔ [Dynamo SubTransactions](https://github.com/DynamoDS/Dynamo/issues/3520) | KSobon/Steell | 01 | 01 | | | discovered from archilab: Elements on sheet // SubTransactions: provides mechanisms for creating a transaction within a Transaction(usually dynamo transactions) // Usually used for getting the elements that would be deleted if a host object was deleted // part of the `DB` [namespace](http://www.revitapidocs.com/2018.1/801e5f17-cab0-044d-835c-a39592374f89.htm) // also discusses issues about having to regenerate the DB in order for some parameters to be 'settable' inside a python script

  ### Dynamo Packages
 Ongoing | Completed | Total
 :-- | :-- | :--
 00 | 03 | 04


 Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
 :-- | :-- | :-- | :-- | :-- | :-- | :--
  ✔ [Add new nodes to existing packages](https://github.com/DynamoDS/Dynamo/issues/470) | DynamoDS issues | 01 | 01 | | 2018 | Simply add to `C:\<>\Mi\AppData\Roaming\Dynamo\Dynamo Revit\1.3\packages\<package name>` the dyf files or whatever (including other files), then Manage Packages > Publish Version
  ✔ [Dynamo Primer: Publishing a Package](http://dynamoprimer.com/en/10_Packages/10-4_Publishing.html) | Danny Bentley | 01 | 01 | | 2018 | To add subcategories, use the format `Faraday.Subcategory1`
  [Ladybug Create Package JSON](https://github.com/ladybug-tools/ladybug-dynamo/blob/master/resources/createpackage/genDynamoPackage.py) | Mostapha | 00 | 01 | | 2018 | Until Dynamo team find a better solution this file creates a `pkg.json` file for Ladybug
  ✔ [Ladybug copy dyf files?](https://github.com/ladybug-tools/ladybug-dynamo/blob/master/plugin/copy_files.py) | Mostapha | 01 | 01 | coded my own version| 2018 | Probably copies dynamo dyf to Github repo folder, more IMPORTANTLY check out `C:\Users\<>\AppData\Roaming\Dynamo\Dynamo Revit\1.3\packages\Ladybug\extra\updategithub.py` - Desc: This script copies files and definitions from package fodler to github folder // created my own code [here](https://github.com/SpencerMAQ/Faraday/blob/master/__git_utilities/copy_files.py)


 ### Revit API
 Ongoing | Completed | Total
 :-- | :-- | :--
 02 | 06 | 18


Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
:-- | :-- | :-- | :-- | :-- | :-- | :--
 | [Download Revit SDK](http://usa.autodesk.com/adsk/servlet/index?siteID=123112&id=2484975)
 ✔  [Learn to program the Revit API by Boost Your BIM](https://www.udemy.com/revitapi/) | Udemy | 14.003 | 14.003 | 2 weeks | 2017 | Comprehensive, Priority, 7 hrs, C# // TaskDialog.Show // UIDocument = info about how the revit user interacts with the file, involves info about the view windows and selections // ALWAYS USE TRANSACTIONS // f.Symbols not working // skipped: 06.005: Extensible Storage, skipped: 06.007 Dynamic Model Update: e.g. user adds text, macro detects it isn't part of standards, deletes it // 07: not reviewed that much // 08: Doesn't contain anything // 10: paid// skipped: 06.001: ISelection Filter: because won't use that much inside Dynamo // 11.006: using selection sets to highlight elements after code runs
 ✔ [Revit Lookup](https://github.com/jeremytammik/RevitLookup) 10/10! | Jeremy Tammik | 00 | ?? | | 2018 | PRIORITY, Interactive Revit BIM database exploration tool to view and navigate element properties and relationships. // already installed [Installation](https://www.youtube.com/watch?v=z-VID-goD_E), [Installer](https://boostyourbim.wordpress.com/2017/04/28/revit-lookup-2018-install/), [Install using VS](https://forums.autodesk.com/t5/revit-api-forum/building-a-dll-from-source-files/m-p/4960758#M6080)
 ⏳  Revit SDK Examples | Autodesk | 000 | 145 | | | Revit 2017 SDK > Samples
 ⏳  [My First Plug-in Training](http://usa.autodesk.com/adsk/servlet/index?siteID=123112&id=16777469) | Autodesk | 00 | 08 | | | Working with room Geometry
 ✔ [Nathan's Revit API Notebook / RevitPythonShell](http://wiki.theprovingground.org/revit-api#toc3) | Nathan Miller | 14 | 14 | | 2018 | Python Scripting in revit, [sample scripts](https://github.com/daren-thomas/rps-sample-scripts) // 05: Form Creation // FamilyItemFactory for methods related to RefPlanes, Revolves, Extrusions, (obsoleted)NewDividedSurface -> DividedSurface.Create // 06: Divided Surfaces // 07: Families// 08: `AdaptiveComponentInstanceUtils.CreateAdaptiveComponentInstance(doc, famsymb)` // 09: OOP for grouping methods // 12: Excel (skipped) // 13: Randomization (looks like perlin wave) // 14: FREAKIN MOBIUS! using parametric equations
 [Revit API C# Getting Started](https://www.youtube.com/watch?v=C0mNU2bEUSs&list=PLlyMZ5IcKcci1TvB4qM9S8J-RKp0DhVWO) | Danny Bentley | 00 | 9 | | |
 ✔ [Python for Revit Course](https://www.youtube.com/watch?v=vsXsc2PYLCU&list=PLc_1PNcpnV5742XyF8z7xyL9OF8XJNYnv) | pyRevit | 09 | 09 | 2 days | 2017 | Approx 5 hours, Comprehensive, Priority, 10/10 for software and plugin
 ✔ [pyRevit: Core Tools](https://www.youtube.com/watch?v=pIjDd4dZng0&list=PLc_1PNcpnV55VgYBfrIPrvjZjsvwki8LR) | pyRevit | 10 | 10 | | 2017 | Such a dope piece of software! // Skipped 05: copying entire sheet from one project to another
 ✔ [pyRevit: Working with Extensions](https://www.youtube.com/watch?v=zERdPh1vNBQ&list=PLc_1PNcpnV57OIsHFkc-zLFynurA6_jJR) | pyRevit | 05 | 05 | 1 day | 2017 |
 [IronPython Helper ](https://github.com/PMoureu/iph) | PMoureu | 00 | 01 | | | Revit Plugin: Half lookup, half doc reader, half visual debugger
 [Introduction to Revit 2015 Programming Part 1](https://www.youtube.com/watch?v=l8dQxoAjSP8&list=PLoC0VXzQcUC7jaS2wFQjwXSGZzq5WVTvN) | Autodesk DevTV | 0 | 20:01 | | |
 [Introduction to Revit 2015 Programming Part 2](https://www.youtube.com/watch?v=zL8pQRJbcyA&index=2&list=PLoC0VXzQcUC7jaS2wFQjwXSGZzq5WVTvN) | Autodesk DevTV | 0 | 33:39 | | |
 [Revit API](https://www.youtube.com/watch?v=la8DBrKVCxc&list=PLokG6yd7UBRDDB7jo15ntPUQ947z_5Bu7) | KrispCAD | 0 | 2 | | | 20 mins
 [Revit API Labs](https://github.com/ADN-DevTech/RevitTrainingMaterial) | KrispCAD | 0 | 2 | | | sample files, AKA RevitTrainingMaterial from github, [mirror](http://usa.autodesk.com/adsk/servlet/index?id=2484975&siteID=123112), look for 'API Labs'
 [Nathan's Revit API Notebook](http://wiki.theprovingground.org/revit-api) | The Proving Ground | 0 | ?? | | | Comprehensive
 [RevitLookup](https://github.com/jeremytammik/RevitLookup) | jeremytammik | 0 | 1 | | | [stackoverflow](https://stackoverflow.com/questions/35271719/gettings-information-about-stairsruns-and-stairs-from-elements-containing-such-i/35287808#35287808), http://www.revitapidocs.com/
 [Revit API Guide/About](http://thebuildingcoder.typepad.com/blog/about-the-author.html#2) | jeremytammik | 0 | ?? | | | VERY Comprehensive
 [Understanding get_](https://forums.autodesk.com/t5/revit-api-forum/hidden-methods-in-api/td-p/7028612) | ?? | 0 | ?? | | | daeff, also [MORE IMPORTANTLY, this](http://thebuildingcoder.typepad.com/blog/2009/09/document-elements.html)


 ----


 ## VCS
 Ongoing | Completed | Total
 :-- | :-- | :--
 01 | 01 | 01


 ### Github
Title | Author | Progress | Total | Duration | Last Reviewed | Remarks |
:-- | :-- | :-- | :-- | :-- | :-- | :--
 ⏳ O'Reilly - Learning GitHub |  | 7.01 | 13.07 | | 2017 | study once a week maybe
