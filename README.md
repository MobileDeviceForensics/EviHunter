# EviHunter
This repository hosts the sources and sinks used by EviHunter, a static program analysis tool for forensic analysis of the file systems on Android devices. If you use these sources/sinks, please cite the following paper:

Chris Chao-Chun Cheng, Chen Shi, Neil Zhenqiang Gong, and Yong Guan. "EviHunter: Identifying Digital Evidence in the Permanent Storage of Android Devices via Static Analysis". In ACM Conference on Computer and Communications Security (CCS), 2018.

  ## Documents
  - Source methods: Represent the types of evidence, used in both the reported evidentiary data types and constructing the file paths.
  - Sink methods: Inherited from existing tools such as [FlowDroid](https://github.com/secure-software-engineering/FlowDroid), [DroidSafe](https://github.com/MIT-PAC/droidsafe-src).
  - Dynamic paths: The path tag <intent> is used whenever EviHunter cannot statically parse the exact data (string) from the ICC bundles.
  
  ## Publication
  Chris Chao-Chun Cheng, Chen Shi, Neil Zhenqiang Gong, and Yong Guan. "EviHunter: Identifying Digital Evidence in the Permanent Storage of Android Devices via Static Analysis". In ACM Conference on Computer and Communications Security (CCS), 2018.
  
Link to our [presentation slides](https://drive.google.com/file/d/1BuVSfVueBKidzo8T1cYBQB9jjR7QJuXH/view?usp=sharing) in ACM CCS 2018 in Toronto, Canada.
  
  ## Contacts
