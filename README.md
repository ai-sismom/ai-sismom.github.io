## Project SisMOM / INPE / MCTI

<embed type="text/html" src="assets/html/br_map.html" width="600" height="600">

SisMOM is an acronym for **Oil Spill Monitoring System for the Ocean** in Portuguese (Brazil). It is funded by the Ministry of Science and Technology ([MCTI](https://www.gov.br/mcti/pt-br)) via [FINEP](http://www.finep.gov.br/) and is executed by [INPE](https://www.gov.br/inpe/pt-br) which engaged several partners institutions. In a nutshell, SisMOM is a proof of concept of a dissuasion system for IBAMA and Brazilian Navy and is based on nine sub-projects which are composed by a coordinator and collaborators. [More about SisMOM]().

## SisMOM composition

| Description of the sub-goals | Example |
|-|:-:|
| **1. Ship Detection:** Responsible for detecting ships from satellite data (optical and SAR). Traditional CFAR methodology and Deep Learning is going to be used to build a labelled dataset for AI training. | [<img src="https://www.researchgate.net/profile/Haitao-Lang/publication/270769959/figure/fig1/AS:613919064334338@1523381119250/Typical-samples-of-challenges-for-both-ship-detection-and-category-recognition-in.png" alt="(Lang et al., 2014)" />](https://www.researchgate.net/publication/270769959_Hierarchical_ship_detection_and_recognition_with_high-resolution_polarimetric_synthetic_aperture_radar_imagery)[^1] |
| **2. Oil Spill Detection:** Responsible for detecting oil spill in the ocean, also from satellite data (optical and SAR). This sub-project will also build a labelled training dataset with uses cases occurred in Brazil by using traditional (but good) methodologies. In addition to monitor oil spill in the ocean, we'll mine social media in order to check (via AI) for messages and photos related to oil spill on the beach. This is important because in some cases the oil navigates under the surface of the water and suddenly appears on the beach and we want to know it as soon as possible. | [<img src="https://www.researchgate.net/profile/Gui-Song_XIA/publication/281530593/figure/fig2/AS:284594248142856@1444863965040/Segmenting-SAR-images-of-a-pond-top-and-oil-spill-bottom-From-left-to-right.png" alt="(Lang et al., 2014)" />](https://www.researchgate.net/figure/Segmenting-SAR-images-of-a-pond-top-and-oil-spill-bottom-From-left-to-right_fig2_281530593)[^2] |
| **3. Oil Dispersion:** Responsible for the oil trajectory, the oil dispersion, both forward as backwards. This is super important because we want to know where the oil came from (to match the back trajectory with the ships detected by M1) and to where it will go, in order to advise coast cities at the ending trajectory (if it happens) in terms of amount of oil and when it will eventually reach the city. | <img src="/assets/img/TrajetoriaReversa.jpg" alt="(Oil Backwards Trajectory, by JRMGarcia)" />[^3] |
| **4. Situation Room:** Responsible for showing the current state of every detection at SisMOM and sub tasks being processed, as your Cerulean web interface and alert system. Is is also responsible for starting the backwards and forwards trajectories of the oil as soon as some oil spill is detected by some source, either in the ocean or in the beach. | | 
| **5. Hydrodynamic Modelling:** Responsible for the coupled numeric modelling of the ocean and atmosphere. The BESM (Brazilian Earth System Model) will simulate the globe in a low resolution and the Eta Model will refine the grid up down 100m in the horizontal grid resolution. | [<img src="https://www.windows2universe.org/earth/climate/images/ucar_model_input.jpg" alt="(Windows to the Universe ®)" />](https://www.windows2universe.org/earth/Water/ocean_atmosphere_coupled_models.html)[^5] |
| **6. Infrastructure and DB:** Deals with the infrastructure used by the project, things like which environment to use, where and how to store the datasets, where to process jobs, run AI training, how things communicate among them, etc. This includes from where the Situational Room will run. | [<img src="https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/styles/full_width/public/thumbnails/image/Figure3_STEMModeling.jpg?itok=g52rEgUB" alt="(Eastern Ecological Science Center)" />](https://www.usgs.gov/media/images/gis-data-layers-visualization)[^6] |
| **7. Drone Surveilance:** Responsible for providing an hierarchy of drones for crossing along beaches seeking for oils spills, find then and report. | <img src="/assets/img/SAM-OilSlicks.png" alt="(by JRMGarcia)" />[^7] |
| **8. Satellite Surveilance:** Is only a study about the needed hierarchy of satellites to monitor our 5.5 million km2 of our ocean. We will not provide them, they are just studies of feasibility to be executed in another project. | |
| **9. Artificial Intelligence:** Is present at every sub-goal. It will be used to not only improve the outcomes from every sub-project as their input data. | |

## SisMOM AI Team
*  [JR Garcia](https://github.com/Garcia-INPE)
*  [Maria Paula Graziotto](https://github.com/)
*  [Bruna Leal](https://github.com/bruezb)
*  [Fernando Bertolaccini](https://github.com/fernando-bertolaccini)
*  [Melissa Oliveira](https://github.com/)

### References
[^1]: Lang, Haitao & Zhang, Jie & Zhang, Ting & Zhao, Di & Meng, Junmin. (2014). Hierarchical ship detection and recognition with high-resolution polarimetric synthetic aperture radar imagery. Journal of Applied Remote Sensing. 8. 083623. 10.1117/1.JRS.8.083623. 
[^2]: Liu, Gang & Xia, Gui-Song & Yang, Wen. (2013). SAR Image Segmentation via Non-local Active Contours. International Geoscience and Remote Sensing Symposium (IGARSS). 10.1109/IGARSS.2014.6947294. 
[^3]: Produced by [Ebenezer Agyei-Yeboah.](https://github.com/), SisMOM's scholarship holder.
[^5]: [Windows to the Universe ®](http://windows2universe.org) © 2010, [National Earth Science Teachers Association](http://www.nestanet.org/).
[^6]: [The U.S. Geological Survey](https://www.usgs.gov/centers/eesc) public domain archive.
[^7]: Produced by [JR Garcia](https://github.com/Garcia-INPE) SisMOM's AI Coordinator.
