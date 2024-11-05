(ENG)   A Constant Current (CC), and Constant Voltage (CV) converter can come in very handy in various conditions, for example, if you want to charge a lithium battery with a constant current you can do that very easily with this module. Furthermore, if we are testing a circuit and powering it for the first time it's always recommended to use a constant current that will limit damage to your circuit if you made any mistakes in the build process.I have two 10K potentiometers that are used to set the constant current and voltage level. Furthermore, there are three LED indicators on the board; the first one near the input connector shows when the module is in constant current mode, while the other two near the output are mainly for battery charging applications (battery charging and battery full indicators). Other than that, this IC has an input voltage range of 8V to 36V, and the output voltage of the device is 1.25V to 32V.   With max load, the PWM of the device can reach 100% duty cycle and it can operate on a 180 kHz operating frequency.

(DEU)   Ein Konstantstrom (CC)- und Konstantspannungs (CV)-Wandler können in verschiedenen Situationen äußerst nützlich sein. Wenn Sie beispielsweise eine Lithiumbatterie mit einem konstanten Strom laden möchten, können Sie dies mit diesem Modul sehr einfach tun. Darüber hinaus wird empfohlen, bei der ersten Inbetriebnahme einer Schaltung immer einen konstanten Strom zu verwenden, um Schäden an Ihrer Schaltung zu begrenzen, falls Sie während des Aufbauprozesses Fehler gemacht haben.Ich habe zwei 10K-Potentiometer, die verwendet werden, um den konstanten Strom- und Spannungspegel einzustellen. Darüber hinaus gibt es drei LED-Anzeigen auf der Platine; die erste in der Nähe des Eingangsanschlusses zeigt an, wenn das Modul im Konstantstrommodus ist, während die anderen beiden in der Nähe des Ausgangs hauptsächlich für Batterieladeanwendungen sind (Batterielade- und Batterievollanzeige). Abgesehen davon hat dieser IC einen Eingangsspannungsbereich von 8V bis 36V, und die Ausgangsspannung des Geräts beträgt 1,25V bis 32V. Bei maximaler Belastung kann das PWM des Geräts eine Tastverhältnis von 100% erreichen und es kann bei einer Betriebsfrequenz von 180 kHz arbeiten. Der konstante Ausgangsstrom des Moduls beträgt 5A und es kann bis zu 96% Effizienz erreichen, während es arbeitet. Wenn wir über Schutzfunktionen sprechen, verfügt es über thermischen Überlastschutz, Kurzschlussschutz und Funktion zur Strombegrenzung.Das Hauptkomponente auf dieser Platine ist der XL4015-Buck-Wandler-IC, ein 5-poliger IC, der entworfen wurde.Wenn wir über Schutzfunktionen sprechen, verfügt es über thermischen Überlastschutz, Kurzschlussschutz und Funktion zur Strombegrenzung. Die Hauptkomponente auf dieser Platine ist der XL4015-Buck-Wandler-IC, ein 5-poliger IC, der entworfen wurde. Im Schaltbild haben wir einen 78L05-Spannungsregler, der ein ultra-niedriger Leistungsregler ist, der verwendet wird, um die Eingangsspannung auf konstante 5V für den TL431-IC umzuwandeln. Der TL431 ist eine Referenz, die mit Hilfe eines 71,5K-Widerstands und eines Potentiometers auf den konstanten Stromreglermodus eingestellt ist. Diese Referenz wird mit der Sensorspannung von der Ausgangsseite des Widerstands verglichen, um den Strom zu begrenzen.  Die Schaltung unten ist die TL431-Schaltung, die eine konstante Stromquelle für die Operationsverstärker bereitstellt. Wenn die Batterie vollständig aufgeladen ist, wird der Ausgang niedrig, sodass die Lade-LED aufleuchtet. Wenn eine Batterie geladen wird, leuchtet die andere LED auf, um anzuzeigen, dass die Batterie geladen wird. Um den Test zu beginnen, habe ich zunächst das Buck-Wandler-Modul an die Stromversorgung angeschlossen und den Ausgang an die Gleichstromlast angeschlossen. Dann habe ich eine konstante Last von 1A eingestellt, um die Schaltung zu testen.


