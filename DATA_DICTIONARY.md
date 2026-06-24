# Strawberry Greenhouse Monitoring Dataset / 草莓温室监测数据集

## Basic Information / 基本信息

| Item / 项目 | Description / 说明 |
|------------|-------------------|
| Greenhouse Location / 大棚位置 | Not disclosed / 不予公开 |
| Greenhouse Area / 大棚面积 | Approximately 1.5 mu (1000 m²) / 约1.5亩（1000㎡） |
| Strawberry Variety / 草莓品种 | Zhangji (Sweet Treasure) / 章姬（甜宝） |
| Monitoring Period / 监测周期 | 2024-09-01 to 2025-03-31 (about 212 days) / 2024-09-01 至 2025-03-31（约212天） |
| Altitude / 海拔高度 | Approximately 1800m / 约1800m |
| Data Collection Frequency / 数据采集频率 | Random collection every 3-8 minutes (average ~5.5 minutes) / 每3-8分钟随机采集一次（平均约5.5分钟） |

---

## Data Overview / 数据概览

| Item / 项目 | Description / 说明 |
|------------|-------------------|
| File Name / 文件名 | strawberry_greenhouse_data.csv |
| Total Rows / 总行数 | 51,074 |
| Total Columns / 总列数 | 56 |
| Data Type / 数据类型 | Time-series sensor data / 时序传感器数据 |
| Crop / 作物 | Strawberry / 草莓 |

---

## Field Dictionary / 字段说明

### 1. Timestamp / 时间戳

| Field Name / 字段名 | Description / 说明 | Unit / 单位 |
|-------------------|-------------------|------------|
| timestamp | Data collection time / 数据采集时间 | YYYY-MM-DD HH:MM:SS |

---

### 2. Indoor Environment (Box Sensor) / 大棚室内环境（箱式传感器）

**BX01 / BX02**: Two redundant monitoring points inside the greenhouse / 大棚内双点位冗余监测

| Field Name / 字段名 | Chinese / 中文 | Description / 说明 | Unit / 单位 |
|-------------------|---------------|-------------------|------------|
| BX01_Temperature | BX01_温度 | Air temperature at monitoring point 01 / 01号监测点空气温度 | ℃ |
| BX01_Humidity | BX01_湿度 | Air relative humidity at monitoring point 01 / 01号监测点空气相对湿度 | % |
| BX01_Light | BX01_光照 | Light intensity at monitoring point 01 / 01号监测点光照强度 | lux |
| BX01_CO2 | BX01_CO2 | Carbon dioxide concentration at monitoring point 01 / 01号监测点二氧化碳浓度 | ppm |
| BX01_O2 | BX01_O2 | Oxygen concentration at monitoring point 01 / 01号监测点氧气浓度 | % |
| BX01_Noise | BX01_噪声 | Noise level at monitoring point 01 / 01号监测点噪声值 | dB |
| BX01_PM2.5 | BX01_PM2.5 | PM2.5 concentration at monitoring point 01 / 01号监测点PM2.5浓度 | μg/m³ |
| BX01_PM10 | BX01_PM10 | PM10 concentration at monitoring point 01 / 01号监测点PM10浓度 | μg/m³ |
| BX02_Temperature | BX02_温度 | Air temperature at monitoring point 02 / 02号监测点空气温度 | ℃ |
| BX02_Humidity | BX02_湿度 | Air relative humidity at monitoring point 02 / 02号监测点空气相对湿度 | % |
| BX02_Light | BX02_光照 | Light intensity at monitoring point 02 / 02号监测点光照强度 | lux |
| BX02_CO2 | BX02_CO2 | Carbon dioxide concentration at monitoring point 02 / 02号监测点二氧化碳浓度 | ppm |
| BX02_O2 | BX02_O2 | Oxygen concentration at monitoring point 02 / 02号监测点氧气浓度 | % |
| BX02_Noise | BX02_噪声 | Noise level at monitoring point 02 / 02号监测点噪声值 | dB |
| BX02_PM2.5 | BX02_PM2.5 | PM2.5 concentration at monitoring point 02 / 02号监测点PM2.5浓度 | μg/m³ |
| BX02_PM10 | BX02_PM10 | PM10 concentration at monitoring point 02 / 02号监测点PM10浓度 | μg/m³ |

---

### 3. Outdoor Meteorology / 室外气象

| Field Name / 字段名 | Chinese / 中文 | Description / 说明 | Unit / 单位 |
|-------------------|---------------|-------------------|------------|
| Wind_Speed | 风速 | Outdoor wind speed / 室外风速 | m/s |
| Wind_Direction | 风向 | Outdoor wind direction (0-360°) / 室外风向（0-360度） | ° |
| Atmospheric_Pressure | 大气压 | Outdoor atmospheric pressure / 室外大气压强 | hPa |

