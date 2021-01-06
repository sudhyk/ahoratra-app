
**HoroData API**
----


* **URL**

 https://secure.ahoratra.app/horodata/v2

* **Method:**

  `GET`
  
*  **URL Query Params**

   **Required:**
 
   `lat=[Float]`- Latitiude <br />
   `lon=[Float]`- Longitude <br />
   `alt=[Float]`- Altitude in meters <br />
   `offset=[integer]`- TimeZone offset in Seconds, Ex. 19800 for IST ( 5.5 hours ) and -18000 for EST <br />

   `day=[Integer]`- Day - [1-31] <br />
   `month=[Integer]`- Month - [1-12] <br />
   `year=[Integer]`- Year - [1900-2100] <br />

   `hours=[Integer]`- Hours - [0-23] <br />
   `minutes=[Integer]`- Minutes - [0-59] <br />
   `seconds=[Integer]`- Seconds - [0-59] <br />


   **Optional:**
    none
    
* **Success Response:**
  
  <_What should the status code be on success and is there any returned data? This is useful when people need to to know what their callbacks should expect!_>

  * **Code:** 200 <br />
    **Content:** `{"muhurtha":[{"start":2451822.691568563,"muhurtha":"Dur1","end":2451822.724458747},{"start":2451822.757348931,"muhurtha":"Abhijeet","end":2451822.7902391152},{"start":2451822.8354631183,"muhurtha":"Rahu","end":2451822.897132213},{"start":2451822.650455833,"muhurtha":"Gulika","end":2451822.712124928},{"start":2451822.527117643,"muhurtha":"Yamaganda","end":2451822.588786738},{"start":2451822.8889096673,"muhurtha":"Dur2","end":2451822.921799851}],"panchanga":{"dinamana":{"seconds":26,"minutes":50,"hours":11,"type":"dinamana"},"nakshatra":20,"tithiDetails":[{"tithi":7,"start":2451821.311409359,"end":2451822.4052142566},{"tithi":8,"start":2451822.4052142566,"end":2451823.5122975055},{"tithi":9,"start":2451823.5122975055,"end":2451824.6213881997}],"ritu":"Sharad","ayana":"Dhakshinayana","yoga":6,"sunrise":2451822.527117643,"moonset":2451823.271339505,"sunset":2451823.020470403,"moonrise":2451822.79046193,"inputjd":2451823.2291683913,"sakasamvat":"Vikrama","pada":3,"isAdhikaMasa":false,"nakshatraDetails":[{"nakshatra":19,"start":2451822.2299394514,"pada":4,"end":2451822.509186895},{"nakshatra":20,"pada":1,"end":2451822.791978303,"start":2451822.509186895},{"nakshatra":20,"start":2451822.791978303,"end":2451823.073928456,"pada":2},{"nakshatra":20,"pada":3,"end":2451823.356268562,"start":2451823.073928456},{"nakshatra":20,"pada":4,"start":2451823.356268562,"end":2451823.637409017}],"vaara":5,"nextdaySunrise":2451823.527170423,"chandraMasa":"Ashwina","tithi":8,"karana":"Bava","suryaMasa":"Kanya","ratrimana":{"hours":12,"seconds":39,"minutes":9,"type":"ratrimana"}},"charts":{"transit":[{"rashi":6,"bhava":11,"items":[{"lat":4.32061361072398,"graha":"Chandra","speed":14.155912386357263,"lon":179.99776378744704},{"lat":0,"graha":"Yamaghantaka","speed":0,"lon":162.92465388860842}]},{"rashi":10,"bhava":3,"items":[{"lat":-2.119580552669643,"graha":"Bhuda","speed":1.6423630397387716,"lon":273.32175184005024},{"lat":-0.4960892653270741,"graha":"Guru","speed":0.23166026953867147,"lon":280.0068556109559},{"lat":-0.3941274401170532,"graha":"Shani","speed":0.11618093391746366,"lon":278.164150612871},{"lat":-1.203300643536013,"graha":"Yama","speed":0.033031553627862635,"lon":270.23744777846224}]},{"rashi":1,"bhava":6,"items":[{"lat":0.9800099932214605,"graha":"Kuja","speed":0.4580620274872733,"lon":5.863930886630609},{"lat":-0.44760924477044745,"graha":"Aruna","speed":-0.006513622566701893,"lon":12.599441393915134}]},{"rashi":7,"bhava":12,"items":[{"lat":0,"graha":"Gulika","speed":0,"lon":197.6443465449266},{"lat":0,"graha":"Maandi","speed":0,"lon":208.77367195650632}]},{"rashi":4,"bhava":9,"items":[{"lat":0,"graha":"Mrityu","speed":0,"lon":116.26604630925816}]},{"items":[],"bhava":8,"rashi":3},{"items":[{"lat":0,"graha":"Indrachap","speed":0,"lon":143.96165951451349},{"lat":0,"graha":"Arthaprahaara","speed":0,"lon":139.3101884680955}],"bhava":10,"rashi":5},{"items":[{"lat":0.00010612850440115406,"graha":"Surya","speed":1.0192694458996876,"lon":262.70500715215314},{"lat":0.4078008654290313,"graha":"Shukra","speed":1.2531512791604653,"lon":243.72824229382888},{"lat":0,"graha":"Kaala","speed":0,"lon":252.44178289469193}],"bhava":2,"rashi":9},{"rashi":2,"bhava":7,"items":[{"lat":-0,"graha":"Rahu","speed":0.01025546940981247,"lon":55.51246896587352},{"lat":0,"graha":"Dhuma","speed":0,"lon":36.038340485486515}]},{"items":[{"lat":0,"graha":"Lagna","speed":0,"lon":231.27899193880532},{"lat":-0,"graha":"Ketu","speed":0.01025546940981247,"lon":235.51246896587352},{"lat":0,"graha":"Indrachap","speed":0,"lon":216.03834048548651},{"lat":0,"graha":"Upaketu","speed":0,"lon":232.70500715215317}],"bhava":1,"rashi":8},{"items":[{"lat":-1.078656325540108,"graha":"Varuna","speed":0.02145356435613993,"lon":324.44649233589536},{"lat":0,"graha":"Vyatipata","speed":0,"lon":323.9616595145135}],"bhava":4,"rashi":11},{"items":[],"bhava":5,"rashi":12}],"d9":[{"items":[],"bhava":9,"rashi":5},{"rashi":6,"bhava":10,"items":[{"lat":0,"graha":"Kuja","speed":0,"lon":150}]},{"items":[{"lat":0,"graha":"Bhuda","speed":0,"lon":300},{"lat":0,"graha":"Shani","speed":0,"lon":300}],"bhava":3,"rashi":11},{"items":[],"bhava":5,"rashi":1},{"items":[{"lat":0,"graha":"Lagna","speed":0,"lon":240},{"lat":0,"graha":"Ketu","speed":0,"lon":240},{"lat":0,"graha":"Yama","speed":0,"lon":240}],"bhava":1,"rashi":9},{"items":[{"lat":0,"graha":"Chandra","speed":0,"lon":180}],"bhava":11,"rashi":7},{"items":[{"lat":0,"graha":"Surya","speed":0,"lon":60},{"lat":0,"graha":"Guru","speed":0,"lon":60},{"lat":0,"graha":"Rahu","speed":0,"lon":60}],"bhava":7,"rashi":3},{"rashi":8,"bhava":12,"items":[]},{"rashi":10,"bhava":2,"items":[]},{"items":[{"lat":0,"graha":"Shukra","speed":0,"lon":330},{"lat":0,"graha":"Varuna","speed":0,"lon":330}],"bhava":4,"rashi":12},{"rashi":4,"bhava":8,"items":[{"lat":0,"graha":"Aruna","speed":0,"lon":90}]},{"rashi":2,"bhava":6,"items":[]}],"d1":[{"rashi":5,"bhava":3,"items":[{"lat":1.2582237930331537,"graha":"Kuja","speed":0.6255857078882127,"lon":137.89938343647293},{"lat":0,"graha":"Indrachap","speed":0,"lon":122.24505321908532},{"lat":0,"graha":"Upaketu","speed":0,"lon":138.91171988575198}]},{"rashi":4,"bhava":2,"items":[{"lat":0,"graha":"Gulika","speed":0,"lon":103.05660101571775},{"lat":0,"graha":"Maandi","speed":0,"lon":113.65585929141459}]},{"rashi":8,"bhava":6,"items":[{"lat":10.564854349293293,"graha":"Yama","speed":0.024020035442885546,"lon":226.85698648889277},{"lat":0,"graha":"Indrachap","speed":0,"lon":237.75494678091468}]},{"items":[{"lat":0.45748474703807784,"graha":"Chandra","speed":11.805163169899942,"lon":261.849880524307},{"lat":-0,"graha":"Ketu","speed":0.0011579753913891913,"lon":267.0249178245761}],"bhava":7,"rashi":9},{"items":[{"lat":0,"graha":"Dhuma","speed":0,"lon":302.2450532190853}],"bhava":9,"rashi":11},{"rashi":3,"bhava":1,"items":[{"lat":0,"graha":"Lagna","speed":0,"lon":67.68809566267458},{"lat":-0,"graha":"Rahu","speed":0.0011579753913891913,"lon":87.0249178245761},{"lat":0,"graha":"Yamaghantaka","speed":0,"lon":71.9604351027299}]},{"rashi":6,"bhava":4,"items":[{"lat":5.9642489288177245e-05,"graha":"Surya","speed":0.9859057860219527,"lon":168.911719885752},{"lat":0,"graha":"Kaala","speed":0,"lon":157.95081515717484}]},{"rashi":10,"bhava":8,"items":[{"lat":-0.7238888892404485,"graha":"Aruna","speed":-0.01687060248401704,"lon":293.21158674221806},{"lat":0.19359670014886066,"graha":"Varuna","speed":-0.005435742719545411,"lon":279.9540531461504}]},{"items":[],"bhava":10,"rashi":12},{"items":[{"lat":0,"graha":"Mrityu","speed":0,"lon":27.749962671154037}],"bhava":11,"rashi":1},{"items":[{"lat":-0.9336213188601504,"graha":"Guru","speed":-0.020864487285974623,"lon":47.307181440156555},{"lat":-2.278533391989706,"graha":"Shani","speed":-0.040574903554696166,"lon":36.63584831100912},{"lat":0,"graha":"Vyatipata","speed":0,"lon":57.75494678091468},{"lat":0,"graha":"Arthaprahaara","speed":0,"lon":50.710638576984834}],"bhava":12,"rashi":2},{"items":[{"lat":-2.8146296114064153,"graha":"Bhuda","speed":1.0076001210952052,"lon":194.26959087388872},{"lat":-0.36002035496444607,"graha":"Shukra","speed":1.2191444047682305,"lon":199.67175777202382}],"bhava":5,"rashi":7}],"d2":[{"items":[],"bhava":11,"rashi":3},{"items":[],"bhava":10,"rashi":2},{"rashi":5,"bhava":1,"items":[{"lat":0,"graha":"Lagna","speed":0,"lon":120},{"lat":0,"graha":"Surya","speed":0,"lon":120},{"lat":0,"graha":"Bhuda","speed":0,"lon":120},{"lat":0,"graha":"Guru","speed":0,"lon":120},{"lat":0,"graha":"Aruna","speed":0,"lon":120},{"lat":0,"graha":"Yama","speed":0,"lon":120},{"lat":0,"graha":"Dhuma","speed":0,"lon":120},{"lat":0,"graha":"Vyatipata","speed":0,"lon":120},{"lat":0,"graha":"Indrachap","speed":0,"lon":120},{"lat":0,"graha":"Indrachap","speed":0,"lon":120},{"lat":0,"graha":"Maandi","speed":0,"lon":120},{"lat":0,"graha":"Arthaprahaara","speed":0,"lon":120},{"lat":0,"graha":"Yamaghantaka","speed":0,"lon":120}]},{"rashi":4,"bhava":12,"items":[{"lat":0,"graha":"Chandra","speed":0,"lon":90},{"lat":0,"graha":"Kuja","speed":0,"lon":90},{"lat":0,"graha":"Shukra","speed":0,"lon":90},{"lat":0,"graha":"Shani","speed":0,"lon":90},{"lat":0,"graha":"Rahu","speed":0,"lon":90},{"lat":0,"graha":"Ketu","speed":0,"lon":90},{"lat":0,"graha":"Varuna","speed":0,"lon":90},{"lat":0,"graha":"Upaketu","speed":0,"lon":90},{"lat":0,"graha":"Gulika","speed":0,"lon":90},{"lat":0,"graha":"Kaala","speed":0,"lon":90},{"lat":0,"graha":"Mrityu","speed":0,"lon":90}]},{"items":[],"bhava":4,"rashi":8},{"rashi":10,"bhava":6,"items":[]},{"rashi":1,"bhava":9,"items":[]},{"items":[],"bhava":8,"rashi":12},{"rashi":11,"bhava":7,"items":[]},{"items":[],"bhava":5,"rashi":9},{"rashi":7,"bhava":3,"items":[]},{"rashi":6,"bhava":2,"items":[]}]}}`

 
* **Error Response:**

  <_Most endpoints will have many ways they can fail. From unauthorized access, to wrongful parameters etc. All of those should be liste d here. It might seem repetitive, but it helps prevent assumptions from being made where they should be._>

  * **Code:** 4XX - Software Error - UNPROCESSABLE ENTRY
  

  OR

  * **Code:** 5XX Server Down <br />

* **Sample Call:**

https://secure.ahoratra.app/horodata/v2?lat=13.5503&lon=78.50288&alt=0.0&offset=19800&day=05&month=10&year=2000&hours=23&minutes=0&seconds=0
