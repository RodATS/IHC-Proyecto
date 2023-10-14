# IHC-Proyecto

<h1>Integrantes</h1>
<li>Joaquin Casusol</li>
<li>Paolo Delgado</li>
<li>Rodrigo Torres</li>

<h3>Proyecto de Terapia Física para el hombro usando RA</h3>

En el ámbito de la terapia física, la convergencia de tecnologías ha dado lugar a una innovación bastante interesante. La Asistente de Terapia Física con Realidad Aumentada es una aplicación revolucionaria que combina el potencial del Magic Leap v1 y el Kinect para ofrecer a los pacientes una experiencia de rehabilitación única.

Esta aplicación está diseñada para permitir a los pacientes llevar a cabo ejercicios terapéuticos en un entorno de realidad aumentada. La tecnología de Magic Leap v1 superpone elementos virtuales a su entorno real, creando un espacio de interacción completamente nuevo. Mientras tanto, el Kinect, con su capacidad de seguimiento de movimientos de alta precisión, monitorea y analiza cada movimiento del paciente, proporcionando retroalimentación instantánea y personalizada.

Entonces, si bien en el mundo real ya existe un proceso de terapia física como tal, nosotros buscamos llevarlo al siguiente nivel, utilizando las últimas tecnologías para hacer que un proceso de terapia sea mucho más cómodo y más efectivo. 

En este trabajo, explicaremos en detalle esta innovadora solución terapéutica, describiendo su funcionalidad, ventajas y el impacto potencial en la atención médica y la calidad de vida de los pacientes. Además, se analizarán los aspectos técnicos, los desafíos y las perspectivas a futuro de la Asistente de Terapia Física con Realidad Aumentada, subrayando su capacidad para revolucionar la rehabilitación física y mejorar el proceso de recuperación de pacientes en todo el mundo.

<h2>Installing the Unity Editor</h2>
1. Go to the Unity Download page, select Download Unity Hub, and install it.  
2. Open the Hub and navigate to the Installs tab and click Add.  
3. Now you can create a new Unity Project with Lumin support.  
4. Open Unity Hub and click the Installs tab.  
5. Click the three dots next to your target Unity version and click Add Modules.  

<h2>Install Magic Leap Tools & SDK</h2>
1. Go to https://ml1-developer.magicleap.com/downloads in your web browser and sign in with your Magic Leap ID.  
2. In the right-hand section of the Magic Leap Lab page, select Download for Windows or Download for Mac. This will download The Lab application onto the computer.  
  
<h2>Installing Lumin SDK Packages</h2>
1. Open The Lab. Initially, you will be required to login using your Magic Leap ID. Enter the 6-digit secret code that is sent to you by email.  
2. Navigate to the Package Manager  
3. Select Unity.  
4. In the right-hand pane, select Zero Iteration. This package allows you to simulate the device on your computer.  
5. Click Apply Changes and wait for the install to complete.  

<h2>Set the Lumin SDK inside Unity</h2>
1. Open or create a new Unity Project.  
2. From the menu, go to Edit > Preferences > External Tools.  
3. Assign the Lumin SDK path to the target Lumin SDK version.  
Mac: $HOME/MagicLeap/mlsdk/v0.26.0/ Windows: %USERPROFILE%/MagicLeap/mlsdk/v0.26.0/  

<h2>Version Compatibility</h2>

| Lumin OS | Lumin SDK | Unity    | Unreal   | API Level |
|----------|-----------|----------|----------|-----------|
| 0.98.30  | 0.26.0    | 2020.3   | 4.24.2   | 10        |
| 0.98.20  | 0.25.0    | 2020.2   | 4.24.2   | 9         |
| 0.98.10  | 0.24.0    | 2019.3   | 4.24.2   | 8         |
| 0.98     | 0.23.0    | 2019.2   | 4.23     | 7         |
| 0.97     | 0.22.0    | 2019.2   | 4.22.2   | 6         |
| 0.96     | 0.21.0    | 2019.1   | 4.22     | 5         |
| 0.95     | 0.20.0    | 2019.1   | 4.21+    | 4         |
| 0.94.0   | 0.19.0    | 2018.1 MLTP 10 | 4.21+ | 3         |
| 0.93.0   | 0.18.0    | 2018.1 MLTP 9  | 4.20  | 2         |
| 0.92.0   | 0.17.0    | 2018.1 MLTP 8  | 4.20  | 1         |
| 0.91.0   | 0.16.0    | 2018.1 MLTP 7  | 4.20  | 1         |
