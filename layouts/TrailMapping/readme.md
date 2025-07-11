Trail Mapping
============
This layout is intended to survey information to support tagging paths (a.k.a Trails in the US), specifically for hiking, but also for mountain biking and horseback riding.
https://wiki.openstreetmap.org/wiki/Hiking
https://wiki.openstreetmap.org/wiki/Tag:highway=path
https://wiki.openstreetmap.org/wiki/United_States/Trails_Stewardship_Initiative
opentrailsmap

This layout draws from the original and work by rkdarst
This layout views best in landscape mode, and anternatives is designed for portrait mode
Tags support the identification of SAC scale with suggestions based on width, visibility, smoothness, steepness, hand use, and fall risk based on definitions of SAC Scale

Button sets or pages  
--------------------


Photo or Voice of Text Fields (Name, Operator)


<layout name="Access"> 
	<!-- Row 1 : foot+bike+horse=des, foot+bike=des, foot=des; Seg=yes	-->
	<!-- Row 2 : horse=no; bike=no; dog=no; dog=leashed	-->
	<!-- Row 3 : wheelchair=des; ski=des; snowmobile=des	-->
	<!-- Row 4 : informal=yes, access=no; access=private; motor=yes	-->

<layout name="RouteMarking">
	<!-- Row 1: (Home) (Visibility) (Access) (Ammenities)	-->
	<!-- Row 2: osmc:symbol=black⬛,  osmc:symbol=gray, osmc:symbol=white⬜,	--> 
	<!-- Row 3: osmc:symbol=red🟥, symbol=green🟩, osmc:symbol=blue🟦  	-->
	<!-- Row 4: osmc:symbol=yellow🟨, osmc:symbol=orange🟧, osmc:symbol=purple🟪, osmc:symbol=brown🟫			-->

<layout name="WidthSurface">
	<!-- Row 1 : (Home) (difficulty) width=0.15 (6in T3), 0.3 (12in T2) -->
	<!-- Row 2 : width=0.5 (20in T1), 1.0 (3ft), 2.0 (7ft), 4.0 (13ft)-->
	<!-- Row 3 : surface=ground, concrete, steppping_stones, stone -->
	<!-- Row 4 : surface=fine_gravel, gravel, wood, metal -->

<layout name="Visibility">
	<!-- Row 1: (Home), (Dificulty), (WidthSurface), (Marking)	-->
	<!-- Row 2: visibility=excellent (Clearly visible path/markers T1), visibility=good (Path/marker visible when searched T2)	-->
	<!-- Row 3: visibility=bad (Path/markers sometimes invisible T3), visibility=no (Mostly pathless/no markers T4+)	-->
	<!-- Row 4: traileblazed=yes, trailbazed=cairnes, trailblazed=poles, trailblazed=symbols	-->

<layout name="Difficulty">
	<!-- Row 1: (Home), smoothness=excellent (0-0.2in), smoothness=good (0.2-0.5in), smoothness=intermediate (0.5-1in) 	--> 
	<!-- Row 2: smoothness=bad(1-3in T1), smoothness=very_bad (3-6in T2), smoothness=horrible (6-10in T2), smoothness=very horrible (10-20in T3), smoothness=impassable (over 20in T4+)	-->  
	<!-- Row 3: steepness:Gentle (0-40% T1), steepness:short steep (40-70% T2), steepness:steep (70-100% T3), steepness:extremely steep (ov 100% T4)  	-->
	<!-- Row 4: fall:limited (T2), fall:significant injury (T3), hands:required to maintain balance (T3), hands:required to advance (T4) 	-->

<layout name="Ratings">
	<!-- Row 1: (Home) (Difficulty)  SAC=hiking (T1), SAC=mountain hiking (T2),  	-->
	<!-- Row 2: SAC=demanding_mountain_hiking (T3), SAC=alpine_hiking (T4), SAC=demanding_alpine_hiking (T5), SAC=difficult_alpine_hiking (T6) 	-->
	<!-- Row 3: MTB:scale=0 (white), MTB:scale=1 (green/easy), MTB:scale=2 (blue/moderate) MTB:scale=3 (blue-black/difficult)	-->
	<!-- Row 4: MTB:scale=4 (black/very difficult)  MTB:scale=5 (double black/extreme)  MTB:scale=6 (orange/expert) (Access)	-->

<layout name="PathStructures">
	<!-- Row 1: (Home), (WidthSurface), highway=steps, handrail=yes, 	-->
	<!-- Row 2: highway=ladder, ford=yes, ford=stepping_stones  	-->
	<!-- Row 3: bridge=yes, bridge=boardwalk, bridge=trestle, barrier=stile	-->
	<!-- Row 4: barrier=gate, barrier=kissing_gate, barrier=swing_gate, barrier=chain	-->

<layout name="Amenities">
	<!-- Row 1: (Home) (RouteMarking) (PathStructures)
	<!-- Row 2: information=route_marker (direction only), information=guidepost (destination/distance), information=map	-->
	<!-- Row 3: amenity=parking, amenity=toilets, leisure=picnic_table, amenity=drinking_water	-->
	<!-- Row 4: amenity=bench backrest=yes; amentity=charcoalgrill; shelter_type=sun_shelter 	-->
	
<layout name="Overnight">
	<!-- Row 1: (home) (Amenities) (PathStructures)	-->
	<!-- Row 2: tourism=camp_pitch, informal=yes; leisure=firepit; ??=bearbox  	-->
	<!-- Row 3: shelter_type=lean_to, shelter_type=basic_hut, shelter_type=wilderness_hut , sheter_type=alpine_hut, 	-->
	<!-- Row 4: capacity=1, capacity=2, capacity=4, capacity=8	--> 

<layout name="NaturalFeatures"> 
	<!-- Row 1: (Home) 	-->
	<!-- Row 2: waterway=stream, natural=spring; water=pond; waterway=waterfall 	-->
	<!-- Row 3: natural=cliff, tourism=viewpoint (Tag: tourism=viewpoint - OpenStreetMap Wiki)	-->
	<!-- Row 4: View N, View S, View E, View W)			-->


Research icons to align with OSM rendering of features (Potlatch?)
Research which tags are most commonly associated with highway=path  https://taginfo.openstreetmap.org/tags/highway=path#combinations
