<html>
  <head>
    <h1>My Journey in Digital Fabrication & Prototyping Fundamentals (EP1000)</h1>
  </head>
<div style="background-image:url(https://user-images.githubusercontent.com/93360827/148720794-2918c04f-8146-49e7-9584-cc3333b509e0.jpg);
		background-attachment:fixed;">
  </div>
  <body>
    <h2>About Me</h2>
    <p>Hello! I am Goh Yi-Herng Keane currently studying in my 3rd year for a Diploma
  in Architecture in SP. Throughout my time in SP, we are given a chance each year to pick up
  an elective module where we can learn new skills that can potentially be useful in our future. 
  For my current Year 3 Elective Module, I have chosen Digital Fabrication (EP1000) as my elective module,
      and this webiste is a compilation of the fun things I've picked up in this module!</p>
    <p>This elective is organised around a self-directed project where students develop design thinking and prototyping skills. Students will be guided through a design thinking process followed by the development of a functional prototype. Students will apply design and digital fabrication process for developing a functional prototype that integrates these processes. Students will practise these skills in a design studio setting.</p>
  <p>Below are some of the places you can explore on my website!</p>
    <ul>
        <li><a href="https://github.com/Keanegoh1/keanegoh1.github.io/blob/main/README.md#my-blogs--documentations">My Weekly Tutorial Blogs & Documentations</a></li>
        <li><a href="Module Project.txt">Module Project Documentation</a></li>
    </ul>
    <h2>Make yourself comfortable!</h2>
    <img src="https://consumervaluecreation.files.wordpress.com/2018/03/html-rapid-prototyping-feature-image.jpg">
</body>
</html>
<html>
 <body>
    <h2>My Blogs & Documentations</h2>
    <h3>3D Printing</h3>
    <p>We learnt how to create a piece on the modelling software Autodesk Fusion360, by imposing the chosen image for the chess piece, and tracing the outline
   followed by extruding out the 2d piece to create the chess piece in a 3d form.</p>
   <img src="https://user-images.githubusercontent.com/93360827/148551094-ca5a077b-0c5e-4671-9893-c48fb7cb0d4f.jpeg" width=550>
    <p>After we extracted the form of the chess piece, we then load the chess piece file into Ultimaker Cura, the software that prepares the files for 3d printing, to ensure that the dimensions were correct, and to ensure that the pieces were able to be printed with sufficient support such that the piece does not collapse during printing.</p>
   <img src="https://user-images.githubusercontent.com/93360827/148551196-5110a5f5-6c29-41b1-8539-63508d63e81f.jpeg" width=500>
   <p> Once arranged well, we then print it!</p>
   <img src="https://user-images.githubusercontent.com/93360827/148549450-bb9295fc-eb7f-4315-bb32-ae08951f2d26.jpeg" width=300 height=500> <img src="https://user-images.githubusercontent.com/93360827/148549889-f6d17f9a-7830-4396-87d5-beb8bcf4fc81.jpeg" width=650 height=500> <img src="https://user-images.githubusercontent.com/93360827/148549942-d64b1c08-3771-40b2-affc-9be0b28ba964.jpeg" width=300 height=500>
<h3>Laser Cutting</h3>
   <p>Finishing the 3d Printing, we moved on to learn laser cutting, an important skill in producing pieces that helps to build up our prototype, again using Fusion360.</p>
   <img sr="https://user-images.githubusercontent.com/93360827/148562587-3ed476c7-f730-4ca9-8e7a-f537fbb2297e.jpeg" width=550>
    <p>The drawing is then saved as a DXF file, which we import it into CorelDraw that assists us in cutting and scoring it on the wooden board provided. I learn't that the each method, cutting and scoring, are identified by colour codes, red being cut, and green being score.</p>
   <img src="https://user-images.githubusercontent.com/93360827/148562827-cf606052-a7a5-4eaf-906a-5e496c7ca49a.jpeg" width=500>
   <img src="https://user-images.githubusercontent.com/93360827/148562926-b29dff91-ae8d-4176-bac4-290c7df29014.jpeg" width=500>
   <p>After cutting, all I needed to do is to assemble and I get my musical box...</p>
   <img src="https://user-images.githubusercontent.com/93360827/148563283-dad846e4-8007-41cf-a126-038f3ae2984e.jpeg" width=300><img src="https://user-images.githubusercontent.com/93360827/148563325-e255983c-d504-47f7-ad54-1e2769afd1d8.jpeg" width=300>
