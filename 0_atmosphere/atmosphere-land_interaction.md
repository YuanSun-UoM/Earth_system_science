# 陆气耦合

- reference: https://www.bilibili.com/video/BV1Qi4y1F7cx/?spm_id_from=333.337.search-card.all.click, Zhanqing Li
- 边界层中能量、水分、物质的交换。对于空气质量和气候最主要的影响，其一是太阳辐射（太阳辐射到达地面之后转化为感热通量和潜热通量。感热通量驱动对流，潜热与水汽以及对流产生的云有关。）
  - https://journals.ametsoc.org/view/journals/bams/99/6/bams-d-17-0001.1.xml
  - https://link.springer.com/article/10.1007/s00704-004-0101-4
  - ![10.1175:BAMS-D-17-0001.1](/Users/user/Desktop/YuanSun-UoM/A_my_progress/figure/10.1175:BAMS-D-17-0001.1.jpg)

![PBL-Aerosol-Convection-Interaction](/Users/user/Desktop/YuanSun-UoM/A_my_progress/figure/PBL-Aerosol-Convection-Interaction.jpg)

- 边界层的确认问题：不同的边界层定义 https://doi.org/10.1016/j.atmosenv.2013.07.019
  - 遥感：用激光雷达对边界层进行判断
  - 污染：边界层对于气溶胶的影响（气溶胶作为边界层的示踪物）

![observation_of_PBL_variations](/Users/user/Desktop/YuanSun-UoM/A_my_progress/figure/observation_of_PBL_variations.jpg)

- 气溶胶的影响 https://academic.oup.com/nsr/article/4/6/810/4191281
  - 减弱地面热通量，进而影响边界层
  - 大气中吸收性强的气溶胶导致逆温inversion，进而影响大气稳定性，加速气溶胶扩展
    - 计算逆温频率 inversion frequency

![Aerosal-PBL_interaction_mechanisms](/Users/user/Desktop/YuanSun-UoM/A_my_progress/figure/Aerosal-PBL_interaction_mechanisms.jpg)

- Aerosol Optical Depth (AOD) 气溶胶光学厚度
  - in the cam6 (https://www2.cesm.ucar.edu/models/cesm2/atmosphere/docs/ug6/hist_flds_f2000.html), AODVISdn is all-sky calculation

![evidence_of_PBL_airpollution_feedback](/Users/user/Desktop/YuanSun-UoM/A_my_progress/figure/evidence_of_PBL_airpollution_feedback.jpg)

- 大气的状态
  - stable: In a stable atmosphere, a parcel of air that is displaced vertically (either upwards or downwards) tends to return to its original position.
  - neutral: In a neutral atmosphere, a parcel of air that is displaced vertically will neither return to its original position nor continue to rise or fall significantly.
  - Convective (Unstable) : In a convective or unstable atmosphere, a parcel of air that is displaced vertically will continue to move in the direction of displacement.

- Aerosol-PBL-Cloud-interactions: Microphysical and dynamic process
  - 气溶胶对于云的影响：一是通过气溶胶对于边界层的影响，二是为大气中的黑炭

![cloud_microphysical_processes](/Users/user/Desktop/YuanSun-UoM/A_my_progress/figure/cloud_microphysical_processes.jpg)

- 陆面过程

![land_surface_processes](/Users/user/Desktop/YuanSun-UoM/A_my_progress/figure/land_surface_processes.jpg)

[water cycle](https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/thumbnails/image/water-cycle-natural.jpg)

- Noah-MP (杨宗良)的特点

  - https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2010JD015139
  - https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2010JD015140

  - multi-physics (MP) 包含多物理过程，可进行多种组合，优点包括：
    - addressing challenges
    - quantifying uncertainty
    - identifying research gap
    - improving process-level understanding
    - developing schemes for new processes

  ![Noah-MP](/Users/user/Desktop/YuanSun-UoM/A_my_progress/figure/Noah-MP.jpg)

- a new approach to global climate modeling: reduce dependence on parameterizations where possible; account for their uncertainty where not. This requires directly simulate deep convection, oceanic eddies, and important land-atmosphere interactions. [ref](10.1073/pnas.1906691116)
- Challegenges

- EU's plan to revolutionize climate forecasts. at 1-km, a climate is nearly indistinguishable from reality.

![land-atmosphere-interaction_challegnes](/Users/user/Desktop/YuanSun-UoM/A_my_progress/figure/land-atmosphere-interaction_challegnes.png)

- a new nirmal in land surface modelling 陆面模型新常态
  - 预测极端事件 predicting extreme events, e.g., floods, droughts, heat waves, dusts, wildfires
  - 紧扣地域特色 targeting regional features, e.g., complex terrain and coastal lines
  - 联系人类活动 focusing on human activities, e.g., irrigation and urbanization
  - 衔接重大国策 connecting with key policies, e.g., The Grain for Green Program
  - 关注衣食住行 paying attention to clothing, food, shelter, and transportation