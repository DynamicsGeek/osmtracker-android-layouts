Trail Mapping
============
This layout is intended to survey information to support tagging paths (a.k.a Trails in the US), specifically for hiking, but also for mountain biking and horseback riding.
https://wiki.openstreetmap.org/wiki/Hiking
https://wiki.openstreetmap.org/wiki/Tag:highway=path
https://wiki.openstreetmap.org/wiki/United_States/Trails_Stewardship_Initiative
opentrailsmap

This layout draws from the original (Walk Ride Detailed) and work by rkdarst (Hiking) 
This layout views best in landscape mode
Tags support the identification of SAC scale with suggestions based on width, visibility, smoothness, steepness, hand use, and fall risk based on definitions of SAC Scale

Pages of button sets  
--------------------


Photo or Voice of Text Fields (Name, Operator)

<layout name="Access">
	<!-- Row 1 : (home) informal=yes, access=no; access=private	-->
	<!-- Row 1 : foot+bike+horse=des, foot+bike=des, foot=des; segregrated=yes	-->
	<!-- Row 2 : horse=no, bike=no, dog=no, dog=leashed	-->
	<!-- Row 3 : wheelchair=des, snowmobile=des, ski=des, motor=yes	-->
<layout name="RouteMarking">
	<!-- Row 1: (Home) (Access) (Ammenities) (Ratings)	-->
	<!-- Row 2: osmc:symbol=black⬛,  osmc:symbol=gray, osmc:symbol=white⬜,	--> 
	<!-- Row 3: osmc:symbol=red🟥, osmc:symbol=green🟩, osmc:symbol=blue🟦  	-->
	<!-- Row 4: osmc:symbol=yellow🟨, osmc:symbol=orange🟧, osmc:symbol=purple🟪, osmc:symbol=brown🟫			-->
<layout name="Ratings">
	<!-- Row 1: (Home) (Difficulty)  SAC=hiking (T1), SAC=mountain hiking (T2),  	-->
	<!-- Row 2: SAC=demanding_mountain_hiking (T3), SAC=alpine_hiking (T4), SAC=demanding_alpine_hiking (T5), SAC=difficult_alpine_hiking (T6) 	-->
	<!-- Row 3: MTB:scale=0 (white), MTB:scale=1 (green:easy), MTB:scale=2 (blue:moderate) MTB:scale=3 (blue-black:difficult)	-->
	<!-- Row 4: MTB:scale=4 (black:very difficult)  MTB:scale=5 (double black:extreme)  MTB:scale=6 (orange:expert) (Access)	-->
<layout name="Visibility">
	<!-- Row 1: (Home), visibility=excellent (Clearly visible path/markers T1)	-->
	<!-- Row 2: trailblazed=yes, visibility=good (Path/marker visible when searched T2)	-->
	<!-- Row 3: trailblazed=cairnes, visibility=bad (Path/markers sometimes invisible T3), -->
	<!-- Row 4: trailblazed=poles, visibility=no (Mostly pathless/no markers T4+)	-->
<layout name="WidthSurface">
	<!-- Row 1 : (Home) (difficulty) width=0.15 (6in T3), 0.3 (12in T2) -->
	<!-- Row 2 : width=0.5 (20in T1), 1.0 (3ft), 2.0 (7ft), 4.0 (13ft)-->
	<!-- Row 3 : Surface = ground, concrete, steppping_stones, stone, -->
	<!-- Row 4 : Surface = fine_gravel,gravel,wood,metal -->
<layout name="Smooth">
	<!-- Row 1: (Home), smoothness=excellent (0-0.2in), -->
	<!-- Row 2: smoothness=good (0.2-0.5in), smoothness=intermediate (0.5-1in) 	--> 
	<!-- Row 3: smoothness=bad(1-3in T1), smoothness=very_bad (3-6in T2), -->
	<!-- Row 4: smoothness=horrible (6-10in T2), smoothness=very_horrible (10-20in T3), -->
	<!-- Row 5: smoothness=impassable (over 20in T4+)	-->  
<layout name="Difficulty">
	<!-- Row 3: gentle incline (0-40% T1), short steep (40-70% T2) -->
	<!-- steep (70-100% T3), extremely steep (ov 100% T4)  	-->
	<!-- Row 4: fall:limited (T2), fall:significant injury (T3) -->
	<!-- hands:required to maintain balance (T3), hands:required to advance (T4) 	-->
<layout name="PathStructures">
	<!-- Row 1: (Home), (WidthSurface), highway=steps, handrail=yes, 	-->
	<!-- Row 2: highway=trailhead, highway=ladder, ford=stepping_stones, ford=yes,   	-->
	<!-- Row 3: bridge=yes, bridge=boardwalk, bridge=trestle, barrier=stile	-->
	<!-- Row 4: barrier=gate, barrier=kissing_gate, barrier=swing_gate, barrier=chain	-->
<layout name="Amenities">
	<!-- Row 1: (Home) (RouteMarking) (PathStructures), amenity=bbq -->
	<!-- Row 2: shelter_type=sun_shelter, information=route_marker (direction only), information=guidepost (destination distance), information=map	-->
	<!-- Row 3: leisure=picnic_table, amenity=toilets, amenity=parking, -->
	<!-- Row 4: amenity=drinking_water, amenity=bench, backrest=yes, -->
<layout name="Overnight">
	<!-- Row 1: (home) (Amenities) (PathStructures)	-->
	<!-- Row 2: tourism=camp_pitch, informal=yes, leisure=firepit, amenity=bear_box  	-->
	<!-- Row 3: shelter_type=lean_to, shelter_type=basic_hut, shelter_type=wilderness_hut , sheter_type=alpine_hut, 	-->
	<!-- Row 4: capacity=1, capacity=2, capacity=4, capacity=8	--> 
<layout name="NaturalFeatures"> 
	<!-- Row 1: (Home) (Difficulty) (Amenities) (PathStructures)		-->
	<!-- Row 2: waterway=stream, natural=spring; water=pond; waterway=waterfall 	-->
	<!-- Row 3: natural=cliff, tourism=viewpoint	-->
	<!-- Row 4: direction= N, direction= N, direction= N, direction= N)			-->


TODO: Research icons to align with OSM rendering of features
TODO: Research which tags are most commonly associated with highway=path  https://taginfo.openstreetmap.org/tags/highway=path#combinations
