Title: Dissertation Related Content
Date: 30/07/2022
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

List of simulations and Results

|      | Simulation                                                   | Log file | Data files                                                   | Chart                                                        | Comment |
| ---- | ------------------------------------------------------------ | -------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------- |
|      | [1ph_10xserv1_1ph_10xserv2_1ph_10xserv3__10rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs1ph_10xserv1_1ph_10xserv2_1ph_10xserv3__10rht_10rhm.log) |          | [JSON](https://raw.githubusercontent.com/PRESIB/documentation/simulation_june_2022/simulation-results/results/1ph_10xserv1_1ph_10xserv2_1ph_10xserv3__10rht_10rhm.log_1658253879513.json)<br />[STEP](https://github.com/PRESIB/documentation/blob/simulation_june_2022/simulation-results/results/procustion_steps_1ph_10xserv1_1ph_10xserv2_1ph_10xserv3__10rht_10rhm.log_1658253879513.json_1658253895688.csv)<br />[TIMES PER SERVICE](https://github.com/PRESIB/documentation/blob/simulation_june_2022/simulation-results/results/times_per_Service_1ph_10xserv1_1ph_10xserv2_1ph_10xserv3__10rht_10rhm.log_1658253879513.json_1658253895693.csv)<br />[TOTAL TIMES](https://github.com/PRESIB/documentation/blob/simulation_june_2022/simulation-results/results/total_times_1ph_10xserv1_1ph_10xserv2_1ph_10xserv3__10rht_10rhm.log_1658253879513.json_1658253895698.csv) | <img src="https://raw.githubusercontent.com/PRESIB/documentation/simulation_june_2022/simulation-results/results/times_per_Service_1ph_10xserv1_1ph_10xserv2_1ph_10xserv3__10rht_10rhm.log_1658253879513.json_1658253910766.svg?sanitize=true" /><br /><a href="https://raw.githubusercontent.com/PRESIB/documentation/simulation_june_2022/simulation-results/results/total_times_1ph_10xserv1_1ph_10xserv2_1ph_10xserv3__10rht_10rhm.log_1658253879513.json_1658253910797.svg?sanitize=true" target="_blank" a>Download</a> |         |
|      | [3diff_ph_10rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs3diff_ph_10rht_10rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [10ph_10xserv1_10ph_10xserv2_10ph_10xserv3__10rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs10ph_10xserv1_10ph_10xserv2_10ph_10xserv3__10rht_10rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [30diff_ph_10rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs30diff_ph_10rht_10rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [100ph_10xserv1_5rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs100ph_10xserv1_5rht_10rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [100ph_10xserv1_10rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs100ph_10xserv1_10rht_10rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [100ph_10xserv1_10rht_20rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs100ph_10xserv1_10rht_20rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [100ph_10xserv1_100ph_10xserv2_100ph_10xserv3__10rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs100ph_10xserv1_100ph_10xserv2_100ph_10xserv3__10rht_10rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [100ph_10xserv2_5rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs100ph_10xserv2_5rht_10rhm%20.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [100ph_10xserv2_10rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs100ph_10xserv2_10rht_10rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [100ph_10xserv2_10rht_20rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs100ph_10xserv2_10rht_20rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [100ph_10xserv3_5rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs100ph_10xserv3_5rht_10rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [100ph_10xserv3_10rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs100ph_10xserv3_10rht_10rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [100ph_10xserv3_10rht_20rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs100ph_10xserv3_10rht_20rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm_1](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm_1.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm_2](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm_2.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm_3](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm_3.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm_4](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm_4.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm_5](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm_5.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm_6](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm_6.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm_7](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm_7.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm_8](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm_8.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm_9](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm_9.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      | [300diff_ph_10rht_10rhm_10](https://raw.githubusercontent.com/PRESIB/documentation/blob/simulation_june_2022/logs300diff_ph_10rht_10rhm_10.log) |          | JSON<br />STEP<br />TIMES PER SERVICE<br />TOTAL TIMES       |                                                              |         |
|      |                                                              |          |                                                              |                                                              |         |
|      |                                                              |          |                                                              |                                                              |         |




just a test to [Hephaestus](#hephaestus)