---

### 4. Soil Monitoring (Soil Sensor) / 土壤监测（土壤传感器）

**SS01 / SS02 / SS03**: Three multi-point soil monitoring stations / 三组多点位土壤监测站

| Field Name / 字段名 | Chinese / 中文 | Description / 说明 | Unit / 单位 |
|-------------------|---------------|-------------------|------------|
| SS01_Soil_Temperature | SS01_土壤温度 | Soil temperature at monitoring point 01 / 01号监测点土壤温度 | ℃ |
| SS01_Soil_Humidity | SS01_土壤湿度 | Soil moisture content at monitoring point 01 / 01号监测点土壤含水量 | % |
| SS01_PH | SS01_PH | Soil pH value at monitoring point 01 / 01号监测点土壤酸碱度 | pH |
| SS01_EC | SS01_电导率 | Soil electrical conductivity at monitoring point 01 / 01号监测点土壤电导率 | μS/cm |
| SS01_Nitrogen | SS01_氮 | Soil nitrogen content at monitoring point 01 / 01号监测点土壤氮含量 | mg/kg |
| SS01_Phosphorus | SS01_磷 | Soil phosphorus content at monitoring point 01 / 01号监测点土壤磷含量 | mg/kg |
| SS01_Potassium | SS01_钾 | Soil potassium content at monitoring point 01 / 01号监测点土壤钾含量 | mg/kg |
| SS02_Soil_Temperature | SS02_土壤温度 | Soil temperature at monitoring point 02 / 02号监测点土壤温度 | ℃ |
| SS02_Soil_Humidity | SS02_土壤湿度 | Soil moisture content at monitoring point 02 / 02号监测点土壤含水量 | % |
| SS02_PH | SS02_PH | Soil pH value at monitoring point 02 / 02号监测点土壤酸碱度 | pH |
| SS02_EC | SS02_电导率 | Soil electrical conductivity at monitoring point 02 / 02号监测点土壤电导率 | μS/cm |
| SS02_Nitrogen | SS02_氮 | Soil nitrogen content at monitoring point 02 / 02号监测点土壤氮含量 | mg/kg |
| SS02_Phosphorus | SS02_磷 | Soil phosphorus content at monitoring point 02 / 02号监测点土壤磷含量 | mg/kg |
| SS02_Potassium | SS02_钾 | Soil potassium content at monitoring point 02 / 02号监测点土壤钾含量 | mg/kg |
| SS03_Soil_Temperature | SS03_土壤温度 | Soil temperature at monitoring point 03 / 03号监测点土壤温度 | ℃ |
| SS03_Soil_Humidity | SS03_土壤湿度 | Soil moisture content at monitoring point 03 / 03号监测点土壤含水量 | % |
| SS03_PH | SS03_PH | Soil pH value at monitoring point 03 / 03号监测点土壤酸碱度 | pH |
| SS03_EC | SS03_电导率 | Soil electrical conductivity at monitoring point 03 / 03号监测点土壤电导率 | μS/cm |
| SS03_Nitrogen | SS03_氮 | Soil nitrogen content at monitoring point 03 / 03号监测点土壤氮含量 | mg/kg |
| SS03_Phosphorus | SS03_磷 | Soil phosphorus content at monitoring point 03 / 03号监测点土壤磷含量 | mg/kg |
| SS03_Potassium | SS03_钾 | Soil potassium content at monitoring point 03 / 03号监测点土壤钾含量 | mg/kg |

---

### 5. Gas Emission Monitoring / 气体排放监测

**EM01 / EM02**: Two trace gas monitoring points / 双点位微量气体监测

| Field Name / 字段名 | Chinese / 中文 | Description / 说明 | Unit / 单位 |
|-------------------|---------------|-------------------|------------|
| EM01_C2H4 | EM01_C2H4 | Ethylene concentration at monitoring point 01 / 01号监测点乙烯浓度 | ppm |
| EM01_NH3 | EM01_NH3 | Ammonia concentration at monitoring point 01 / 01号监测点氨气浓度 | ppm |
| EM01_H2S | EM01_H2S | Hydrogen sulfide concentration at monitoring point 01 / 01号监测点硫化氢浓度 | ppm |
| EM01_CH4 | EM01_CH4 | Methane concentration at monitoring point 01 / 01号监测点甲烷浓度 | ppm |
| EM02_C2H4 | EM02_C2H4 | Ethylene concentration at monitoring point 02 / 02号监测点乙烯浓度 | ppm |
| EM02_NH3 | EM02_NH3 | Ammonia concentration at monitoring point 02 / 02号监测点氨气浓度 | ppm |
| EM02_H2S | EM02_H2S | Hydrogen sulfide concentration at monitoring point 02 / 02号监测点硫化氢浓度 | ppm |
| EM02_CH4 | EM02_CH4 | Methane concentration at monitoring point 02 / 02号监测点甲烷浓度 | ppm |

