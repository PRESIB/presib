Title: PRESIB - Helper post for Nuno Fernandes' dissertation
Date: 30/07/2020
Category: Blog
Tags: presib, dissertation
Author: Nuno Fernandes
Summary: This Post provides content related to Nuno Fernandes' dissertation entitled *Modelo Gráfico para Simulação e Controlo do Chão de Fábrica no Contexto da Indústria 5.0*



This Post provides the links to files, documentation and information mentioned on Nuno Fernandes’ dissertation to be presented on IPBeja. It is organized as follows: 

 

- **Repositories** – Information about the different repositories 
- **Helios Models** - SVG images of the models described on Chapter 4 *PRESIB Model* 
- **Simulation Resource** – Log files and Listing of all tables and diagrams produced 

 

# Repositories 

PRESIB project is hosted on GitHub and is composed by the following repositories: 

## <a id="presib-web">Presib</a>

Description: This repository contains the source code of this web site. It is built using <a href="https://getpelican.com/" target="_blank">Pelican</a>.

Link:  <a href="https://github.com/PRESIB/presib" target="_blank">https://github.com/PRESIB/presib</a>

## <a id="helios">Helios</a> 

Description: This repository contains the nets referenced in the Chapter 4 on section *Helios* (4.2.1). Is the package that contains the nets used on the model. It is build using <a href="http://www.renew.de/" target="_blank">Renew - The Reference Net Workshop</a>. It is a JAVA based editor and simulator for the <a href="https://www.logos-verlag.de/cgi-bin/engbuchmid?isbn=0035&lng=deu&id=" target="_blank">Refenrence Nets</a> that is a high-level formalism of <a href="https://www.informatik.uni-hamburg.de/TGI/PetriNets/index.php" target="_blank">Petri Nets</a>.

Link: <a href="https://github.com/PRESIB/helios" target="_blank">https://github.com/PRESIB/helios</a>
## <a id="hermes">Hermes</a>    

Description: This repository contains the sorce code referenced in Chapter 4 on section *Hermes* (4.2.2). Is the package that contains the source code used on the model. It is built using <a href="https://kotlinlang.org/" target="_blank">Kotlin</a>. The source code is compiled to a <a href="https://www.java.com/en/" target="_blank">Java</a> JAR file.

Link: <a href="https://github.com/PRESIB/hermes" target="_blank">https://github.com/PRESIB/hermes</a>

## <a id="hephaestus">Hephaestus</a> 

Description: This repository contains the source code of the microcontrollers used on the simulation. It is built using <a href="https://platformio.org/" target="_blank">PlatformIO</a>.

Link: <a href="https://github.com/PRESIB/hephaestus" target="_blank">https://github.com/PRESIB/hephaestus</a>

## Ponos 

Description: This repository contains the source code of the parser application used to generate the charts and tables from the simulation's logs. It is built using <a href="https://nodejs.org" target="_blank">NodeJS</a>.


Link: a href="https://github.com/PRESIB/ponos" target="_blank">https://github.com/PRESIB/ponos</a>





## Presib-model 

Description: Legacy repository that holds information related with the article [A Graphical and Executable Model for Production Simulation in the Context of Industry 5.0.](https://ieeexplore.ieee.org/document/9831527) This repository has been archived and is not mantained any more. 

Link: 

## documentation 

Description: Host documentation mentioned on the articles. Each branch is related with a specific article. 

 

# <a id="helios-models"></a>Helios Models 

List of the available hets that compose the Helios <a href="https://github.com/PRESIB/helios" target="_blank">repository</a>

<table>
<tr>
<th>Playground</th>
<th>Product Holon</th>
<th>Resource Holon</th>
<th>Service Register</th>
<th>Holon Communicator</th>
<th>MQTT Message Receiver</th>
</tr>

<tr>
<td><img width="150" src="https://raw.githubusercontent.com/PRESIB/helios/master/images/playground.svg"></td>
<td><img width="150" src="https://raw.githubusercontent.com/PRESIB/helios/master/images/productHolon.svg"></td>
<td><img width="150" src="https://raw.githubusercontent.com/PRESIB/helios/master/images/resourceHolon.svg"></td>
<td><img width="150" src="https://raw.githubusercontent.com/PRESIB/helios/master/images/service_register.svg"></td>
<td><img width="150" src="https://raw.githubusercontent.com/PRESIB/helios/master/images/holon_communicator.svg"></td>
<td><img width="150" src="https://raw.githubusercontent.com/PRESIB/helios/master/images/mqtt_message_receiver.svg"></td>
</tr>
<tr>
<td><a href="https://github.com/PRESIB/helios/blob/32aef2b2200d7bde7de39699edd0cf217fef2031/imges/playground.svg" target="_blank">File on Repository</a></td>
<td><a href="https://github.com/PRESIB/helios/blob/3b253c995de783ffed2eec4dc59b600d98131d4a/images/productHolon.svg" target="_blank">File on Repository</a></td>
<td><a href="https://github.com/PRESIB/helios/blob/3b253c995de783ffed2eec4dc59b600d98131d4a/images/resourceHolon.svg" target="_blank">File on Repository</a></td>
<td><a href="https://github.com/PRESIB/helios/blob/3b253c995de783ffed2eec4dc59b600d98131d4a/images/service_register.svg" target="_blank">File on Repository</a></td>
<td><a href="https://github.com/PRESIB/helios/blob/3b253c995de783ffed2eec4dc59b600d98131d4a/images/holon_communicator.svg" target="_blank">File on Repository</a></td>
<td><a href="https://github.com/PRESIB/helios/blob/3b253c995de783ffed2eec4dc59b600d98131d4a/images/mqtt_message_receiver.svg" target="_blank">File on Repository</a></td>
</tr>
<tr>
<td><a href="https://raw.githubusercontent.com/PRESIB/helios/master/images/playground.svg" target="_blank">View Image in full screen</a></td>
<td><a href="https://raw.githubusercontent.com/PRESIB/helios/master/images/productHolon.svg" target="_blank">View Image in full screen</a></td>
<td><a href="https://raw.githubusercontent.com/PRESIB/helios/master/images/resourceHolon.svg" target="_blank">View Image in full screen</a></td>
<td><a href="https://raw.githubusercontent.com/PRESIB/helios/master/images/service_register.svg" target="_blank">View Image in full screen</a></td>
<td><a href="https://raw.githubusercontent.com/PRESIB/helios/master/images/holon_communicator.svg" target="_blank">View Image in full screen</a></td>
<td><a href="https://raw.githubusercontent.com/PRESIB/helios/master/images/mqtt_message_receiver.svg" target="_blank">View Image in full screen</a></td>
</tr>
</table>



# <a id="simulations-resources"></a>Simulations Resources 






just a test to [Hephaestus](#hephaestus)