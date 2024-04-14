## About SisMOM / INPE / MCTI Project

SisMOM is an acronym for **Oil Spill Monitoring System for the Ocean**. It is funded by the Ministry of Science and Technology ([MCTI]()) via [FINEP]() and is executed by [INPE]() which engaged several partners institutions. In a nutshell, SisMOM, is a proof of concept of a dissuasion tool for IBAMA and Brazilian Navy and is based on nine sub-projects which is composed by a coordinator and collaborators. [More about SisMOM]().

## SisMOM Main Goals

<p>
<img src="https://www.researchgate.net/profile/Haitao-Lang/publication/270769959/figure/fig1/AS:613919064334338@1523381119250/Typical-samples-of-challenges-for-both-ship-detection-and-category-recognition-in.png" alt="(Lang et al., 2014)" align="right" height="100px" width="200px" />
1. Ship Detection</p>
Responsible for detecting ships from satellite data (optical and SAR). Traditional CFAR methodology and Deep Learning is going to be used to build a labelled dataset for AI training.


<p>
<img src="https://www.researchgate.net/profile/Haitao-Lang/publication/270769959/figure/fig1/AS:613919064334338@1523381119250/Typical-samples-of-challenges-for-both-ship-detection-and-category-recognition-in.png" alt="(Lang et al., 2014)" align="right" height="100px" width="200px" />
2. Oil Spill Detection</p>
Responsible for detecting oil spill in the ocean, also from satellite data (optical and SAR). This sub-project will also build a labelled training dataset with uses cases occurred in Brazil by using traditional (but good) methodologies. Dr. Milton Kampel, from INPE's Remote Sensing dept is the coordinator. In addition to monitor oil spill in the ocean, we'll mine social media in order to check (via AI) for messages and photos related to oil spill on the beach. This is important because in some cases the oil navigates under the surface of the water and suddenly appears on the beach. And we want to check it as soon as possible.

### 3. Oil Dispersion
 M3 is responsible for the oil trajectory, the oil dispersion, both forward as backwards. This is super important because we want to know where the oil came from (to match the back trajectory with the ships detected by M1) and to where it will go, in order to advise coast cities at the ending trajectory (if it happens) in terms of amount of oil and when it will eventually reach the city. Dr. Angelo Lemos, from University of Southern Bahia is the coordinator.

### 4. Situation Room
* M4 is our Situational Room, it will be responsible for showing the current state of every detection at SisMOM and sub tasks being processed, as your Cerulean web interface and alert system. Is is also responsible for starting the backwards and forwards trajectories of the oil as soon as some oil spill is detected by some source, either in the ocean or in the beach. Dr. Eymar Lopes, also from INPE's remote sensing dept, is the responsible researcher.

### 5. Hydrodynamic Modelling
* M5 is the sub-project responsible for the coupled numeric modelling of the ocean and atmosphere. The BESM (Brazilian Earth System Model) will simulate the globe in a low resolution and the Eta Model will refine the grid up down 100m in the horizontal grid resolution. Dr. Vinicius Capistrano, from the Mato Grosso do Sul University is the coordinator.

### 6. Infrastructure and DB
* M6 deals with the infrastructure used by the project, things like which environment to use, where and how to store the datasets, where to process jobs, run AI training, how things communicate among them, etc. This includes from where the Situational Room will run. Dr. Jorge Gomes, from INPE's modelling group is in charge.

### 7. Drone Surveilance
### 8. Satellite Surveilance
* M7 and M8 - Are only studies about the needed hierarchy of drones, UAVs (Unmanned Aerial Vehicles) and satellites to monitor our 5.5 million km2 of our ocean. We will not provide them, they are just studies of feasibility to be executed in another project.

### 9. Artificial intelligence
* M9 is the Artificial Intelligence sub-project, as can be seen in the figure, it is present at every goal. It will be used to not only improve the outcomes from every sub-project as their input data. I'm also the coordinator of this sub-project. The M.Sc. in oceanography Maria Paula Graziotto (cc) is also in this team and will be responsible for segmenting the oil spill from satellite data in order to accelerate the built of the dataset. 


<!-- 
(https://www.researchgate.net/publication/270769959_Hierarchical_ship_detection_and_recognition_with_high-resolution_polarimetric_synthetic_aperture_radar_imagery) | [<img width="100%" height="100%" src="https://www.researchgate.net/profile/Gui-Song_XIA/publication/281530593/figure/fig2/AS:284594248142856@1444863965040/Segmenting-SAR-images-of-a-pond-top-and-oil-spill-bottom-From-left-to-right.png" alt="(Liu et al., 2013)" style="text-align: center; height: 100px; width:100%;"/>]() | [<img width="100%" height="100%" src="https://www.researchgate.net/profile/Haitao-Lang/publication/270769959/figure/fig1/AS:613919064334338@1523381119250/Typical-samples-of-challenges-for-both-ship-detection-and-category-recognition-in.png" alt="(Lang et al., 2014)" style="text-align: center; height: 100px; width:200;"/>](https://www.researchgate.net/publication/281530593_SAR_Image_Segmentation_via_Non-local_Active_Contours) |
--> 
                       
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

## Team:

*  MP Graziotto
*  Bruna
*  Fernando
*  Melissa 
