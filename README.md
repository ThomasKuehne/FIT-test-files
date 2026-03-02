# FIT test files

This is a corpus of Flexible and Interoperable Data Transfer ([FIT](https://developer.garmin.com/fit/overview/)) Protocol files to support interoperability testing of FIT file decoding, parsing, analysing and visualization.

FIT files are a data file format used by - among others - [COROS](https://coros.com/), [Garmin](https://www.garmin.com/), [Suunto](https://www.suunto.com/), [Zwift](https://www.zwift.com/) and [Wahoo](https://wahoofitness.com/) for sharing health, fitness and sport data.

[AllFitMessageTypes.fit](AllFitMessageTypes.fit) is a synthetic test vector that contains at least one example of each FIT message supported by the [Garmin - FIT C# SDK](https://github.com/garmin/fit-csharp-sdk).

## activity examples

| [Sport](https://developer.garmin.com/connect-iq/api-docs/Toybox/Activity.html#Sport-module) | [Subsport](https://developer.garmin.com/connect-iq/api-docs/Toybox/Activity.html#SubSport-module) | sample FIT file |
| ---: | ---: | :--- |
|   0 |   0 | [generic](Activity/2022/Activity_20220806_000_000_Generic_Fenix5Plus_42b466c5fd0115ae3dfe373cc134ba3f.fit) |
|   0 |  15 | [elliptical](Activity/2018/Activity_20180113_000_015_Elliptical_Fenix3Hr_f5b51a4c7ad45cedcaefea6fe076b126.fit) |
|   0 |  18 | [open water](Activity/2014/Activity_20140118_000_018_Open-Water_Fr310xt_3d912d931e795fe047986ebc1012a1f9.fit) |
|   1 |   0 | [running](Activity/2026/Activity_20260208_001_000_Running_Fenix7x_31f85d1ad3c4bb3dd3e786abe9fd651a.fit) |
|   1 |   1 | [running / treadmill](Activity/2023/Activity_20231205_001_001_Running_Treadmill_Fenix7x_96a02d9fe4ae9518cb3932907f8b8465.fit) |
|   1 |   2 | [running / street](Activity/2025/Activity_20250410_001_002_Running_Street_Nike_1794463148babf53fb33b260a19a91fe.fit) |
|   1 |   3 | [running / trail](Activity/2026/Activity_20260215_001_003_Running_Trail_Fenix7x_a790a6293770eda5fbd090ebfe8203b6.fit) |
|   1 |   4 | [running / track](Activity/2021/Activity_20210610_001_004_Running_Track_Fenix6_73dac73ee893e107be67b2cebb617e45.fit) |
|   1 |  45 | [running / indoor running](Activity/2022/Activity_20221213_001_045_Running_Indoor-Running_Watch6,18_f210d4280842997b50d2fd0705b9eb5c.fit) |
|   1 |  58 | [running / virtual activity](Activity/2022/Activity_20220217_001_058_Running_Virtual-Activity_Zwift_e6aa5b5c230e0846bb2231adc47018eb.fit) |
|   2 |   0 | [cycling](Activity/2025/Activity_20251119_002_000_Cycling_Karoo-2_f596048b2f0e5f2f73f6b10e8cedca16.fit) |
|   2 |   6 | [cycling / indoor cycling](Activity/2025/Activity_20251213_002_006_Cycling_Indoor-Cycling_Wattbike_e1cfeba6f1bfb55842f3a0374edb8d34.fit) |
|   2 |   7 | [cycling / road](Activity/2026/Activity_20260217_002_007_Cycling_Road_Edge1050_7941c9691ae19ad740a6673e95ea837d.fit) |
|   2 |   8 | [cycling / mountain](Activity/2026/Activity_20260114_002_008_Cycling_Mountain_EdgeMtb_da6a5e2deec8f950a983c0dd81ab28c0.fit) |
|   2 |  46 | [cycling / gravel cycling](Activity/2025/Activity_20250629_002_046_Cycling_Gravel-Cycling_EdgeExplore2_f1035fbf1c9b4dd03ca3a24b05ff81fe.fit) |
|   2 |  47 | [cycling / e-bike mountain](Activity/2026/Activity_20260203_002_047_Cycling_E-Bike-Mountain_Fenix7ProSolar_668112b50cf680234becf64c39009d6c.fit) |
|   2 |  48 | [cycling / commuting](Activity/2025/Activity_20250525_002_048_Cycling_Commuting_Bryton_5be04daa0b6e535ebb22a12390e3b818.fit) |
|   2 |  58 | [cycling / virtual activity](Activity/2026/Activity_20260222_002_058_Cycling_Virtual-Activity_TrainingPeaks-Virtual_ced33004c3740cf90240e773c746d33d.fit) |
|   2 | 252 | [cycling / ???](Activity/2025/Activity_20251018_002_252_Cycling_YYY_CC600-08166_45b664a4270116e747b057b67d67cbe4.fit) |
|   4 |  14 | [fitness / equipment indoor rowing](Activity/2017/Activity_20170518_004_014_Fitness-Equipment_Indoor-Rowing_VivoActiveHr_94dbffeb8be296bb39027edc041a2963.fit) |
|   5 |   0 | [swimming](Activity/2018/Activity_20180324_005_000_Swimming_Fr935_ae9c05519ca8c802f33a8ffd90b15915.fit) |
|   5 |  17 | [swimming / lap swimming](Activity/2026/Activity_20250224_005_017_Swimming_Lap-Swimming_Fenix6x_e7bd1e42e76b937ad3e30a1c3110ab58.fit) |
|   5 |  18 | [swimming / open water](Activity/2024/Activity_20240831_005_018_Swimming_Open-Water_Fenix3Hr_3fd1baf9c1fda907fcd2078dfa0df3ad.fit) |
|  10 |  20 | [training / strength training](Activity/2025/Activity_20251025_010_020_Training_Strength-Training_Fr965_c848261f4fa519263b36032d31131b6f.fit) |
|  10 |  26 | [training / cardio training](Activity/2023/Activity_20230719_010_026_Training_Cardio-Training_Fenix5Plus_51389637b6f92316d95b9a855a2366cd.fit) |
|  10 |  43 | [training / yoga](Activity/2023/Activity_20230929_010_043_Training_Yoga_Fenix6x_815ca8641be748193ae4e97a267c1074.fit) |
|  10 |  62 | [training / breathing](Activity/2023/Activity_20231213_010_062_Training_Breathing_Fenix7x_d3d4d3c9e95a9cf3508b57987775308b.fit) |
|  11 |   0 | [walking](Activity/2023/Activity_20230912_011_000_Walking_Fr645m_9e6e9614db368ac380c10214cf8b38ac.fit) |
|  11 |  27 | [walking / indoor walking](Activity/2025/Activity_20250630_011_027_Walking_Indoor-Walking_Venu2s_f653113e1454e350d171aa3a3809b2a9.fit) |
|  12 |   0 | [cross / country-skiing](Activity/2020/Activity_20200114_012_000_Cross-Country-Skiing_Fenix3_7c44cb53ce1ab36dccfd10a53a828de5.fit) |
|  15 |   0 | [rowing](Activity/2022/Activity_20221211_015_000_Rowing_Watch5,9_1740829541f656f0ee0ba5e9ba6bfa50.fit) |
|  15 |  14 | [rowing / indoor-rowing](Activity/2022/Activity_20221211_015_014_Rowing_Indoor-Rowing_Fr945_7041dc177c9c718831419fb58a63dc4c.fit) |
|  17 |   0 | [hiking](Activity/2022/Activity_20220406_017_000_Hiking_Fenix7_f84ddb27c8203ed7aaa4b0b87447974b.fit) |
|  17 |   3 | [hiking / trail](Activity/2023/Activity_20230610_017_003_Hiking_Trail_Suunto-Vertical_d149673ba8d0667bef7a9fb68d91925d.fit) |
|  21 |     | [e-biking](Activity/2026/Activity_20250308_021_E-Biking_Strava_643851414007e5b3640367bacdd555b5.fit) |
|  37 |   0 | [stand up paddleboarding](Activity/2022/Activity_20220815_037_000_Stand-Up-Paddleboarding_Development_626641cac7ead3606a9af17b87e35d54.fit) |
|  43 |     | [windsurfing](Activity/2022/Activity_20220913_043_Windsurfing_COROS-VERTIX_46e02a470a9dd63fdd28aa24aad832fc.fit) |
|  52 |   0 | [stopwatch](Activity/2023/Activity_20230722_052_000_Stopwatch_Fenix5Plus_3739f4bb7e630179d278cc446f94664a.fit) |
|  53 |     | [diving](Activity/2024/Activity_20241016_053_Diving_Suunto-Ocean_7472453235dff1e64fb193d64f7efacd.fit) |
|  53 |  53 | [diving / single gas diving](Activity/2022/Activity_20220918_053_053_Diving_Single-Gas-Diving_Descent_5915616601537b7b33ac78a29c33685d.fit) |
|  53 |  54 | [diving / multi gas diving](Activity/2023/Activity_20231122_053_054_Diving_Multi-Gas-Diving_DescentMk2_9e6310d95e5fb06878b67ccee5f902a8.fit) |
|  53 |  56 | [diving / apnea diving](Activity/2024/Activity_20241230_053_056_Diving_Apnea-Diving_DescentMk2s_f17834965665d419f67604d779f85a03.fit) |
|  53 |  63 | [diving / CCR diving](Activity/2023/Activity_20231020_053_063_Diving_Ccr-Diving_Descent_4d6bfacaa18ba0a392cd05c5312142a6.fit) |
|  75 |   0 | [volleyball](Activity/2025/Activity_20250930_075_000_Volleyball_Fr965_59dfb83b97f9a5786c466d13a8b3de9e.fit) |
|  80 |   0 | [mixed martial art](Activity/2025/Activity_20250907_080_000_Mixed-Martial-Art_Development_0e421dab676538e970fcda617266e883.fit) |
|  80 |  70 | [mixed martial art / HIIT](Activity/2025/Activity_20250907_080_070_Mixed-Martial-Art_Hiit_Development_ac03c7377d27d0770fd6828c3f0d4cdb.fit) |
|  82 |     | [snorkeling](Activity/2025/Activity_20250827_082_Snorkeling_Suunto-Vertical-2_d055fea983a3830a0f2ddbb483358d96.fit) |