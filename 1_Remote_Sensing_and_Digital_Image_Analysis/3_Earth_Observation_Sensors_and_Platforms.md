# Earth Observation Sensors and Platforms

<p>We are sensing energy that is EM energy either it is reflected, emitted, or backscatter.</p>

<p>RS sensors which are used for earth observation purposes they can work beyound that wavelength. It can use IR, thermal IR, and mmicrowave.</p>

<p>Sun ----------->//- - -clouds- - -\\----------->Target</p>
<p>Target<--------//- - -clouds- - - -\\---------->Satellite Sensor</p>
<p>Satellite Sensor---------->Ground Reciever & Processing Station</p>
<p>Satellite Sensor----------->SatCom----------------->Ground Reciever & Processing Station</p>

### Sensors and Platforms that are used to create image data of the earth.
### Sensor:
<p>A device that records EM energy</p>

### Platform:
<p>Carrier bed used to carry a sensor</p>
<p>Such as Groundbased, Airborne, Spaceborne</p>

<hr>
<p> 1827: first photograph</p>
<p> 1858: first aerial photograph from hot air baloon</p>
<p> 1957: sputnik 1 satellite by russia.</p>
<p> 1975: aryabhatta satellie by india.</p>
<p> 1967: NASE "Earth Resource Technology Satellite" programme -> first RS satellite</p>
<hr>

### Satellite Referencing Scheme
<p>A Satellite Referencing Scheme refers to the methods and protocols used for locating, communicating with, and referencing satellites in space for various purposes such as communication, navigation, Earth observation, and more</p>
- Path : Path refers to the satellite's orbital track, which is the north-south trajectory that the satellite follows as it orbits the Earth.
- Row : Row refers to the position of the satellite along its east-west swath, which represents how far the satellite is in its orbit when taking an image.
- Swath : A swath in satellite terminology refers to the strip of the Earth's surface that a satellite sensor observes or images during a single pass over the Earth. It represents the width of the area that the satellite captures as it moves along its orbit. Essentially, it's the ground area covered by the satellite's sensors in one pass.

### Satellite Orbital Characterstics
- Altitude
- Inclination Angle
- Period
- Repeat Cycle
- Swath
- Ascending path & Descending path.

<p><b>Altitude : </b> Definition: The altitude is the height of the satellite above the Earth’s surface. It is measured from the Earth's surface to the satellite’s position in orbit.</p>
- Types:
- - Low Earth Orbit (LEO): 160 km to <!--2,000-->300 km above Earth (e.g., Earth observation satellites like Landsat).
- - Medium Earth Orbit (MEO): <!--2,000-->300 km to <!--35,786-->6400 km (e.g., GPS satellites).
- - Geostationary Orbit (GEO): 35,786 km above Earth (e.g., communication satellites that appear stationary relative to the Earth).

<p><b>Inclination Angle : </b>The inclination is the angle between the satellite's orbital plane and the Earth’s equatorial plane.</p> 
- Types of Orbits:
- - Equatorial orbit (0°): Orbits along the equator.
- - Polar orbit (90°): Passes over the Earth’s poles, providing global coverage.
- - Sun-synchronous orbit: Typically between 98°-99° inclination, allowing the satellite to pass over the same location at the same local solar time.

<p><b>Period : </b>The period is the time it takes for a satellite to complete one full orbit around the Earth.</p>
<p><b>Repeat Cycle : </b> The repeat cycle is the time it takes for a satellite to pass over the same point on the Earth's surface again.</p>
<p><b>Revisit Time : </b> Time b/w two subsequential images of same area.</p>

<p><b>Swath : </b> The swath is the width of the strip of the Earth's surface that the satellite can observe or image in one pass.</p>

<p><b>Ascending Path & Descending Path : </b>These terms describe the direction in which the satellite is moving relative to the Earth during its orbit.</p>
- Ascending Path: When the satellite is moving northward, from the southern hemisphere to the northern hemisphere.
- Descending Path: When the satellite is moving southward, from the northern hemisphere to the southern hemisphere.
<hr>