<h3>Arduino Uno</h3>
<p>I also got to learn Arduino Programming. The Arduino Uno is an open-source microcontroller board that is equipped with sets of digital and analog input/output pins that may be interfaced to various expansion boards and other circuits.</p> 
    	<img src="https://docs.arduino.cc/static/6ec5e4c2a6c0e9e46389d4f6dc924073/A000066-pinout.png">
<h3>Input and Output Devices</h3>
	 <p>An input device is connected to the Arduino Uno that is programmed through the Arduino Uno while an output device has information sent to it. The button in this case is used to operate the LED bulb</p>
	<img src="https://cdn.sparkfun.com//assets/parts/9/0/00097-03-L.jpg">
	 <p>Below shows an example of the LED bulb.</p>
	<img src="https://media.rs-online.com/t_large/F2285988-01.jpg">
<p>As a push button switch is a small and sealed mechanism that completes an electric circuit when you press on it, a resistor is needed to step-down the current to allow it to transmit through and alternate with the LED bulb. </p>
	 <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/75/Electronic-Axial-Lead-Resistors-Array.jpg/1200px-Electronic-Axial-Lead-Resistors-Array.jpg">
	 <p> With the items above, I used tinkerCAD to simulate the entire circuit with the simple coding given below, by alternating the current to allow the button to work simultaneously with the LED bulb such that when activated, the current flows through the alternate route through the LED bulb that lights it up. </p>
	 <img src="https://user-images.githubusercontent.com/93360827/155739881-8efc56df-e79f-454c-899a-0989e6f1e73a.jpeg">
<p>Arduino Coding</p>
<p>int buttonState = 0;

void setup()
{
  pinMode(2, INPUT);
  pinMode(13, OUTPUT);
}

void loop()
{
  buttonState = digitalRead(2);
  
  if(buttonState == HIGH) {
    digitalWrite(13, HIGH);
  } else {
    digitalWrite(13, LOW);
  }
  delay(10);
	}</p>
</body>
</html>

<html>
  <body>
   <h2>Module Project Documentation</h2>
    <p>For our module project, I have decided to design a Christmas tree designed Mood Lighting.</p>
	  <p>This project would require...</p>
	      <ul>
        <li>Arduino Uno</li>
        <li>Breadboard</li>
	<li>Neopixel Strip (4 Lights)</li>
	<li>Pushbutton</li>
  	<li>Jumper Pins</li>
    </ul>
<h3>Design Process</h3> 
	  <p> The software I have decided to use as part of my design phase was SketchUp, a modelling software.</p>
	  <p> Using SketchUp, I drafted a rough model of how the design would look like as shown below, by creating 2 parts, first the base board, then the second being the acrylic mood piece that holds the christmas tree design to it, which I will use a separate software to create.</p>
	  <img src="https://user-images.githubusercontent.com/93360827/153740879-b4373561-b5a8-4c88-b554-010117c90a8d.jpeg"><img src="https://user-images.githubusercontent.com/93360827/153740936-293a73eb-a493-4b02-bb3f-1ba783b83022.jpeg">  
	  <p> For the 2nd piece, I opted to use AutoCAD to generate the design of the Christmas Tree as well as export both the SketchUp Base pieces and Christmas Tree design to DXF files, preparing them for laser cutting.</p>
	  <img src="https://user-images.githubusercontent.com/93360827/153740966-8aed38d4-129e-4fb0-b6b1-053c17796743.jpeg"><img src="https://user-images.githubusercontent.com/93360827/153740982-a3019993-8c2a-4bd6-9034-6ba383c4d17d.jpeg"><img src="https://user-images.githubusercontent.com/93360827/153741001-3f8043c4-e5fc-4ae0-8528-aa467c758a0f.jpeg"><img src="https://user-images.githubusercontent.com/93360827/153741004-a2d30c00-dfd8-45dd-9849-4c50172e3c38.jpeg">
