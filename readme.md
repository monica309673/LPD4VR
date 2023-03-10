### Business Process Dataset of Service Regulation (Labelled process dataset for violation recognition 2.0, LPD4VR2.0)

A business process dataset of Internet healthcare service regulation, which contains 102 service process files. All business process files are in XML format.

 **<summary>Detail</summary>**

[comment]: <One-line summary (TL:DR)>
  
* This dataset contains mainly 74 compliant processes, 15 violation processes, and 13 unknown processes(processes that do not fall within the regulatory scope of Internet medical services). The process files in XML format follow the BPMN2.0 standard. 

[comment]: <Name (email address)>
* **Maintainer**: Jintao Chen(chenjintao@zju.edu.cn)

[comment]: <Last modification date>
* **Last Modification**: 2023.02.21

* **dataset sample**:
   <img src="https://github.com/monica309673/LPD4VR/blob/master/sample.svg" >
 
* **regulation rules**:
   * Internet medical services cannot provide first-diagnosis services
   * The medical staff need to be authenticated before conducting consultations
   * Qualification review is required for medical institutions to settle in
   * Qualification review is required for the entry of medical staff
   * The service process must be complete
* **data augmentation method**:
   * Back-translation
   * Randomly removing some of the task nodes
   * Targeted change of some compliance processes to violation processes, e.g. removal of some data objects required for compliance.

* **dataset analysis**:
  * **Distribution of the BPMN elements numbers in the dataset**：
  
    <img src="https://github.com/monica309673/LPD4VR/blob/master/lens.png" width="500px">
    
  * **Semantic distribution of processes in the dataset**:
  
    <img src="https://github.com/monica309673/LPD4VR/blob/master/tsne4.png" width="500px">
   
