# Provenance in Social Computing
SCU-Provenance is tool which supports social computing unit (SCU) to take the advantages of the provenance data of Komadu.

## Description
Complex systems such as Collective Adaptive Systems that include a variety of resources, are increasingly being designed to include people in task-execution. Collectives, encapsulating human resources/services, represent one type of an appli- cation within which people with different type of skills can be engaged to solve one common problem or work on the same project. Mechanisms of managing social col- lectives are dependent on functional and non-functional parameters of members of social collectives. In SCU-Provenance, we implemented the functions to employ provenance in developing more efficient provisioning and management mechanisms in social computing.


## Dependencies
SCU-Provenance requires provenance services of Komadu (https://github.com/Data-to-Insight-Center/komadu) and Komadu SDK.


## Usage
Deploy Komadu in a Ubuntu 14.04 virtual machine. Please follow the guideline to deploy Komadu from its repository.
Install JDK 1.8.x in another virtual machine. 
Clone the source code of SCU-Provenance
Modify the Komadu service endpoint and log file path in class SCUProvo
Compile the source code using Maven
Excute the built .jar file with the main class SCUProvo  

## Publications
* Mirela Riveni, Tien-Dung Nguyen, Mehmet S. Aktas and Schahram Dustdar. "Application of Provenance in Social Computing: A Case Study" submitted to Concurrency and Computation: Practice and Experience, 2018.

## License
GNU General Public License
