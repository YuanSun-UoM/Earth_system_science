# Energy transfer

## conduction 热传导

- 固体（热传导过程中载体不移动）

## convection 热对流

- 流体

## radiation 热辐射

- 通过电子和电磁波传递能量
- radiation quality and quantity 
  - The amplitude corresponds to the energy carried. 辐射波的振幅越大，携带的能量越高 
  - The wavelength corresponds to the type. 波长对应辐射类型

### Stefan-Boltzman Law

- Governs how much energy is radiated.

### Wien’s Law

- Governs wavelength radiated at greatest intensity.

## Atmosphere-land interaction

- The Earth and atmosphere emit almost completely longwave radiation (thermal infrared).
- This radiation emitted by the Earth is largely absorbed by the atmosphere (carbon dioxide and water vapor). 地球发射的长波辐射大部分被大气吸收（二氧化碳和水蒸气）

- 对流
  - Free Convection – convection related to buoyancy：空气略过地表受热膨胀，在上升过程中冷却，循环
  - Forced Convection – turbulence, formation of eddies as the large-scale flow breaks down 强制对流-湍流，大尺度气流破裂时形成涡流

### sensible heat

- Sensible – heat which we physically sense
- The magnitude of temperature is related to two factors: Specific heat; Mass

- capture the amplitude and phase of the sensible heat fluxes 捕捉感热通量的振幅和相位

### latent heat

- Latent – energy exchange required to change a phase of a substance  改变物质的一个相所需要的能量交换
  - Latent heat of fusion (solid to liquid) - melting 固体到液体，熔化潜热
  - Latent heat of evaporation (liquid to gas) –vaporization  蒸发潜热(液体到气体)-汽化
  - Latent heat of sublimation (solid to gas)  升华潜热(固体到气体)
  - Latent heat of freezing (liquid to solid) 冻结潜热(液体到固体)
  - Latent heat of condensation (gas to liquid) 
  - Latent heat of deposition (gas to solid)

感热和潜热通量的分配差异可以由波文比表征，即某一界面上感热通量与潜热通量的比值。较大的波文比表明湍流热通量以感热为主，通常伴随干燥气候，而较小值表明潜热为主导，通常出现在潮湿气候下。波文比的增加表明地面温度增强，可能会加剧干旱；而波文比的降低可以减缓地表变暖，并影响大气中的云和降水过程。
- 地表热通量（热通量包括：感热通量、潜热通量、地表净辐射量、土壤热通量）
- 感热和潜热通量是湍流通量Turbulent flux
- 感热通量是指温度变化而引起的大气与土壤之间发生的湍流形式的热交换；
- 潜热通量主要是水的蒸发和凝结产生的热交换，
- 土壤热通量指地表土壤与下层土壤间热传导的热量通量，向下为正

## altitude

- 海拔高度对温度的影响
  - 白天：海拔低 的地方吸收的太阳辐射多，升温快
  - 晚上：海拔低的地方释放的长波辐射多，冷却快
- 分辨率提高后，地形对于气象预报的影响很大（在一公里的分辨率（粗分辨率）时地形的影响）
  - 风速脉动特征


## temperature means and ranges

- Daily mean – The average of the maximum and minimum temperature for that day
- Daily temperature range – subtraction of maximum temperature from minimum 
- Monthly mean – average of daily means 
- Annual mean – average of monthly means

## pressure

- Increased pressure can result from Increased density and Increased temperature
- Sea Level Pressure – the pressure that would exist if the observation point were at sea level.
- Surface Pressure – the pressure observed at a particular location
- 因为空气总是从高压流向低压。因此压强的变化导致垂直向和水平向的风。
- 在复杂地形条件下，10-m风的预报准确率比2米温度的准确率低；

### Coriolis force 科氏力：

- 地球自转引起的一种惯性力，影响着大气和海洋的运动方向。在北半球，气流和水流会向右偏转，在南半球则会向左偏转

## water 

- water vapor 水蒸气
- Droplet 水滴
- Saturation 饱和 – The maximum amount of water that can exist in the atmosphere as a vapor. 可以以水蒸气形式存在于大气中的最大水量。
  - Saturation vapor pressure: The vapor pressure of the atmosphere when it is saturated
  - Dependencies: Temperature
  - three ways to achieve saturation
    - Adding water vapor to the air 向空气中加入水蒸气
    - Lowering the temperature to the dew point 将温度降至露点
    - Mixing cold air with warm, moist air. 冷空气与温暖潮湿的空气混合
- Evaporation – Change in phase from liquid to vapor. The process in which molecules break free of the liquid volume 蒸发-从液体到蒸汽的相变。分子脱离液体体积的过程
- Condensation – Change in phase from vapor to liquid. The process whereby molecules collide with the water surface and bond with adjacent molecules. 冷凝-从蒸汽到液体的相变化。分子与水面碰撞并与邻近分子结合的过程。

### humidity

- humidity is an expression of the amount of water vapor in the air. 
- There are several ways to measure humidity: 
  - Vapor Pressure (Pressure) 
    - The part of the total atmospheric pressure due to water vapor. 由水蒸气产生的总大气压力的一部分。
    - Dependencies: Temperature
  - Absolute Humidity (Density) 
    - The density of water vapor (mass of water vapor in a volume of air). 水蒸气的密度(空气中水蒸气的质量)。不经常使用
    - Dependencies: Volume of the air
  - Specific Humidity (Mass Ratio) 
    - The mass of water vapor per unit mass of air.
    - Dependencies: Atmospheric pressure
  - Mixing Ratio (Mass Ratio) 
    - The mass of water vapor relative to the mass of the other gases.
  - Relative Humidity (Percentage) 
    - The amount of water vapor in the air relative to the maximum amount possible.
    - Dependencies: Temperature
    - Widely used, but not necessarily good
  - Dew Point Temperature (Temperature) 
    - The temperature at which saturation would occur.
    - Widely used

