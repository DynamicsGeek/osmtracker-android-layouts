Trail Mapping
============
This layout is intended to survey information to support tagging paths (a.k.a Trails in the US), specifically for hiking, but also for mountain biking and horseback riding.
https://wiki.openstreetmap.org/wiki/Hiking
https://wiki.openstreetmap.org/wiki/Tag:highway=path
https://wiki.openstreetmap.org/wiki/United_States/Trails_Stewardship_Initiative

This layout draws from the original 

Button sets or pages  
--------------------

The button sets should assist you with surveying such features as a 'track' which is used by farm vehicles, but is also a Public Right of Way (UK probably), designated as a **footpath**.  
**Button sets include**;  



*  **LOOKS LIKE** - allows you to chose what the feature looks like, such as a track or a path.  
*  **DESIGNATION** - if signed, allows you to note the designation displayed.  
*  **ACCESS** - Who is allowed such as foot=yes, bike=no.  
*  **SURFACE** - Asphalt, gravel, grass, etc..  
*  **BARRIER** - Bollards, gates, kissing-gates, stiles (with buttons for steps up to or down from), etc..   
*  **VARIOUS** - Is it lit? Are dogs allowed, are there dog-poo bins? Bench & information boards.  
*  **WIDTH** - 9 buttons of different options.    
*  **SOLAR -ERRORS** - Roof PV panels and orientation, and 'Errors' for those moments when you took the wrong fork and want to have a note of this.  
*  **TRACKTYPE** - Buttons for each of the grades. 
*  **SMOOTHNESS** - Buttons for each grade, with an indication as to you should tag it as.


Photo or Voice of Text Fields (Name, Operator)
Three buttons on a row gives about 8 or 9 letters, four buttons give 6 or 7
Keep Photo and Voice on each sub page.  Too bad there is not a "back" button on screen.

Acess: 
Row 1 : Ft+Bike+Horse:Des, Foot+Bike: Des, Foot: Des; Seg=yes
Row 2 : Horse No; Bike No; Dog No; Dog leashed
Row 3 : Wheelchair: Des; Ski Des; Snow Des
Row 4 : Informal - Yes, Access = No; Access= Private; Motor= yes