---

### 6. Equipment Status / 设施设备状态

| Field Name / 字段名 | Chinese / 中文 | Description / 说明 | Values / 取值 |
|-------------------|---------------|-------------------|--------------|
| Water_Pump_Status | 水泵状态 | Irrigation water pump running status / 灌溉水泵运行状态 | 0=Off/关闭, 1=On/开启 |
| Ventilation_Fan_Status | 通风风扇状态 | Greenhouse ventilation fan status / 大棚通风风扇状态 | 0=Off/关闭, 1=On/开启 |
| Grow_Light_Status | 补光灯状态 | Supplementary grow light status / 植物补光灯状态 | 0=Off/关闭, 1=On/开启 |
| Solenoid_Valve_Status | 电磁阀状态 | Irrigation solenoid valve status / 灌溉电磁阀状态 | 0=Off/关闭, 1=On/开启 |
| Roller_Shutter_Status | 卷帘机状态 | Greenhouse roller shutter status / 大棚卷帘机状态 | 0=Off/停止, 1=Running/运行 |

---

### 7. Growth Stage Labels / 生长阶段标签

| Field Name / 字段名 | Chinese / 中文 | Description / 说明 |
|-------------------|---------------|-------------------|
| growth_stage | 生长阶段 | Strawberry growth period label / 草莓生长周期标签 |

**Growth Stage Values / 生长阶段取值：**

| English / 英文 | Chinese / 中文 | Description / 说明 |
|---------------|---------------|-------------------|
| Transplanting Stage | 定植期 | Seedling transplanting and rooting phase / 幼苗移栽定植生根阶段 |
| Vegetative Growth Stage | 营养生长期 | Leaf and stem growth phase / 茎叶营养生长阶段 |
| Flower Bud Differentiation Stage | 花芽分化期 | Flower bud formation phase / 花芽形成分化阶段 |
| Flowering Stage | 开花期 | Flower blooming phase / 开花绽放阶段 |
| Early Fruiting Stage | 结果初期 | Early fruit development phase / 果实初期发育阶段 |
| Full Fruiting Stage | 盛果期 | Peak fruit production phase / 果实盛产期 |
| Late Harvest Stage | 采收后期 | Late harvest and senescence phase / 采收后期与衰老阶段 |

---

### 8. Remarks / 备注信息

| Field Name / 字段名 | Chinese / 中文 | Description / 说明 |
|-------------------|---------------|-------------------|
| remark | 备注 | Special event notes and anomaly records / 特殊事件说明与异常记录 |

**Common Remark Values / 常见备注取值：**

| English / 英文 | Chinese / 中文 | Description / 说明 |
|---------------|---------------|-------------------|
| Autumn high temperature, greenhouse temperature rises to 33℃ | 秋季高温，大棚温度升至33℃ | High temperature weather event / 高温天气事件 |
| Continuous rain, light drops sharply, humidity rises to 95% | 连续阴雨，光照骤降，湿度升至95% | Continuous rainy weather event / 连续阴雨天气事件 |
| Cold wave hits, nighttime temperature drops to 2℃ | 寒潮来袭，夜间温度降至2℃ | Cold wave weather event / 寒潮天气事件 |
| Snowy weather, extremely low light | 降雪天气，光照极低 | Snowfall weather event / 降雪天气事件 |
| Topdressing operation, NH3 briefly increases | 追肥作业，NH3短暂升高 | Fertilization operation event / 追肥作业事件 |
| Late spring cold snap, temperature drops sharply to 1℃ | 倒春寒，温度骤降至1℃ | Late spring cold snap event / 倒春寒天气事件 |
| SS-02 soil sensor malfunction | SS-02土壤传感器故障 | Equipment failure record / 设备故障记录 |

---

## Sensor Naming Convention / 传感器命名规则

| Prefix / 前缀 | Full Name / 全称 | Chinese / 中文 | Category / 类别 |
|--------------|-----------------|---------------|----------------|
| BX | Box Sensor | 箱式传感器 | Indoor environment / 室内环境 |
| SS | Soil Sensor | 土壤传感器 | Soil monitoring / 土壤监测 |
| EM | Emission Sensor | 排放传感器 | Gas monitoring / 气体监测 |

---

## Data Usage / 数据用途

- Smart agriculture environmental regulation / 智慧农业环境调控
- Crop growth model training / 作物生长模型训练
- Environmental factor correlation analysis / 环境因子相关性分析
- Equipment operation efficiency optimization / 设备运行效率优化
- Anomaly detection and early warning / 异常检测与预警
- Agricultural IoT algorithm verification / 农业物联网算法验证
