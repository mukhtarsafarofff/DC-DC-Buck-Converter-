This module is Constant Current(CC) and Constant Voltage(CV) converter and this  Constant Current (CC), and Constant Voltage (CV) converter can come in very handy in various conditions, for example, if we  want to charge a lithium battery with a constant current we can do that very easily with this module. If we are testing a circuit and powering it for the first time it's always recommended to use a constant current that will limit damage to your circuit if you made any mistakes in the build process.We have the DC input connector, which is to connect to an unregulated power source.We have two 10K potentiometers that are used to set the constant current and voltage level. There are three LED indicators on the board; the first one near the input connector shows when the module is in constant current mode, while the other two near the output are mainly for battery charging applications.The constant output current of the module is 5A and it can reach up to 96% efficiency while working.There TL431 is a reference that is set to a constant current regulator mode with the help of a 72K resistor and a potentiometer. This reference is compared to the sense voltage from the output side of the resistor to limit the current. The circuit shown below is the TL431 circuit that is providing a constant current source to the op-amps.We  have the first op-amp portion; this portion of the circuit is actually used to limit the current. What happens in this portion is that the output sense voltage gets compared with the reference voltage from the TL431 IC. Next what happens is that if the output sense voltage is greater than the reference voltage the output of the op-amp turns high and with the shutdown function of the circuit, the output of the IC turns off.

Dieses Modul ist ein Konverter für Konstantstrom (CC) und Konstantspannung (CV), und dieser Konverter für Konstantstrom (CC) und Konstantspannung (CV) kann unter verschiedenen Bedingungen sehr nützlich sein, beispielsweise wenn wir eine Lithiumbatterie laden möchten Mit einem konstanten Strom können wir das mit diesem Modul ganz einfach machen. Wenn wir einen Schaltkreis testen und ihn zum ersten Mal mit Strom versorgen, empfiehlt es sich immer, einen konstanten Strom zu verwenden, der Schäden an Ihrem Schaltkreis begrenzt, falls Sie beim Aufbau Fehler gemacht haben. Wir haben den DC-Eingangsanschluss, an den Sie ihn anschließen können eine ungeregelte Stromquelle. Wir verfügen über zwei 10K-Potentiometer, mit denen der konstante Strom- und Spannungspegel eingestellt wird. Auf der Platine befinden sich drei LED-Anzeigen; Die erste in der Nähe des Eingangsanschlusses zeigt an, wann sich das Modul im Konstantstrommodus befindet, während die anderen beiden in der Nähe des Ausgangs hauptsächlich für Batterieladeanwendungen vorgesehen sind. Der konstante Ausgangsstrom des Moduls beträgt 5 A und es kann dabei einen Wirkungsgrad von bis zu 96 % erreichen funktioniert. Es gibt TL431 eine Referenz, die mit Hilfe eines 72K-Widerstands und eines Potentiometers auf einen Konstantstromreglermodus eingestellt wird. Diese Referenz wird mit der Messspannung von der Ausgangsseite des Widerstands verglichen, um den Strom zu begrenzen. Die unten gezeigte Schaltung ist die TL431-Schaltung, die eine Konstantstromquelle für die Operationsverstärker bereitstellt. Wir haben den ersten Operationsverstärkerteil; Dieser Teil der Schaltung dient eigentlich der Strombegrenzung.
