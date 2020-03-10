# midimixvoicemeeter
AKAI midimix voicemeeter's macro button settings

<h3>Example Mute 1 (far left)</h3>

<strong>Button Type:</br></strong>
2 Positions</br></br>
<strong>Request For initial State:</br></strong>
Strip[0].Mute=0;</br>
System.SendMidi("out1","data","90,01,00");</br></br>
<strong>Request For Button ON:</br></strong>
Strip[0].Mute=1;</br>
System.SendMidi("out1","data","90,01,7F");</br></br>
<strong>Request For Button OFF:</br></strong>
Strip[0].Mute=0;</br>
System.SendMidi("out1","data","90,01,00");</br></br>