# turbulence modeling

- Three method [ref](https://www.intechopen.com/online-first/1181827)
  - Direct Numerical Simulation (DNS)
  - Large Eddy Simulation (LES)
    - Subgrid-scale model (LCZ-SGS)
  - Reynolds-Averaged Navier-Stokes (RANS)

# Black carbon

- soot 煤烟，烟灰
- fine particulate matter 细颗粒物：悬浮在空气中的固体颗粒或液滴，颗粒微小甚至肉眼难以辨识但仍有尺度的差异。
- PM2.5
- aerosol
- 悬浮在空中的黑碳遇雨、雪凝结后落回到地面
- 落在植物上，会降低光合作用速率（reduce plants' rate of photosynthesis）
- refractory black carbon (rBC) 难燃黑碳

## 燃烧 combustion

- Flaming-dominant combustion 
  - 由于高温和剧烈燃烧产生较大的烟灰颗粒。
  - 在耐火炭黑（rBC）的质量尺寸分布中导致较大的模态直径。
- Smolder-dominant combustion
  - 发生在较低的温度和不完全燃烧。
  - 产生更小的颗粒，将质量尺寸分布的模态直径移动到更小的值

## 黑碳老化 aging

- 途径：碰并、凝结、非均相氧化
- 混合态
- 粒径 particle size
  - Mode diameter 模态直径
  - 粒径分布中的模态直径是指粒径分布曲线的峰值， 它表示在特定分布中最常见的粒度
  - 较大的颗粒吸收和散射光更有效，影响辐射强迫。
  - 较小的颗粒在空气中停留的时间更长，可以传播得更远，影响其区域和全球影响。 较小的颗粒可以深入呼吸系统，增加健康风险。
  - the smaller the particle size the larger the specific surface (比表面积).

### coating 

## physicochemical properties 物理化学特性

### chemical composition 化学成分

- **Pure Carbon Backbone**: BC is composed primarily of elemental carbon, formed from incomplete combustion of fossil fuels, biomass, and biofuels.
- **Surface Functional Groups** (表面官能团): Often contains oxygenated or functionalized compounds due to atmospheric aging processes, altering its reactivity and hygroscopicity.

### morphology 

- **Fractal Aggregates** (分形聚集体): BC particles are typically irregular chains of smaller spherical primary particles (10–50 nm in diameter), forming a “fluffy” or fractal structure.
- **Size Distribution**: Primarily in the fine particle mode (PM2.5), with mass size distributions peaking at diameters between 100–300 nm.

### optical properties 光学特性

- **Strong Absorption of Visible and Infrared Radiation**: BC is the most light-absorbing aerosol, with a significant impact on radiative forcing. Its absorption efficiency is enhanced when coated with other materials (e.g., sulfates).
- **Single Scattering Albedo (SSA)** (单散射反照率): Low SSA indicates BC predominantly absorbs rather than scatters light.

### Hygroscopicity 吸水性，吸湿性

- **Low Intrinsic Hygroscopicity** (低固有吸湿性): Fresh BC particles are hydrophobic (疏水的) but become more hydrophilic (亲水的) through atmospheric aging (e.g., by acquiring a coating of sulfate 硫酸盐 or organic compounds 有机化合物).
- **Coating Effects**: Aging enhances the ability of BC to act as cloud condensation nuclei (CCN, 云凝结核), influencing cloud formation.
  - 云凝结核活性
  - 冰核活性

### Thermal Stability 热稳定性

- **High Stability**: BC is refractory, meaning it resists decomposition (分解) at high temperatures and is stable up to 4000°C in inert conditions.

### **Lifetime and Aging**

- **Atmospheric Lifetime**: Short-lived (days to weeks), dependent on removal processes such as wet deposition (湿沉积). 
  - Lifetime extends in dry regions.
- **Aging**: BC undergoes “aging” in the atmosphere, acquiring coatings (e.g., sulfates, nitrates 硝酸盐, organics) that increase its hygroscopicity and optical absorption (lensing effect). 增强吸水性和光学性能



# Ensemble

## [The Difference Between Deterministic and Ensemble Forecasts](https://www.worldclimateservice.com/2021/10/12/difference-between-deterministic-and-ensemble-forecasts/)

- deterministic forecast (DF) 确定性预报

- deterministic 确定性的；命运注定论的
- initial conditions (IC)
- butterfly effect: a sensitive dependence to initial conditions that can cause the model solution to be substantially different from the real world when the forecast calculation starts – the phrase implies that the flap of a butterfly’s wings could significantly change the forecast
- Ensemble Average
- Confidence: how likely the forecast is to be correct. We can see that early in the forecast (left side of graph Figure 4), the small boxes indicate a narrow range of possibilities and thus confidence is high
- challenges of ensenble forecast
  - Interpreting multiple forecasts can be complex, so very often the EA is used for simplicity.
  - As the ensemble runs at a lower resolution than the DF, it is less sensitive to changes in the IC and thus can be slower to respond to new observations.