## About SisMOM / INPE / MCTI Project

SisMOM is an acronym for **Oil Spill Monitoring System for the Ocean**. It is funded by the Ministry of Science and Technology ([MCTI]()) via [FINEP]() and is executed by [INPE]() which engaged several partners institutions. In a nutshell, SisMOM, is a proof of concept of a dissuasion tool for IBAMA and Brazilian Navy and is based on nine sub-projects which is composed by a coordinator and collaborators. [More about SisMOM]().

## SisMOM Main Goal

| Description of the Objective | Example |
|-|:-:|
| **1. Ship Detection:** Responsible for detecting ships from satellite data (optical and SAR). Traditional CFAR methodology and Deep Learning is going to be used to build a labelled dataset for AI training. | <img src="https://www.researchgate.net/profile/Haitao-Lang/publication/270769959/figure/fig1/AS:613919064334338@1523381119250/Typical-samples-of-challenges-for-both-ship-detection-and-category-recognition-in.png" alt="(Lang et al., 2014)" /> |
| **2. Oil Spill Detection:** Responsible for detecting oil spill in the ocean, also from satellite data (optical and SAR). This sub-project will also build a labelled training dataset with uses cases occurred in Brazil by using traditional (but good) methodologies. In addition to monitor oil spill in the ocean, we'll mine social media in order to check (via AI) for messages and photos related to oil spill on the beach. This is important because in some cases the oil navigates under the surface of the water and suddenly appears on the beach. And we want to check it as soon as possible. | <img src="https://www.researchgate.net/profile/Haitao-Lang/publication/270769959/figure/fig1/AS:613919064334338@1523381119250/Typical-samples-of-challenges-for-both-ship-detection-and-category-recognition-in.png" alt="(Lang et al., 2014)" /> |
| **3. Oil Dispersion:** Responsible for the oil trajectory, the oil dispersion, both forward as backwards. This is super important because we want to know where the oil came from (to match the back trajectory with the ships detected by M1) and to where it will go, in order to advise coast cities at the ending trajectory (if it happens) in terms of amount of oil and when it will eventually reach the city. | <img src="/assets/img/TrajetoriaReversa.jpg" alt="(Oil Backwards Trajectory, by JRMGarcia)" /> |
| **4. Situation Room:** Responsible for showing the current state of every detection at SisMOM and sub tasks being processed, as your Cerulean web interface and alert system. Is is also responsible for starting the backwards and forwards trajectories of the oil as soon as some oil spill is detected by some source, either in the ocean or in the beach. | | 
| **5. Hydrodynamic Modelling:** Responsible for the coupled numeric modelling of the ocean and atmosphere. The BESM (Brazilian Earth System Model) will simulate the globe in a low resolution and the Eta Model will refine the grid up down 100m in the horizontal grid resolution. | |
| **6. Infrastructure and DB:** Deals with the infrastructure used by the project, things like which environment to use, where and how to store the datasets, where to process jobs, run AI training, how things communicate among them, etc. This includes from where the Situational Room will run. | |
| **7. Drone Surveilance:** Responsible for providing an hierarchy of drones for crossing along beaches seeking for oils spills, find then and report. | |
| **8. Satellite Surveilance:** Is only a study about the needed hierarchy of satellites to monitor our 5.5 million km2 of our ocean. We will not provide them, they are just studies of feasibility to be executed in another project. | |
| **9. Artificial Intelligence:** Is present at every sub-goal. It will be used to not only improve the outcomes from every sub-project as their input data. | <img src="/assets/img/SAM-OilSlicks.png" alt="(by JRMGarcia)" /> |

## References

* Ship Detection: Lang, Haitao & Zhang, Jie & Zhang, Ting & Zhao, Di & Meng, Junmin. (2014). Hierarchical ship detection and recognition with high-resolution polarimetric synthetic aperture radar imagery. Journal of Applied Remote Sensing. 8. 083623. 10.1117/1.JRS.8.083623. 

* Oil Detection: Liu, Gang & Xia, Gui-Song & Yang, Wen. (2013). SAR Image Segmentation via Non-local Active Contours. International Geoscience and Remote Sensing Symposium (IGARSS). 10.1109/IGARSS.2014.6947294. 


<!-- 
SisMOM's AI Team homepage
[INPE' homepage](https://www.gov.br/inpe/pt-br)

## Coordination: Garcia
![Alt text](https://media.licdn.com/dms/image/C4E03AQHGWTSbVI0eLQ/profile-displayphoto-shrink_200_200/0/1516305289998?e=1718236800&v=beta&t=xaiBsbI7jk3lDJSdpLaUs129mpv4Q7RWkCvqDgJG12U)

HTML
| Old me | New me |
|---|---|
| <img src="http://www3.cptec.inpe.br/dimnt/wp-content/uploads/sites/3/2020/07/JOS%C3%89-ROBERTO-MOTTA-GARCIA.png" width="125" height="125"> | <img src="/img/JRMGarcia.jpeg" width="125" height="125"> |
-->

## SisMOM AI Team

*  [JR Garcia](https://github.com/Garcia-INPE)
*  [Maria Paula Graziotto](https://github.com/)
*  [Bruna Leal](https://github.com/bruezb)
*  [Fernando Bertolaccini](https://github.com/fernando-bertolaccini)
*  [Melissa Oliveira](https://github.com/)

