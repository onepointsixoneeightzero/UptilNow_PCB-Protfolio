# PCB PORFOLIO
****

****
##### Embedded Hardware PCBs
> TM4C123 MAX UARTS RS232/ ANALOGS/ isolated IOs PCB
>>THE CIRCULAR PIN HOLE PATTERN IS ATTACHED TO EACH
> PIN OF THE MCU, FOR DEBUGGING AND FUTURE DEVELOPMENT
> PURPOSES
> <p> Objective was to get all available UARTS 
> and configure them as RS 232 using MAX 232. ANALOG
> Sensors Attachment was also demanded and maximum
> ports of Analog were installed (pulled down).
> More over, Isolated IO with mixed In, Outs and IOs
> requirement was also demanded and was catered
> by interfacing MAX14851.
> Power Supply Demand was customized and the circuit
> has to be designed according to customers need.


<figure>
    <img align="center" width="450" height="350" 
    src=".\TOP_pic\TM4C123x1_MAX232ex7_ANALOGx7_IsolatedinX_outX_ioX_POWERSUPPLYx2_top.png" title="NAbeel">
    <img align="right" width="450" height="350" 
    src=".\BOT_pic\TM4C123x1_MAX232ex7_ANALOGx7_IsolatedinX_outX_ioX_POWERSUPPLYx2_bottom.png">
    <figcaption align="center">Top and Bottom View of PCB</figcaption>
    </figure>

****
> TM4C123 Version 2 with switchable RS 232 and 422
>> THE CIRCULAR PIN HOLE PATTERN IS ATTACHED TO EACH
> PIN OF THE MCU, FOR DEBUGGING AND FUTURE DEVELOPMENT
> PURPOSES
> <p>Objective was similar as above, But with a
> major difference of installing DIP switch to serve
> purpose of switching between RS232 and RS422 protocols
> for this reason, the MAX232 IC was ditched and
> SP335e IC was used instead </p>

<figure>
    <img align="center" width="450" height="350"
src=".\TOP_pic\TM4C123x1_SP335ex7_ANALOGx7_IsolatedinX_outX_ioX_POWERSUPPLYx2_top.png">
    <img align="right" width="450" height="350"
src=".\BOT_pic\TM4C123x1_SP335ex7_ANALOGx7_IsolatedinX_outX_ioX_POWERSUPPLYx2_bottom.png">
    <figcaption align="center">Top and Bottom View of PCB</figcaption>
    </figure>

****
****

##### ANALOG AND DIGITAL COMPLEX PCBs
>> Analog IN - Digital SERIAL OUT
>- ANALOG Obj. Getting Data from and Analog Sensor with Multi pins
>- Digital Obj. Parsing that data and throwing it out as an 
> RS Protocol (SERIAL)

<figure>
    <img align="center" width="450" height="350"
src=".\TOP_pic\Synchro_To_nmea_AnalogCard_TOP.png">
    <img align="right" width="450" height="350"
src=".\TOP_pic\Synchro_To_nmea_DigitalCard_top.png">
    <figcaption align="center"><---ANALOG CARD----------DIGITAL CARD---></figcaption>
    </figure>

****
>>DIGITAL SERIAL IN - ANALOG OUT
>- Digital Obj. Getting Data from and Digital Sensor Serialy
>- ANALOG Obj. Converting that Data into Analog

<figure>
    <img align="center" width="450" height="350"
src=".\TOP_pic\NmeaToResolver_DigitalCard_top.png">
    <img align="right" width="450" height="350"
src=".\TOP_pic\NmeaToResolver_AnalogCard_TOP.png">
    <figcaption align="center"><---DIGITAL CARD----------ANALOG CARD---></figcaption>
    </figure>

****
****
##### Dimension-Critical PCB
>> BIG BOARD - CONNECTORS PRECISE PLACEMENT
>- The only objective here, apart from circuit, was that 
> the connector placement has to be perfect. 
>- In order to
> achieve that I had to 
>measure the real board with
> vernier caliper many times and Averaged the readings out
>to reduce human error

<figure>
<img align="center" width="501" height="401"
    src=".\TOP_pic\DimensionCriticalBoard_TOP.png">
    <img align="right" width="501" height="401"
    src=".\TOP_pic\DimensionCriticalBoard_2_TOP.png">
    <figcaption align="center">These PCB were quite big and Measurement consumed a lot of time</figcaption>
    </figure>


****
****
##### Misc PCBs
>> TIVA SHIELDS
>Here are some other PCBs which I made for TIVA Development
> board .
>- One is a simple empty board with no component.
>- Exact size and pin placement
>- Other is the same shield with RS 422 protocol chip pad
> installed

<figure>
    <img align="center" width="450" height="350"
    src=".\TOP_pic\TIVA_SHIELD_TOP.png">
    <img align="right" width="450" height="350"
    src=".\TOP_pic\RS422_TIVA_SHIELD_TOP.png">
    <figcaption align="center"><-- TIVA EMPTY SHIELD -------- TIVA RS422 SHIELD --></figcaption>
    </figure>

****
****
# ABOUT THE DESIGNER
>## MECHATRONICS ENGINEERING Masters
> with THESIS (NUST)
>### 3 Years Overall Professional Experience
>> 2.5 Years of PCB DESIGN EXPERIENCE
>>- Eagle
>>- Allegro
>>- Proteus
>>- Python Automation
>>>- All the Components were manually designed by referring to DATASHEET
>>>- Even the Smallest of capacitors and Resistors.
>>>- No component is Picked from Online Component Libraries or even from Eagle Library itself
>>>- Current Plan is to Automate Component Designs in EAGLE
>
>- Contact @ [linkedin](https://www,linkedin.com/in/nbl1330/)
****