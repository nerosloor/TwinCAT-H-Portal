# TwinCAT-H-Portal

Beckhoff / TwinCAT 3 H-Portal interpolator

Der FB dient dazu den Schlitten eines H-Portals mit nur einem einizigen durchgängigen Riemen positionieren zu können.
Die Antriebe die verwendet werden, besitzen absolut-multi-turn Drehgeber. Eine Referenzierfahrt ist somit hinnfällig.
Besonders ist, dass ein abgegebener Fahrauftrag nicht zu ende gefahren werden muss. Es ist möglich einen aktuelleren
Fahrauftrag abzugeben und damit einen aktuellen Fahrauftrag abzulösen.


Benötigte Bibliotheken:
	-> Tc2_MC2
	
Benötigte FB´s:
	-> FB_ServoAchse

	
Benötigte Lizenzen:
	-> TF5000