Surface
Row 1 : Width 6" (0.15M), 12" (.3M", 19" (0.5M), 39" (1.0M) 72" (2.0M)
Row 2 : 39" (1.0M), 60" (1.5M), 79" (2.0M)
Row 3 : Surface: ground, paved, paving_stones,compacted,
Row 4 : fine_gravel,gravel,wood,metal

Visibility
Row 1: photo, information post
Row 2	"excellent" short_description="Unambiguous path or markers everywhere" />
		"good" short_description="Path or next marker always visible, but sometimes has to be searched for" />
Row 3	"bad" short_description="Path (or markers) sometimes invisible/absent, route partly pathless " />
		"no" short_description="Mostly pathless or no markers" />
Row 4: Traileblazed yes, Trailbazed Cairnes, TB: Poles, TB: Symbols;
<row>
			<button type="tag" label="Blue 🟦"/>
			<button type="tag" label="Green 🟩"/>
			<button type="tag" label="Orange 🟧"/>
			<button type="tag" label="Purple 🟪"/>
		</row>
		<row>
			<button type="tag" label="Red 🟥"/>
			<button type="tag" label="White ⬜"/>
			<button type="tag" label="Yellow 🟨"/>
			<button type="tag" label=""/>
		</row>
		

Challenge
Row 1: SAC T1, SAC T2, SAC T3, SAC T4, SAC T5, SAC T6
Row 2: Fall potential - Limited, significant injury, Hands - required to maintain balance, required to advance,
Row 3: Obstacles (1", 1-3" 3-6", 
Row 4: Obstacles  6-10", 10-14", Over 16"  

sac_scale
				<list_entry value="hiking" display_value="T1 - hiking trail" short_description="Trail well cleared. Area flat or slightly sloped, no fall hazard" />
				<list_entry value="mountain_hiking" display_value="T2 - mountain hiking trail" short_description="Trail with continuous line and balanced ascent. Terrain partially steep, fall hazard possible" />
				<list_entry value="demanding_mountain_hiking" display_value="T3 - difficult, exposed hiking trail" short_description="exposed sites may be secured with ropes or chains, possible need to use hands for balance. Partly exposed sites with fall hazard, scree, pathless jagged rocks" />
				<list_entry value="alpine_hiking" display_value="T4 - difficult, exposed, steep alpine trail" short_description="sometimes need for hand use to get ahead. Terrain quite exposed, precarious grassy acclivities, jagged rocks, facile snow-free glaciers" />
				<list_entry value="demanding_alpine_hiking" display_value="T5 - difficult alpine trail with climbing" short_description="single plainly climbing up to second grade. Exposed, demanding terrain, jagged rocks, few dangerous glacier and snow" />
				<list_entry value="difficult_alpine_hiking" display_value="T6 - hazardous alpine trail with climbing" short_description="climbing up to second grade. Often very exposed, precarious jagged rocks, glacier with danger to slip and fall" />
			</combo>

mtb:scale" text="MTB Scale" values="0-,0,0+,1-,1,1+,2-,2,2+,3-,3,3+,4-,4,4+,5-,5,5+,6-,6,6+" values_sort="false" values_no_i18n="true" />
smoothness" text="Smoothness" values_searchable="true" values_sort="false">
				<list_entry value="excellent" short_description="Thin Rollers: rollerblade, skateboard" />
				<list_entry value="good" short_description="Thin Wheels: racing bike" />
				<list_entry value="intermediate" short_description="Wheels: city bike, wheelchair, scooter (1 in)" />
				<list_entry value="bad" short_description="Robust Wheels: car (3in)" />
				<list_entry value="very_bad" short_description="High Clearance: light duty OHV (6in)" />
				<list_entry value="horrible" short_description="Off-Road: heavy duty OHV (10in)" />
				<list_entry value="very_horrible" short_description="Specialized off-road: tractor, ATV (14in)" />
				<list_entry value="impassable" short_description="Climbing" />
			</combo>
			<combo key="bridge" text="Bridge" values="yes,boardwalk,trestle" values_sort="false" />
			<combo key="ford" text="Ford" values="yes,stepping_stones" values_sort="false" />

Path Structure

Stairs (uneven, manmade, railing)
Ladder
ford = yes Create a section of the way if long or just tag the node if the trails crosses water.  (maybe add depth= if you might get ankles wet) or =stepping_stones (Tag:ford=yes - OpenStreetMap Wiki)
bridge
gates
   <button type="tag" label="gate" icon="TrailMapping_icons/narrow-gate.png" />

Ammenities
parking
Toilet
Camp Pitch (1 tent, 2 tents, 4 tents, 6 tents) (consider how to incorporate informal=yes for allowed by not maintained, and acccess=no)
leisure=firepit (https://wiki.openstreetmap.org/wiki/Tag:leisure%3Dfirepit )
leisure=picnic_table (https://wiki.openstreetmap.org/wiki/Tag:leisure%3Dpicnic_table )
tourism=information; information=guidepost; hiking=yes; guide_type=intermediary (for a directional arrow without name/mileage)(https://wiki.openstreetmap.org/wiki/Tag:information%3Dguidepost )
amenity=bench
leisure=picnic_table
	<button type="tag" label="Lean-to"/>
			<button type="tag" label="Basic hut"/>
		

Water 


natural=water + drinking_water=untreated for water sources along a backpacking trail, and 
<button type="tag" label="Stream"/>
	<button type="tag" label="Waterfall"/>
		Natural spring
		pond
			
Overlook

tourism=viewpoint (Tag: tourism=viewpoint - OpenStreetMap Wiki)
<button type="tag" label="Viewpoint"/>
			
direction=SW-W (or N, S, E, W) for the direction of the view, from left to right

name= if named


------
ccess: Foot/Bicycle/Horse: Designated, Yes, No (any thing complex use voice recordingg
Maybe typical combos: Desgnated Foot/Bicycle/Horse, Designate Foot/ No Horse-Bicycle, Designated Foot, Bicycle, No horse
Separate No Horse, No Bicycle (I would not be there if no foot)
Assume No Motor Vechicle, add Motor Vehicle Yes)
			<combo key="foot" text="Foot" values="yes,no,designated,permissive,permit,private" values_sort="false" />
			<combo key="bicycle" text="Bicycle" values="yes,no,designated,permissive,permit,private, dismount" values_sort="false" />
			<combo key="horse" text="Horse" values="yes,no,designated,permissive,permit,private, dismount" values_sort="false" />
			<combo key="motor_vehicle" text="Motor vehicles" values="yes,destination,delivery,permissive,permit,private,agricultural,forestry,no" values_sort="false" match="key" />
Informal = yes
Segregated = yes
Access = yes,no,permissive,private,discouraged
			<combo key="wheelchair" text="Wheelchairs" values="yes,designated,limited,no" values_sort="false" />
			<combo key="ski" text="Ski" values="yes,designated,permissive,permit,private,no" values_sort="false" /> 	
			<combo key="snowmobile" text="Snowmobile" values="yes,designated,permissive,destination,delivery,permit,private,no" values_sort="false" />
			<combo key="dog" text="Dog" values="yes,leashed,unleashed,designated,permissive,permit,private,no" values_sort="false" match="key" />

width" text="Width (meters)" />
		(6" 12" 18" 24")