### 1. Imaging Sensors
<p>These sensors create images of the Earth's surface by detecting and recording electromagnetic radiation (EMR) in various bands.</p>

- A. Passive Sensors:
Definition: Passive sensors rely on natural sources of energy (such as sunlight) to capture reflected or emitted radiation from the Earth's surface.

Examples:

- - Photographic Camera:
Captures images using visible light, much like traditional cameras. It records the sunlight reflected from objects.
- - Optical Scanner:
Measures reflected light and breaks it into various bands of the electromagnetic spectrum. These sensors are used in remote sensing for mapping.
- - - Across-Track Scanner (Whiskbroom):
Scans the Earth's surface perpendicular to the satellite’s motion by sweeping back and forth.
Example: Landsat MSS (Multispectral Scanner).
- - - Along-Track Scanner (Pushbroom):
Scans the Earth along the satellite’s path using a linear array of detectors.
Example: Landsat TM (Thematic Mapper).
- - Thermal Scanner:
Detects infrared radiation emitted by objects, which is a measure of their heat.
Example: Used for mapping land and sea temperatures, detecting forest fires, etc.

- B. Active Sensors
Definition: Active sensors emit their own source of energy and measure the reflected or backscattered signal to form images.

Examples:

- - SAR (Synthetic Aperture Radar):
A form of radar used to create high-resolution images by transmitting microwaves and measuring their reflection.
Can capture images day or night and through clouds.
Example: RADARSAT, Sentinel-1.
- - LiDAR (Light Detection and Ranging):
Uses laser pulses to measure distances by timing the return of the light that reflects off the surface.
Often used for topographical mapping and forestry applications.
Example: Airborne LiDAR systems for terrain mapping.

### 2. Non-Imaging Sensors
Non-imaging sensors do not produce detailed images but instead measure specific characteristics like radiation intensity, altitude, or distances.

- A. Passive Sensors
Definition: Passive non-imaging sensors measure natural energy emitted or reflected by objects.

Examples:

- - Spectroradiometers:
Measure the intensity of different wavelengths of electromagnetic radiation (across multiple spectral bands).
Used for monitoring vegetation, atmospheric properties, and water quality.
Example: MODIS (Moderate Resolution Imaging Spectroradiometer) on NASA's Terra and Aqua satellites.
- B. Active Sensors
Definition: Active non-imaging sensors emit their own energy and detect the reflected or backscattered signals to measure specific properties.

Examples:

- - Laser Distance Meter:
Measures distances by emitting a laser beam and calculating the time it takes for the beam to reflect back.
Example: Used in surveying, engineering, and topography.
- - Laser Water Depth Meter:
Measures the depth of water bodies by emitting laser pulses and timing their reflection from the water surface and bottom.
Example: Used in bathymetric studies and hydrographic surveys.
- - Microwave Altimeter:
Measures altitude by timing the return of microwave signals reflected off the Earth's surface.
Example: Jason-3 satellite uses microwave altimeters for ocean topography.

<hr>

### Across Track Scanner(Whiskboom)
- Dwell Time = Scan rate per line/No. of cells per line.
= 2X10^-2 sec/2000 cells = 1X10^-5

### Along Track Scanner(Pushboom)
- Dwell Time = Cell dimension/Velocity.
= 10m cell^-1/200 m.sec^-1 = 5X10^-2 sec.cell^-1

### High Resolution Imaging Mode
- Time Delay Integration
- Step & Stare

### Resolution
<p>In remote sensing, resolution refers to the level of detail that can be captured by a sensor.</p>
**four resolution of RS:**
- Spatial : Spatial resolution refers to the size of the smallest object or feature that can be resolved by the sensor on the ground.
- Spectral : Spectral resolution refers to the ability of a sensor to distinguish between different wavelengths or spectral bands of electromagnetic radiation.
- Radiometric : Radiometric resolution refers to the sensor’s ability to distinguish between slight differences in energy (brightness or reflectance) levels.
- Temporal : Temporal resolution refers to the frequency at which a satellite or sensor revisits and captures imagery of the same location on the Earth's surface.