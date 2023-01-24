# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:
### Step 1:
start a django project and create templates folder

### Step 2:
then write the code in html files and assign path and edit views

## Code:
```
#map.html
!DOCTYPE html>
<html>
    <head>
        <title>gce tirunelveli Image Map</title>
    </head>
    <body>
        <h1 align='center'> Map of government college of engineering  tirunelveli</h1>
        <h2<  align='left'>Address:</h2>
        <h3 align='left'>MPPG+C8J, Trivandrum Rd, Marshal Nager, Tirunelveli, Tamil Nadu 627007</h3>
        <img src = "/static/images/mapping.png" height="700" width="1500" align="center" usemap="#collegemap">
        <map name="collegemap">
            <area  alt="" title="eee deprtment" href="eee.html" shape="poly" coords="795,598,960,616,939,696,765,690" style="outline:none;" target="_self" />
            <area  alt="" title="cse department" href="cse.html" shape="poly" coords="585,55,616,105,718,108,727,38" style="outline:none;" target="_self"  />
            <area  alt="" title="ece department" href="ece.html" shape="poly" coords="90,40,61,106,276,114,255,53" style="outline:none;" target="_self"  />
            <area  alt="" title="library" href="lib.html" shape="poly" coords="888,18,916,102,1092,84,1073,3" style="outline:none;" target="_self"     />
            <area  alt="" title="Mechanical department" href="mech.html" shape="poly" coords="1018,153,956,253,1082,285,1145,172" style="outline:none;" target="_self"     />
        </map>
</body>
</html>
#cse.html:
<!DOCTYPE html>
<html>
	<head>
		<title>CSE department</title>
	</head>
	<body>
 <center><img src = "/static/images/cse.png" height="250" width="600" align="center"></center>c
 <h2 align="center">cse department</h2>
 <p>
We the Department of Computer Science and Engineering ever since 1984 strive to create an ambience of academic excellence in which new ideas, research and scholarship flourish and from which the leaders and innovators of tomorrow emerge 
 
Accredited by the National Board of Accrediation for a period of 2 years, the computer science and engineering is one of the most eminent programme in GCT. The four year under graduate programme in Computer Science is intended to train the students in both advanced areas in the core courses and specialized topics in the emerging technology. 
 
It has become the pool for research scholars with  inclusion of M.Phil and PhD courses in 1992. We have a team of highly qualified and dedicated teaching faculty well supported by a  group of Techincal support staff for keeping campus vibrant as a temple of knowledge under a self imposed discipline by one and all. 
 
Our future techies, scientists, executives, entrepreneurs are nurtured and encouraged with creative approach. It has excellent infrastructure and facilities for students. It is the endeavor of the management to periodically migrate to the latest software and hardware to keep pace with ever changing needs with the industries so that our students come out with latest knowledge in both software and hardware 
 
The necessary licensed software and internet facilities are available for all students round the clock. Besides imparting theoretical knowledge, the curriculum stresses on developing analytical stills, communication, problem solving, and teamwork abilities 
</p>
	</body>
</html>
#ece.html:
<!DOCTYPE html>
<html>
	<head>
		<title>ece department</title>
    </head>
    <center><img src = "/static/images/ece.png" height="250" width="600" align="center"></center>
    <h3 align="center">ECE department</h3>
	<body>
		<p> 
 
The Department was established in 1970 with B.E. programme in Electronics and Communication Engineering. Later on, in 1981 post graduate programme in M.E. Applied Electronics and in 2003 M.E. VLSI Design programme were also started in the Department. All the courses are offered as both part-time and full-time. 
 
The Department has total staff strength of 16 including Teaching and Non-Teaching staff. The experienced professors guide the Department aiming at educating and training students with sound knowledge and awareness in the fields of electronics, communication and information technology. 
 
The Department is recognized for research under Information and Communication Engineering affiliated to Anna University::Chennai. The Department has signed MoU with several companies like Texas Instruments, Robert Bosch which provide training to faculty and students on recent techniques.Various workshops and trainingprogrammeare frequently conducted in the Department. Every year Department organizes National conference on Advanced Computing and Communication Systems. A National level technical symposium ‘NEXUS’ is being conducted by ECE students association. 
</p>
	</body>
</html>
## lib.html:
<!DOCTYPE html>
<html>
	<head>
		<title>library</title>
    </head>
    <center><img src = "/static/images/lib.jpeg" height="300" width="600" align="center"></center>
	<body>
        <h3 align="center">Library</h3>
		<p>A library is a collection of materials, books or media that are accessible for use and not just for display purposes. A library provides physical (hard copies) or digital access (soft copies) materials, and may be a physical location or a virtual space, or both. A library's collection can include printed materials and other physical resources in many formats such as DVD, CD and cassette as well as access to information, music or other content held on bibliographic databases. 
 
A library, which may vary widely in size, may be organized for use and maintained by a public body such as a government; an institution such as a school or museum; a corporation; or a private individual. In addition to providing materials, libraries also provide the services of librarians who are trained and experts at finding, selecting, circulating and organizing information and at interpreting information needs, navigating and analyzing very large amounts of information with a variety of resources. 
 
Library buildings often provide quiet areas for studying, as well as common areas for group study and collaboration, and may provide public facilities for access to their electronic resources; for instance: computers and access to the Internet. The library's clientele and services offered vary depending on its type: users of a public library have different needs from those of a special library or academic library, for example. Libraries may also be community hubs, where programs are delivered and people engage in lifelong learning. Modern libraries extend their services beyond the physical walls of a building by providing material accessible by electronic means, including from home via the Internet. 
 
The services that libraries offer are variously described as library services, information services, or the combination "library and information services", although different institutions and sources define such terminology differently. </p>
	</body>
</html>
## mech.html
<!DOCTYPE html>
<html>
	<head>
		<title>mechanical department</title>
    </head>
    <center><img src = "/static/images/mech.png" height="250" width="600"></center>
    <h3 align="center">Mechanical department</h3>
	<body>
		<p>The Government College of Technology formerly named as Arthur Hope College of Technology, was established in July 1945 to provide valuable guide ship to the industrial sectors in variant field of manufacturing. In this reputed institution, the Department of Mechanical Engineering geared up in the academic year of 1952 with the Undergraduate Programme and in the year 1971 Engineering Design as a Post Graduate Programme continued by Manufacturing Engineering in the year 1980 and Thermal Engineering in the year 2002. The involvement and contribution of work force on teaching and learning process of both teaching and non-teaching staff enrich the Mechanical Department of as a pioneer one. Coimbatore is the Manchester of South India' having Foundries, Textile machinery manufacturing industries, Automobile spares manufacturing industries. Also it is runner to full-fill the need of globalized engineering requirements. To the industrial needs and to stabilise their logo in the field, man-potential with in-hands training knowledge in mechanical engineering is important. The department has been showing in-hands training knowledge to their mechanical discipliners with the aid of conventional and modernized technology systems. The department has achieved NBA with its academic records and supporting activities to the industries. The modern technology of CMM, CNC Machineries, Wire cut EDM, Advanced Thermal Measurement Techniques, Vibration Fundamental Trainer, 3D Printing and Advanced Casting Technologies have been included in the curriculum to build up the students as a handsome engineer to the modern technological fields. To elevate the discipliners as an entrepreneur in its specialization of field, the industrial environment training programmes passionate with the academic topics. Measurement on every carrier creates a novelty in their life style in the engineering environment.  
 
 
</p>
	</body>
</html>
##eee html:
<!DOCTYPE html>
<html>
	<head>
		<title>eee department</title>
	</head>
	<body>
         <center> <img src = "/static/images/eee.jpeg" align="center" height="300" width="800"></center>
        <h3 align=center>EEE department</h3>
		<p>  
            
The Department of Electrical and Electronics Engineering (EEE) is one of the two oldest departments of the institution spanning 75 years of existence which offers undergraduate programme B.E-EEE (and two post graduate programmes  Power Systems Engineering and Power Electronics and Drives) and research programme. The Department of Electrical Engineering is committed to excel in Electrical and Electronics Engineering through education and research with well-qualified and experienced faculty and technical staff members. Top ranked students in the state who secure 190 and above cut-off marks out of 200in higher secondary school examinations, are admitted in the institution through Tamilnadu Engineering Admission on-line counseling conducted every year by Directorate of Technical Education, Chennai. More than 60 scholars have completed Ph.D. and more than 30 are pursuing research. The department has established Centre of Excellence for Alternate Energy Research (CoE-AER) under Technical Education Quality Improvement Programme (TEQIP) phase – II with fund of Rs.5 crores and TEQIP phase – III with fund of Rs.1.5 crores.

The long term goal of CoE-AER is to develop a centre for research and development activities in the thrust areas of solar and wind energy. The main objectives are to provide a better solution for industrial problems and to carry out academic and sponsored research projects. The department is committed to provide exposure to students in state of the art technologies by signing Memorandum of Understanding (MoU) with reputed companies. An U.S patent on Dual axis solar tracking system driven by a low powered drivewas granted to the department under TEQIP-II - CoE-AER (Patent Number: US 10,340,841 B1 dated: 02.07.2019). The students exhibit their co-curricular and extra-curricular skills through the activities of EEE student association and institution of Electrical and Electronics Engineers (IEEE) students’ chapter.
          

  </p>
	</body>
</html>
```
## Output:
## map:
![Screenshot from 2023-01-24 22-15-44](https://user-images.githubusercontent.com/118660461/214363713-108f48f4-cfaf-479f-9e42-51e695d5a2e3.png)
## cse:
![Screenshot from 2023-01-24 22-15-53](https://user-images.githubusercontent.com/118660461/214363784-5f4f1f24-3730-4ae1-a649-fb8b4a561d60.png)
## ece :
![Screenshot from 2023-01-24 22-16-40](https://user-images.githubusercontent.com/118660461/214363837-1f3b29ed-282f-4caf-ac89-a95dce636774.png)
# library:
![Screenshot from 2023-01-24 22-16-10](https://user-images.githubusercontent.com/118660461/214363856-e9e112e7-40d3-4af0-ac9d-44a0abad4141.png)
## mechanical:
![Screenshot from 2023-01-24 22-16-50](https://user-images.githubusercontent.com/118660461/214363878-2fc92c62-3d6a-4614-86cb-b41151c7a514.png)
## eee:
![Screenshot from 2023-01-24 22-16-20](https://user-images.githubusercontent.com/118660461/214363891-66b67215-0123-4361-b68b-2d6a37c35db5.png)
## Result:
mapping program was executed successfully