<h3>Arduino Programming</h3> 
	<p> Before carrying out the actual live programming, I used TinkerCAD to help simulate and test the entire coding experiment, as well as wiring as shown below.</p>
	  <img src="https://user-images.githubusercontent.com/93360827/153741110-ff98b045-b8b1-4187-8cb8-830919b73b25.jpeg">
	  <p> Making use of prior prepared basic coding for NeoPixel Strips, I added on to it different types of coding that helped to generate the outcome I wanted, for example,</p>
	  <img src="https://user-images.githubusercontent.com/93360827/153741154-f22ae483-f267-4b42-a129-0769569ccea4.jpeg">
	  <p> Adding multiple colour codes that changes on a click of the pushbutton, in total 6 different colours and a "Black/Blank" colour that acts as an "off" section.</p>
	  <img src="https://user-images.githubusercontent.com/93360827/153741189-7f51408d-7a67-498a-9799-59d46707f500.jpeg">
	  <p> This set of coding then loops the entire process back to allow for the colours to repeat themselves and can operate separately as long as theres a power supply connected to it. </p>
<h3>Assembly</h3> 
	  <p>Now that both the Model and the Programming works, it comes to the assembly part...</p>
	  <p>Assembling the Arduino Circuit and the Base box</p>
	  <img src="https://user-images.githubusercontent.com/93360827/153741253-36ac0aa4-ccf4-47c4-9455-f396da1b4480.jpeg"><img src="https://user-images.githubusercontent.com/93360827/153741266-9e1263e7-37e1-492d-b8f5-302fec0cc4ff.jpeg">
	  <p>Then creating a platform base for the NeoPixel strip to rest on to produce the light straight up to the Acrylic</p>
	  <img src="https://user-images.githubusercontent.com/93360827/153741307-85595602-7fc9-44c7-af67-9f37a0dc35ab.jpeg"><img src="https://user-images.githubusercontent.com/93360827/153741321-4f1dcd3f-43df-44fe-a319-a250a3794973.jpeg"><img src="https://user-images.githubusercontent.com/93360827/153741329-76afe2a3-3bb5-4766-b2a3-3f85ec0b457a.jpeg">
	  <p>The Final Product!</p>
		  <img src="https://user-images.githubusercontent.com/93360827/153741339-b9f04505-bfd2-498e-8e26-3b850d19c61d.jpeg">
	  <h3>Testing the Lights!</h3>
	  <p> Green Light </p>
<img src="https://user-images.githubusercontent.com/93360827/153741377-12acefbb-bbac-41d6-9814-c197f23b70a1.jpeg">
	   <p> Orange Light </p>
<img src="https://user-images.githubusercontent.com/93360827/153741378-33b62235-5e59-4180-a562-e3cf6dda708b.jpeg">
	   <p> Red Light </p>
<img src="https://user-images.githubusercontent.com/93360827/153741379-9b3861af-c069-4697-a780-bd0bb9fad5a3.jpeg">
	   <p> Blue Light </p>
<img src="https://user-images.githubusercontent.com/93360827/153741380-939e7c06-2cb3-4251-b0f4-b8c50d991b95.jpeg">
	   <p> Magenta Light </p>
<img src="https://user-images.githubusercontent.com/93360827/153741381-40aef31e-50dd-44dd-a6b7-c938e7f66959.jpeg">
	   <p> Yellow-White Light </p>
<img src="https://user-images.githubusercontent.com/93360827/153741382-fe62e342-6ec8-4d3e-8032-ce7f89f077e1.jpeg">

</body>
</html>
