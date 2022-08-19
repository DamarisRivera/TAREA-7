# TAREA-7

#### UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE
##### CIRCUITOS ELÉCTRICOS
##### NOMBRE: Damaris Rivera.
##### NRC: 7318                                                                                                                  
##### FECHA: 08 – 17 – 2022

## 1. Objetivos 
  
### 1.1 Objetivo General
        
Analizar y resolver problemas utilizando los conocimientos de los capítulos respectivos a la corriente y voltaje de forma alterna y como funcionan los inductores y transformadores, usando la teoría para la correcta aplicación de los temas en los ejercicios prácticos.
	
### 1.2 Objetivos Específicos
        
- Desarrollar mapas mentales donde se explique los conceptos básicos de cada capítulo.
- Resolver los problemas planteados dentro de cada capítulo.
- Comprender como aplicar los conceptos dentro de los ejercicios prácticos.
	
## 2. Marco Teórico

#### CAPITULO 13 

![image](https://user-images.githubusercontent.com/105671763/185533143-8a469979-565e-4ad8-bfc4-cad1f44454b1.png)
![image](https://user-images.githubusercontent.com/105671763/185533185-1feebbc1-d204-447a-ac5a-7f264a9db0be.png)
![image](https://user-images.githubusercontent.com/105671763/185533209-13ae7849-5bf7-44e8-a195-be22cf50a962.png)

#### CAPITULO 14 

![image](https://user-images.githubusercontent.com/105671763/185537607-fa840cb6-0e1f-440c-a9d5-555fded155c8.png)
![image](https://user-images.githubusercontent.com/105671763/185537630-71c0c903-5bc8-40f6-8e53-baa4ecdbb54d.png)
![image](https://user-images.githubusercontent.com/105671763/185537652-0d598d11-c5aa-41f5-af5b-443a2dd93027.png)
![image](https://user-images.githubusercontent.com/105671763/185537681-7c852b83-2a38-402e-9922-3dff635eb2c6.png)
![image](https://user-images.githubusercontent.com/105671763/185537706-c2ed2aad-fa50-4fe5-be2e-ab8c76fcdec7.png)
![image](https://user-images.githubusercontent.com/105671763/185537724-9e4aa58d-f7af-431c-82ca-6605ada9e1a9.png)

## 3. Explicación y resolución de ejercicios 

#### CAPITULO 13

#### PROBLEMAS 

##### *SECCIÓN 13-1 	 El inductor básico*
	
##### 2. Convierta los siguientes valores en microhenries:

	(a) 300 mH
	    300000 𝜇H
	(b) 0.08 H
	    80000 𝜇H
	(c) 5 mH
	    5000 𝜇H
	(d) 0.00045 mH
	    0.45 𝜇H

##### 4. Se inducen 50 volts en una bobina de 25 mH. ¿Con qué rapidez cambia la corriente?

	Vind = L(di/dt)
	di/dt = Vind/L
	di/dt = 50/0.025
	di/dt = 2.000 A/s

##### 6. ¿Cuántas vueltas se requieren para producir 30 mH con una bobina enrollada sobre un núcleo cilíndrico cuya área de sección transversal mide 10 x 10^-5 m^2 y tiene longitud de 0.05 m? La permeabilidad del núcleo es de 1.2 x 10^-6 H/m. 

	L = (N^2*𝜇A)/I
	N^2 = (0.030*0.05)/[(10 x 10^-5)(1.2 x 10^-6)] 
	N^2 = 12500000
	N = 3535.6 

##### 8. Compare la inductancia de dos inductores idénticos excepto que el inductor 2 tiene dos veces la cantidad de vueltas del inductor 1.

	Como el inductor dos duplicará la cantidad de vueltas que el primer inductor, se concluye que el inductor 2 será mayor al inductor 1.

##### 10. Un estudiante enrolla 100 vueltas de alambre sobre un lápiz de 7 mm de diámetro como se muestra en la figura 13-43. El lápiz es un núcleo no magnético de tal suerte que su permeabilidad es igual a la de un vacío (4𝜋 x 10^-6 H/m). Determine la inductancia de la bobina que se formó.

![image](https://user-images.githubusercontent.com/105671763/185483413-a708615d-1152-481b-b132-a43e7fbc976e.png)

	A = 𝜋*r^2 = 𝜋*(0.0035)^2 
	A = 0.00003
	
	L = (N^2*𝜇A)/I
	L = [100^2*(4𝜋 x 10^-6)*(0.00003)]/[0.035]
	L = 0.10 mH

##### *SECCIÓN 13-3 	Inductores en serie y en paralelo*

##### 12. Usted requiere una inductancia total de 50 mH. Tiene disponibles una bobina de 10 mH y otra de 22 mH. ¿Cuánta inductancia adicional necesita?

	Lx = LT - Lb1 - Lb2
	Lx = 50 mH - 10 mH - 22 mH
	Lx = 18 mH

##### 14. En la figura 13-45, ¿cuál es la inductancia total entre los puntos A y B con cada posición del interruptor?

![image](https://user-images.githubusercontent.com/105671763/185483711-f2936006-4d7e-416a-8f3d-59b10ce90ce8.png)

	1.5 mH = 1500 𝜇H

	Posición 1
	IT = L1 + L2 + L4
	IT = 330 + 680 + 800
	IT = 1810 𝜇H
	
	Posición 2
	IT = L2 + L4
	IT = 680 + 800
	IT = 1480 𝜇H
	
	Posición 3
	
	IT = L4
	IT = 800 𝜇H
	
	Posición 4
	IT = 1500 + 800
	IT = 2300 𝜇H
	
##### 16. Usted tiene un inductor de 12 mH, y éste es su valor más bajo, pero necesita una inductancia de 8 mH. ¿Qué valor puede utilizar en paralelo con el inductor de 12 mH para obtener 8 mH?

	8 mH = 12L/(L + 12)
	8L + 96 = 12L
	L = 96/4
	L = 24 mH

##### 18. Determine la inductancia total de cada circuito mostrado en la figura 13-47.

![image](https://user-images.githubusercontent.com/105671763/185483879-ce72c875-6ea0-4a79-bef5-307eab7270cf.png)

	(a) LT = [(100*50)/(150)] + [(60*40)/(100)] 
	    LT = 172/3
	    LT = 57.33 mH

	(b) LT = (12*6)/(12+6)
	    LT = 4 mH
	
	(c) LT = (4*2)/(4+2) + 4
	    LT = 5.33 mH

##### *SECCIÓN 13-4 	 Inductores en circuitos de cd*

##### 20. En un circuito RL en serie, determine cuánto tiempo se lleva la corriente para incrementarse a su valor total con cada una de las siguientes combinaciones:

	(a) R = 56 𝛺, L = 50 𝜇H
	(b) R = 3300 𝛺, L = 15 mH
	(c) R = 22 K𝛺, L = 100 mH

##### 22. Para el inductor ideal de la figura 13-49, calcule la corriente en cada uno de los siguientes instantes:

![image](https://user-images.githubusercontent.com/105671763/185484699-b236115a-20c9-4968-a90e-de0d5ad62109.png)

	(a) 10 𝜇s
	(b) 20 𝜇s
	(c) 30 𝜇s

##### 24. Repita el problema 22 para los siguientes instantes:

	(a) 65 𝜇s
	(b) 75 𝜇s
	(c) 85 𝜇s

##### 26. 
	(a) ¿Cuál es la polaridad del voltaje inducido en el inductor de la figura 13-49 cuando la onda cuadrada está creciendo?
![image](https://user-images.githubusercontent.com/105671763/185484699-b236115a-20c9-4968-a90e-de0d5ad62109.png)

	(b) ¿Cuál es la corriente justo antes de que la onda cuadrada se reduzca a cero?

##### 28.
	(a) ¿Cuál es la corriente en el inductor 1.0 𝜇s después de que se cierra el interruptor en la figura 13-50?
![image](https://user-images.githubusercontent.com/105671763/185485303-1cbd5b35-5353-4421-a4e1-5b96e71c2f8f.png)
	
	(b)  ¿Cuál es la corriente después de que transcurren 5𝑇?

##### *SECCIÓN 13-5 	  Inductores en circuitos de ca*

##### 30. Determine la resistencia total para cada circuito de la figura 13-46 cuando se aplica voltaje a una frecuencia de 5 kHz entre las terminales.

![image](https://user-images.githubusercontent.com/105671763/185485479-f47cc9d3-eb4b-4144-8e9d-0d4588ecdbea.png)

##### 32. En la figura 13-51, determine la corriente rms total. ¿Cuáles son las corrientes a través de L2 y L3?

![image](https://user-images.githubusercontent.com/105671763/185485625-baf5b318-89ac-49e1-adde-6bb03af36f72.png)

##### 34. En la figura 13-51, determine la potencia reactiva.

![image](https://user-images.githubusercontent.com/105671763/185485625-baf5b318-89ac-49e1-adde-6bb03af36f72.png)

#### CAPITULO 14

#### PROBLEMAS 

##### *SECCIÓN 14-1 	   Inductancia mutua*

##### 2. Determine el coeficiente de acoplamiento cuando LM = 1 𝜇H, L1 = 8 𝜇H, y L2 = 2 𝜇H.

##### *SECCIÓN 14-2 	  El transformador básico*

##### 4. Cierto transformador tiene 250 vueltas en su devanado primario. Para duplicar el voltaje, ¿cuántas vueltas debe haber en el devanado secundario?

##### *SECCIÓN 14-3 	   Transformadores elevadores y reductores*

##### 6. Para elevar 240 V de ca a 720 V, ¿cuál debe ser la relación de vueltas?

##### 8. ¿Cuántos volts primarios se deben aplicar a un transformador que tiene relación de vueltas de 10 para obtener un voltaje secundario de 60 V de ca?

##### 10. El devanado primario de un transformador tiene 1200 V a través de él. ¿Cuál es el voltaje secundario si la relación de vueltas es de 0.2?

##### 12. ¿Cuál es el voltaje a través de la carga en cada uno de los circuitos de la figura 14-43?

![image](https://user-images.githubusercontent.com/105671763/185486430-31b500c0-0106-4ade-892f-be0d82f12087.png)

##### *SECCIÓN 14-4 	   Carga del devanado secundario*

##### 14. Determine Is en la figura 14-45. ¿Cuál es el valor de RL?

![image](https://user-images.githubusercontent.com/105671763/185486587-0ad8901a-77a2-436a-a656-91f927f2eb65.png)

##### *SECCIÓN 14-5 	   Carga reflejada*

##### 16. ¿Cuál es la resistencia en la carga vista por la fuente en la figura 14-47?

![image](https://user-images.githubusercontent.com/105671763/185486840-991b34b1-8947-4248-b92f-3a15fcc07c6c.png)

##### *SECCIÓN 14-6 	    Igualación de impedancia*

##### 18. En el circuito de la figura 14-49, encuentre la relación de vueltas requerida para suministrar potencia máxima al altavoz de 4 𝛺.

![image](https://user-images.githubusercontent.com/105671763/185487025-f7e9090c-5136-4262-ac82-d08b73e07c9b.png)

##### 20. Encuentre la relación de vueltas apropiada en cada una de las posiciones mostradas en la figura 14-50 para transferir potencia máxima a cada carga cuando la resistencia de fuente es de 10 Æ. Especifique el número de vueltas requerido para el devanado secundario si el devanado primario tiene 1000 vueltas.

![image](https://user-images.githubusercontent.com/105671763/185487108-5b036c91-1def-42b0-b396-6601056670b7.png)

##### *SECCIÓN 14-7 	   Características de un transformador no ideal*

##### 22. ¿Cuál es la eficiencia del transformador en el problema 21?

##### 24. La potencia nominal de cierto transformador es de 1 kVA. El transformador opera a 60 Hz y 120 V de ca. El voltaje secundario es de 600 V. 

	(a) ¿Cuál es la corriente máxima en la carga?
	(b) ¿Cuál es el valor RL más pequeño que puede ser excitado?
	(c) ¿Cuál es el capacitor más grande que se puede conectar como carga?

##### 26. La potencia nominal de cierto transformador es de 5 kVA, 2400/120 V, a 60 Hz. 

	(a) ¿Cuál es la relación de vueltas si los 120 V son el voltaje secundario?
	(b) ¿Cuál es la corriente nominal del secundario si los 2400 V son el voltaje primario?
	(c) ¿Cuál es la corriente nominal del devanado primario si los 2400 V son el voltaje primario?

##### *SECCIÓN 14-8 	   Transformadores con tomas y devanados múltiples*

##### 28. Con los voltajes indicados en la figura 14-52, determine la relación de vueltas de cada sección de toma del devanado secundario al devanado primario.

![image](https://user-images.githubusercontent.com/105671763/185487753-53eb6e28-49e6-4413-95be-2a64ab3103eb.png)

##### 30. En la figura 14-54, cada primario puede acomodar 120 V de ca. ¿Cómo se deberán conectar los primarios para que operen con 240 V de ca? Determine cada voltaje secundario para operación con 240 V

![image](https://user-images.githubusercontent.com/105671763/185487863-2f823486-b84d-42ce-8b02-272b228a0a24.png)

##### *SECCIÓN 14-9 	    Localización de fallas*

##### 32. Cuando se aplican 120 V de ca a través del devanado primario de un transformador y se verifica el voltaje en el devanado secundario, se leen 0 V. Una investigación más a fondo muestra que no hay corriente en el primario ni en el secundario. Enumere las posibles fallas. ¿Cuál es el siguiente paso en la investigación del problema?

##### 34. Mientras usted revisa un transformador, se da cuenta que el voltaje secundario es menor de lo que debería ser aunque no es de cero. ¿Cuál es la falla más probable?

## 4. Video



## 5. Conclusiones

- Los inductores o bobinas al interactura entre si crean un campo electromagnético, las líneas de fuerza localizadas alrededor de espiras adjuntas y forman un fuerte campo electromagnético adentro y en torno de la bobina. 
- Los transformadores se basan en el principio de la inductancia mutua, es decir, cuando dos bobinas o  más se encuentran cerca una de otra.

## 6. Bibliografía

Floyd, Thomas. 2007. Principios de circuitos eléctricos. Octava edición.
