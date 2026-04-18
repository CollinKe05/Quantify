(dlec) PS C:\Users\19653\Desktop\嵌赛\Quantify\method\BRECQ> python main_imagenet.py --data_path C:\Users\19653\Desktop\嵌赛\Quantify\data\tiny-imagenet-200 --arch resnet18 --n_bits_w 2 --n_bits_a 4 --act_quant
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
==> Using Pytorch Dataset
Setting the first and the last layer to 8-bit
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
Ignore reconstruction of layer conv1
Reconstruction for block 0
Init alpha to be FP32
Init alpha to be FP32
Total loss:     0.146 (rec:0.146, round:0.000)  b=0.00  count=500
Total loss:     0.089 (rec:0.089, round:0.000)  b=0.00  count=1000
Total loss:     0.069 (rec:0.069, round:0.000)  b=0.00  count=1500
Total loss:     0.056 (rec:0.056, round:0.000)  b=0.00  count=2000
Total loss:     0.051 (rec:0.051, round:0.000)  b=0.00  count=2500
Total loss:     0.040 (rec:0.040, round:0.000)  b=0.00  count=3000
Total loss:     0.037 (rec:0.037, round:0.000)  b=0.00  count=3500
Total loss:     637.329 (rec:0.039, round:637.290)      b=20.00 count=4000
Total loss:     322.788 (rec:0.037, round:322.751)      b=19.44 count=4500
Total loss:     296.975 (rec:0.043, round:296.932)      b=18.88 count=5000
Total loss:     279.231 (rec:0.035, round:279.196)      b=18.31 count=5500
Total loss:     265.805 (rec:0.034, round:265.771)      b=17.75 count=6000
Total loss:     253.048 (rec:0.031, round:253.017)      b=17.19 count=6500
Total loss:     242.060 (rec:0.032, round:242.029)      b=16.62 count=7000
Total loss:     231.103 (rec:0.030, round:231.073)      b=16.06 count=7500
Total loss:     220.017 (rec:0.027, round:219.990)      b=15.50 count=8000
Total loss:     208.829 (rec:0.035, round:208.794)      b=14.94 count=8500
Total loss:     197.544 (rec:0.031, round:197.514)      b=14.38 count=9000
Total loss:     186.213 (rec:0.030, round:186.184)      b=13.81 count=9500
Total loss:     175.746 (rec:0.032, round:175.713)      b=13.25 count=10000
Total loss:     164.817 (rec:0.031, round:164.787)      b=12.69 count=10500
Total loss:     154.915 (rec:0.032, round:154.883)      b=12.12 count=11000
Total loss:     143.867 (rec:0.027, round:143.839)      b=11.56 count=11500
Total loss:     132.376 (rec:0.032, round:132.344)      b=11.00 count=12000
Total loss:     120.653 (rec:0.033, round:120.620)      b=10.44 count=12500
Total loss:     108.857 (rec:0.033, round:108.824)      b=9.88  count=13000
Total loss:     97.522 (rec:0.035, round:97.487)        b=9.31  count=13500
Total loss:     85.523 (rec:0.034, round:85.489)        b=8.75  count=14000
Total loss:     73.653 (rec:0.038, round:73.615)        b=8.19  count=14500
Total loss:     60.900 (rec:0.041, round:60.860)        b=7.62  count=15000
Total loss:     48.710 (rec:0.042, round:48.668)        b=7.06  count=15500
Total loss:     36.828 (rec:0.046, round:36.783)        b=6.50  count=16000
Total loss:     26.059 (rec:0.056, round:26.003)        b=5.94  count=16500
Total loss:     16.804 (rec:0.067, round:16.736)        b=5.38  count=17000
Total loss:     9.352 (rec:0.066, round:9.286)  b=4.81  count=17500
Total loss:     4.128 (rec:0.069, round:4.059)  b=4.25  count=18000
Total loss:     1.202 (rec:0.095, round:1.107)  b=3.69  count=18500
Total loss:     0.218 (rec:0.101, round:0.117)  b=3.12  count=19000
Total loss:     0.106 (rec:0.098, round:0.007)  b=2.56  count=19500
Total loss:     0.099 (rec:0.099, round:0.000)  b=2.00  count=20000
Reconstruction for block 1
Init alpha to be FP32
Init alpha to be FP32
Total loss:     0.362 (rec:0.362, round:0.000)  b=0.00  count=500
Total loss:     0.267 (rec:0.267, round:0.000)  b=0.00  count=1000
Total loss:     0.215 (rec:0.215, round:0.000)  b=0.00  count=1500
Total loss:     0.195 (rec:0.195, round:0.000)  b=0.00  count=2000
Total loss:     0.194 (rec:0.194, round:0.000)  b=0.00  count=2500
Total loss:     0.169 (rec:0.169, round:0.000)  b=0.00  count=3000
Total loss:     0.172 (rec:0.172, round:0.000)  b=0.00  count=3500
Total loss:     657.057 (rec:0.161, round:656.896)      b=20.00 count=4000
Total loss:     369.345 (rec:0.170, round:369.175)      b=19.44 count=4500
Total loss:     340.784 (rec:0.162, round:340.622)      b=18.88 count=5000
Total loss:     321.968 (rec:0.166, round:321.802)      b=18.31 count=5500
Total loss:     305.235 (rec:0.138, round:305.097)      b=17.75 count=6000
Total loss:     290.863 (rec:0.158, round:290.705)      b=17.19 count=6500
Total loss:     277.171 (rec:0.158, round:277.013)      b=16.62 count=7000
Total loss:     264.912 (rec:0.169, round:264.743)      b=16.06 count=7500
Total loss:     252.356 (rec:0.143, round:252.212)      b=15.50 count=8000
Total loss:     240.567 (rec:0.151, round:240.416)      b=14.94 count=8500
Total loss:     228.255 (rec:0.151, round:228.104)      b=14.38 count=9000
Total loss:     216.076 (rec:0.148, round:215.928)      b=13.81 count=9500
Total loss:     204.230 (rec:0.136, round:204.094)      b=13.25 count=10000
Total loss:     191.959 (rec:0.131, round:191.828)      b=12.69 count=10500
Total loss:     179.966 (rec:0.168, round:179.797)      b=12.12 count=11000
Total loss:     167.908 (rec:0.140, round:167.768)      b=11.56 count=11500
Total loss:     155.315 (rec:0.172, round:155.143)      b=11.00 count=12000
Total loss:     142.557 (rec:0.127, round:142.430)      b=10.44 count=12500
Total loss:     128.944 (rec:0.163, round:128.781)      b=9.88  count=13000
Total loss:     114.633 (rec:0.180, round:114.452)      b=9.31  count=13500
Total loss:     101.279 (rec:0.161, round:101.118)      b=8.75  count=14000
Total loss:     87.280 (rec:0.174, round:87.106)        b=8.19  count=14500
Total loss:     73.172 (rec:0.183, round:72.989)        b=7.62  count=15000
Total loss:     59.107 (rec:0.195, round:58.913)        b=7.06  count=15500
Total loss:     44.629 (rec:0.220, round:44.410)        b=6.50  count=16000
Total loss:     30.889 (rec:0.195, round:30.694)        b=5.94  count=16500
Total loss:     19.467 (rec:0.213, round:19.255)        b=5.38  count=17000
Total loss:     10.137 (rec:0.227, round:9.910) b=4.81  count=17500
Total loss:     4.229 (rec:0.241, round:3.988)  b=4.25  count=18000
Total loss:     1.346 (rec:0.260, round:1.085)  b=3.69  count=18500
Total loss:     0.377 (rec:0.248, round:0.129)  b=3.12  count=19000
Total loss:     0.226 (rec:0.219, round:0.007)  b=2.56  count=19500
Total loss:     0.232 (rec:0.232, round:0.000)  b=2.00  count=20000
Reconstruction for block 0
Init alpha to be FP32
Init alpha to be FP32
Init alpha to be FP32
Total loss:     0.205 (rec:0.205, round:0.000)  b=0.00  count=500
Total loss:     0.178 (rec:0.178, round:0.000)  b=0.00  count=1000
Total loss:     0.154 (rec:0.154, round:0.000)  b=0.00  count=1500
Total loss:     0.137 (rec:0.137, round:0.000)  b=0.00  count=2000
Total loss:     0.145 (rec:0.145, round:0.000)  b=0.00  count=2500
Total loss:     0.121 (rec:0.121, round:0.000)  b=0.00  count=3000
Total loss:     0.126 (rec:0.126, round:0.000)  b=0.00  count=3500
Total loss:     2051.505 (rec:0.116, round:2051.389)    b=20.00 count=4000
Total loss:     1004.596 (rec:0.155, round:1004.441)    b=19.44 count=4500
Total loss:     913.941 (rec:0.130, round:913.811)      b=18.88 count=5000
Total loss:     857.031 (rec:0.140, round:856.891)      b=18.31 count=5500
Total loss:     811.774 (rec:0.130, round:811.644)      b=17.75 count=6000
Total loss:     770.645 (rec:0.141, round:770.504)      b=17.19 count=6500
Total loss:     732.144 (rec:0.125, round:732.019)      b=16.62 count=7000
Total loss:     695.996 (rec:0.132, round:695.863)      b=16.06 count=7500
Total loss:     660.417 (rec:0.148, round:660.269)      b=15.50 count=8000
Total loss:     626.719 (rec:0.143, round:626.576)      b=14.94 count=8500
Total loss:     593.620 (rec:0.142, round:593.478)      b=14.38 count=9000
Total loss:     559.218 (rec:0.148, round:559.070)      b=13.81 count=9500
Total loss:     524.882 (rec:0.148, round:524.734)      b=13.25 count=10000
Total loss:     491.007 (rec:0.145, round:490.862)      b=12.69 count=10500
Total loss:     456.143 (rec:0.154, round:455.989)      b=12.12 count=11000
Total loss:     420.974 (rec:0.155, round:420.819)      b=11.56 count=11500
Total loss:     383.433 (rec:0.151, round:383.282)      b=11.00 count=12000
Total loss:     346.689 (rec:0.160, round:346.529)      b=10.44 count=12500
Total loss:     308.209 (rec:0.154, round:308.054)      b=9.88  count=13000
Total loss:     269.295 (rec:0.174, round:269.121)      b=9.31  count=13500
Total loss:     229.852 (rec:0.184, round:229.668)      b=8.75  count=14000
Total loss:     189.533 (rec:0.181, round:189.352)      b=8.19  count=14500
Total loss:     149.388 (rec:0.195, round:149.193)      b=7.62  count=15000
Total loss:     112.040 (rec:0.213, round:111.827)      b=7.06  count=15500
Total loss:     78.046 (rec:0.208, round:77.838)        b=6.50  count=16000
Total loss:     48.950 (rec:0.217, round:48.733)        b=5.94  count=16500
Total loss:     26.989 (rec:0.247, round:26.742)        b=5.38  count=17000
Total loss:     12.005 (rec:0.227, round:11.778)        b=4.81  count=17500
Total loss:     3.822 (rec:0.268, round:3.555)  b=4.25  count=18000
Total loss:     0.931 (rec:0.281, round:0.650)  b=3.69  count=18500
Total loss:     0.390 (rec:0.302, round:0.088)  b=3.12  count=19000
Total loss:     0.302 (rec:0.290, round:0.012)  b=2.56  count=19500
Total loss:     0.292 (rec:0.292, round:0.000)  b=2.00  count=20000
Reconstruction for block 1
Init alpha to be FP32
Init alpha to be FP32
Total loss:     0.439 (rec:0.439, round:0.000)  b=0.00  count=500
Total loss:     0.375 (rec:0.375, round:0.000)  b=0.00  count=1000
Total loss:     0.340 (rec:0.340, round:0.000)  b=0.00  count=1500
Total loss:     0.337 (rec:0.337, round:0.000)  b=0.00  count=2000
Total loss:     0.336 (rec:0.336, round:0.000)  b=0.00  count=2500
Total loss:     0.336 (rec:0.336, round:0.000)  b=0.00  count=3000
Total loss:     0.329 (rec:0.329, round:0.000)  b=0.00  count=3500
Total loss:     2633.510 (rec:0.337, round:2633.173)    b=20.00 count=4000
Total loss:     1226.959 (rec:0.381, round:1226.578)    b=19.44 count=4500
Total loss:     1120.861 (rec:0.352, round:1120.509)    b=18.88 count=5000
Total loss:     1055.986 (rec:0.365, round:1055.622)    b=18.31 count=5500
Total loss:     1005.933 (rec:0.352, round:1005.582)    b=17.75 count=6000
Total loss:     961.623 (rec:0.348, round:961.275)      b=17.19 count=6500
Total loss:     920.223 (rec:0.345, round:919.878)      b=16.62 count=7000
Total loss:     880.551 (rec:0.363, round:880.188)      b=16.06 count=7500
Total loss:     841.623 (rec:0.347, round:841.276)      b=15.50 count=8000
Total loss:     805.086 (rec:0.384, round:804.703)      b=14.94 count=8500
Total loss:     767.717 (rec:0.368, round:767.349)      b=14.38 count=9000
Total loss:     730.991 (rec:0.377, round:730.614)      b=13.81 count=9500
Total loss:     694.435 (rec:0.345, round:694.089)      b=13.25 count=10000
Total loss:     656.505 (rec:0.359, round:656.146)      b=12.69 count=10500
Total loss:     617.955 (rec:0.354, round:617.601)      b=12.12 count=11000
Total loss:     578.529 (rec:0.399, round:578.130)      b=11.56 count=11500
Total loss:     537.390 (rec:0.411, round:536.979)      b=11.00 count=12000
Total loss:     494.335 (rec:0.396, round:493.939)      b=10.44 count=12500
Total loss:     448.972 (rec:0.425, round:448.547)      b=9.88  count=13000
Total loss:     402.821 (rec:0.450, round:402.372)      b=9.31  count=13500
Total loss:     353.231 (rec:0.369, round:352.862)      b=8.75  count=14000
Total loss:     302.805 (rec:0.411, round:302.395)      b=8.19  count=14500
Total loss:     249.554 (rec:0.413, round:249.142)      b=7.62  count=15000
Total loss:     195.826 (rec:0.436, round:195.390)      b=7.06  count=15500
Total loss:     143.293 (rec:0.442, round:142.851)      b=6.50  count=16000
Total loss:     94.745 (rec:0.481, round:94.264)        b=5.94  count=16500
Total loss:     54.346 (rec:0.505, round:53.841)        b=5.38  count=17000
Total loss:     23.853 (rec:0.510, round:23.343)        b=4.81  count=17500
Total loss:     7.183 (rec:0.512, round:6.671)  b=4.25  count=18000
Total loss:     1.806 (rec:0.505, round:1.301)  b=3.69  count=18500
Total loss:     0.650 (rec:0.495, round:0.156)  b=3.12  count=19000
Total loss:     0.574 (rec:0.557, round:0.017)  b=2.56  count=19500
Total loss:     0.573 (rec:0.571, round:0.001)  b=2.00  count=20000
Reconstruction for block 0
Init alpha to be FP32
Init alpha to be FP32
Init alpha to be FP32
Total loss:     0.317 (rec:0.317, round:0.000)  b=0.00  count=500
Total loss:     0.281 (rec:0.281, round:0.000)  b=0.00  count=1000
Total loss:     0.262 (rec:0.262, round:0.000)  b=0.00  count=1500
Total loss:     0.233 (rec:0.233, round:0.000)  b=0.00  count=2000
Total loss:     0.248 (rec:0.248, round:0.000)  b=0.00  count=2500
Total loss:     0.246 (rec:0.246, round:0.000)  b=0.00  count=3000
Total loss:     0.223 (rec:0.223, round:0.000)  b=0.00  count=3500
Total loss:     8261.865 (rec:0.206, round:8261.659)    b=20.00 count=4000
Total loss:     3537.431 (rec:0.295, round:3537.135)    b=19.44 count=4500
Total loss:     3232.976 (rec:0.275, round:3232.700)    b=18.88 count=5000
Total loss:     3054.615 (rec:0.277, round:3054.338)    b=18.31 count=5500
Total loss:     2916.899 (rec:0.278, round:2916.621)    b=17.75 count=6000
Total loss:     2795.794 (rec:0.289, round:2795.505)    b=17.19 count=6500
Total loss:     2686.222 (rec:0.285, round:2685.937)    b=16.62 count=7000
Total loss:     2580.237 (rec:0.265, round:2579.972)    b=16.06 count=7500
Total loss:     2477.688 (rec:0.298, round:2477.390)    b=15.50 count=8000
Total loss:     2375.606 (rec:0.272, round:2375.334)    b=14.94 count=8500
Total loss:     2272.698 (rec:0.275, round:2272.424)    b=14.38 count=9000
Total loss:     2170.576 (rec:0.295, round:2170.281)    b=13.81 count=9500
Total loss:     2065.704 (rec:0.293, round:2065.411)    b=13.25 count=10000
Total loss:     1959.658 (rec:0.304, round:1959.354)    b=12.69 count=10500
Total loss:     1848.951 (rec:0.304, round:1848.646)    b=12.12 count=11000
Total loss:     1734.037 (rec:0.318, round:1733.719)    b=11.56 count=11500
Total loss:     1615.813 (rec:0.330, round:1615.483)    b=11.00 count=12000
Total loss:     1492.465 (rec:0.342, round:1492.123)    b=10.44 count=12500
Total loss:     1365.206 (rec:0.331, round:1364.876)    b=9.88  count=13000
Total loss:     1230.505 (rec:0.324, round:1230.182)    b=9.31  count=13500
Total loss:     1087.885 (rec:0.352, round:1087.532)    b=8.75  count=14000
Total loss:     941.486 (rec:0.353, round:941.134)      b=8.19  count=14500
Total loss:     788.934 (rec:0.346, round:788.588)      b=7.62  count=15000
Total loss:     634.060 (rec:0.363, round:633.697)      b=7.06  count=15500
Total loss:     478.812 (rec:0.397, round:478.415)      b=6.50  count=16000
Total loss:     328.403 (rec:0.397, round:328.006)      b=5.94  count=16500
Total loss:     193.826 (rec:0.416, round:193.410)      b=5.38  count=17000
Total loss:     87.253 (rec:0.409, round:86.843)        b=4.81  count=17500
Total loss:     21.975 (rec:0.448, round:21.527)        b=4.25  count=18000
Total loss:     2.946 (rec:0.471, round:2.475)  b=3.69  count=18500
Total loss:     0.592 (rec:0.444, round:0.147)  b=3.12  count=19000
Total loss:     0.514 (rec:0.509, round:0.005)  b=2.56  count=19500
Total loss:     0.431 (rec:0.431, round:0.000)  b=2.00  count=20000
Reconstruction for block 1
Init alpha to be FP32
Init alpha to be FP32
Total loss:     0.556 (rec:0.556, round:0.000)  b=0.00  count=500
Total loss:     0.512 (rec:0.512, round:0.000)  b=0.00  count=1000
Total loss:     0.510 (rec:0.510, round:0.000)  b=0.00  count=1500
Total loss:     0.509 (rec:0.509, round:0.000)  b=0.00  count=2000
Total loss:     0.514 (rec:0.514, round:0.000)  b=0.00  count=2500
Total loss:     0.485 (rec:0.485, round:0.000)  b=0.00  count=3000
Total loss:     0.489 (rec:0.489, round:0.000)  b=0.00  count=3500
Total loss:     10631.352 (rec:0.480, round:10630.871)  b=20.00 count=4000
Total loss:     4679.840 (rec:0.576, round:4679.265)    b=19.44 count=4500
Total loss:     4297.448 (rec:0.522, round:4296.927)    b=18.88 count=5000
Total loss:     4076.740 (rec:0.524, round:4076.216)    b=18.31 count=5500
Total loss:     3905.557 (rec:0.521, round:3905.037)    b=17.75 count=6000
Total loss:     3755.022 (rec:0.566, round:3754.457)    b=17.19 count=6500
Total loss:     3612.685 (rec:0.513, round:3612.171)    b=16.62 count=7000
Total loss:     3477.146 (rec:0.552, round:3476.594)    b=16.06 count=7500
Total loss:     3345.257 (rec:0.498, round:3344.759)    b=15.50 count=8000
Total loss:     3213.654 (rec:0.528, round:3213.126)    b=14.94 count=8500
Total loss:     3083.096 (rec:0.547, round:3082.549)    b=14.38 count=9000
Total loss:     2948.666 (rec:0.560, round:2948.106)    b=13.81 count=9500
Total loss:     2812.114 (rec:0.575, round:2811.539)    b=13.25 count=10000
Total loss:     2672.053 (rec:0.559, round:2671.494)    b=12.69 count=10500
Total loss:     2529.601 (rec:0.551, round:2529.050)    b=12.12 count=11000
Total loss:     2381.927 (rec:0.580, round:2381.347)    b=11.56 count=11500
Total loss:     2229.903 (rec:0.549, round:2229.354)    b=11.00 count=12000
Total loss:     2069.614 (rec:0.577, round:2069.036)    b=10.44 count=12500
Total loss:     1903.226 (rec:0.594, round:1902.632)    b=9.88  count=13000
Total loss:     1730.032 (rec:0.577, round:1729.455)    b=9.31  count=13500
Total loss:     1547.925 (rec:0.627, round:1547.298)    b=8.75  count=14000
Total loss:     1358.389 (rec:0.581, round:1357.809)    b=8.19  count=14500
Total loss:     1165.080 (rec:0.603, round:1164.476)    b=7.62  count=15000
Total loss:     963.175 (rec:0.605, round:962.569)      b=7.06  count=15500
Total loss:     756.402 (rec:0.652, round:755.750)      b=6.50  count=16000
Total loss:     552.517 (rec:0.677, round:551.841)      b=5.94  count=16500
Total loss:     359.326 (rec:0.703, round:358.623)      b=5.38  count=17000
Total loss:     190.006 (rec:0.792, round:189.214)      b=4.81  count=17500
Total loss:     65.868 (rec:0.707, round:65.160)        b=4.25  count=18000
Total loss:     10.982 (rec:0.749, round:10.233)        b=3.69  count=18500
Total loss:     1.265 (rec:0.726, round:0.538)  b=3.12  count=19000
Total loss:     0.789 (rec:0.778, round:0.011)  b=2.56  count=19500
Total loss:     0.762 (rec:0.762, round:0.000)  b=2.00  count=20000
Reconstruction for block 0
Init alpha to be FP32
Init alpha to be FP32
Init alpha to be FP32
Total loss:     0.944 (rec:0.944, round:0.000)  b=0.00  count=500
Total loss:     0.825 (rec:0.825, round:0.000)  b=0.00  count=1000
Total loss:     0.768 (rec:0.768, round:0.000)  b=0.00  count=1500
Total loss:     0.725 (rec:0.725, round:0.000)  b=0.00  count=2000
Total loss:     0.648 (rec:0.648, round:0.000)  b=0.00  count=2500
Total loss:     0.666 (rec:0.666, round:0.000)  b=0.00  count=3000
Total loss:     0.646 (rec:0.646, round:0.000)  b=0.00  count=3500
Total loss:     33897.871 (rec:0.622, round:33897.250)  b=20.00 count=4000
Total loss:     17340.684 (rec:0.671, round:17340.014)  b=19.44 count=4500
Total loss:     16067.346 (rec:0.676, round:16066.670)  b=18.88 count=5000
Total loss:     15262.141 (rec:0.628, round:15261.513)  b=18.31 count=5500
Total loss:     14600.215 (rec:0.614, round:14599.601)  b=17.75 count=6000
Total loss:     13990.996 (rec:0.621, round:13990.375)  b=17.19 count=6500
Total loss:     13411.884 (rec:0.637, round:13411.247)  b=16.62 count=7000
Total loss:     12847.608 (rec:0.566, round:12847.042)  b=16.06 count=7500
Total loss:     12292.755 (rec:0.610, round:12292.145)  b=15.50 count=8000
Total loss:     11739.499 (rec:0.594, round:11738.904)  b=14.94 count=8500
Total loss:     11184.581 (rec:0.597, round:11183.984)  b=14.38 count=9000
Total loss:     10630.855 (rec:0.588, round:10630.268)  b=13.81 count=9500
Total loss:     10068.448 (rec:0.626, round:10067.822)  b=13.25 count=10000
Total loss:     9498.364 (rec:0.607, round:9497.757)    b=12.69 count=10500
Total loss:     8916.977 (rec:0.603, round:8916.373)    b=12.12 count=11000
Total loss:     8324.498 (rec:0.637, round:8323.861)    b=11.56 count=11500
Total loss:     7724.282 (rec:0.634, round:7723.648)    b=11.00 count=12000
Total loss:     7116.312 (rec:0.626, round:7115.687)    b=10.44 count=12500
Total loss:     6492.637 (rec:0.644, round:6491.993)    b=9.88  count=13000
Total loss:     5859.117 (rec:0.654, round:5858.463)    b=9.31  count=13500
Total loss:     5210.260 (rec:0.684, round:5209.576)    b=8.75  count=14000
Total loss:     4549.454 (rec:0.685, round:4548.770)    b=8.19  count=14500
Total loss:     3885.970 (rec:0.708, round:3885.262)    b=7.62  count=15000
Total loss:     3217.326 (rec:0.717, round:3216.608)    b=7.06  count=15500
Total loss:     2556.960 (rec:0.732, round:2556.228)    b=6.50  count=16000
Total loss:     1911.517 (rec:0.780, round:1910.737)    b=5.94  count=16500
Total loss:     1297.085 (rec:0.793, round:1296.292)    b=5.38  count=17000
Total loss:     739.284 (rec:0.808, round:738.476)      b=4.81  count=17500
Total loss:     284.927 (rec:0.900, round:284.027)      b=4.25  count=18000
Total loss:     49.924 (rec:0.915, round:49.008)        b=3.69  count=18500
Total loss:     4.268 (rec:0.966, round:3.302)  b=3.12  count=19000
Total loss:     1.065 (rec:0.932, round:0.132)  b=2.56  count=19500
Total loss:     0.910 (rec:0.907, round:0.003)  b=2.00  count=20000
Reconstruction for block 1
Init alpha to be FP32
Init alpha to be FP32
Total loss:     127.611 (rec:127.611, round:0.000)      b=0.00  count=500
Total loss:     113.070 (rec:113.070, round:0.000)      b=0.00  count=1000
Total loss:     108.545 (rec:108.545, round:0.000)      b=0.00  count=1500
Total loss:     92.663 (rec:92.663, round:0.000)        b=0.00  count=2000
Total loss:     85.889 (rec:85.889, round:0.000)        b=0.00  count=2500
Total loss:     87.300 (rec:87.300, round:0.000)        b=0.00  count=3000
Total loss:     80.851 (rec:80.851, round:0.000)        b=0.00  count=3500
Total loss:     44072.582 (rec:79.144, round:43993.438) b=20.00 count=4000
Total loss:     31823.744 (rec:76.756, round:31746.988) b=19.44 count=4500
Total loss:     29962.893 (rec:70.830, round:29892.062) b=18.88 count=5000
Total loss:     28861.986 (rec:71.822, round:28790.164) b=18.31 count=5500
Total loss:     28000.697 (rec:67.448, round:27933.250) b=17.75 count=6000
Total loss:     27259.203 (rec:69.944, round:27189.260) b=17.19 count=6500
Total loss:     26570.959 (rec:64.775, round:26506.184) b=16.62 count=7000
Total loss:     25916.184 (rec:61.034, round:25855.148) b=16.06 count=7500
Total loss:     25283.865 (rec:59.958, round:25223.906) b=15.50 count=8000
Total loss:     24661.029 (rec:57.205, round:24603.824) b=14.94 count=8500
Total loss:     24048.496 (rec:59.093, round:23989.402) b=14.38 count=9000
Total loss:     23430.049 (rec:61.407, round:23368.643) b=13.81 count=9500
Total loss:     22804.391 (rec:59.306, round:22745.084) b=13.25 count=10000
Total loss:     22167.074 (rec:58.988, round:22108.086) b=12.69 count=10500
Total loss:     21510.801 (rec:55.324, round:21455.477) b=12.12 count=11000
Total loss:     20843.494 (rec:60.427, round:20783.066) b=11.56 count=11500
Total loss:     20145.496 (rec:59.308, round:20086.188) b=11.00 count=12000
Total loss:     19427.871 (rec:57.598, round:19370.273) b=10.44 count=12500
Total loss:     18677.002 (rec:57.983, round:18619.020) b=9.88  count=13000
Total loss:     17890.178 (rec:56.416, round:17833.762) b=9.31  count=13500
Total loss:     17064.094 (rec:62.386, round:17001.707) b=8.75  count=14000
Total loss:     16181.216 (rec:62.411, round:16118.805) b=8.19  count=14500
Total loss:     15238.504 (rec:60.552, round:15177.951) b=7.62  count=15000
Total loss:     14231.708 (rec:63.643, round:14168.064) b=7.06  count=15500
Total loss:     13151.992 (rec:65.311, round:13086.682) b=6.50  count=16000
Total loss:     11982.604 (rec:69.758, round:11912.846) b=5.94  count=16500
Total loss:     10696.765 (rec:67.354, round:10629.410) b=5.38  count=17000
Total loss:     9308.388 (rec:75.343, round:9233.045)   b=4.81  count=17500
Total loss:     7773.773 (rec:80.849, round:7692.925)   b=4.25  count=18000
Total loss:     6105.455 (rec:85.707, round:6019.748)   b=3.69  count=18500
Total loss:     4322.544 (rec:93.095, round:4229.449)   b=3.12  count=19000
Total loss:     2531.946 (rec:104.333, round:2427.614)  b=2.56  count=19500
Total loss:     1089.058 (rec:117.358, round:971.699)   b=2.00  count=20000
Reconstruction for layer fc
Init alpha to be FP32
Total loss:     115.230 (rec:115.230, round:0.000)      b=0.00  count=500
Total loss:     112.934 (rec:112.934, round:0.000)      b=0.00  count=1000
Total loss:     105.712 (rec:105.712, round:0.000)      b=0.00  count=1500
Total loss:     99.275 (rec:99.275, round:0.000)        b=0.00  count=2000
Total loss:     95.370 (rec:95.370, round:0.000)        b=0.00  count=2500
Total loss:     100.158 (rec:100.158, round:0.000)      b=0.00  count=3000
Total loss:     102.349 (rec:102.349, round:0.000)      b=0.00  count=3500
Total loss:     4359.564 (rec:97.733, round:4261.831)   b=20.00 count=4000
Total loss:     2822.701 (rec:100.316, round:2722.385)  b=19.44 count=4500
Total loss:     2583.354 (rec:88.051, round:2495.302)   b=18.88 count=5000
Total loss:     2416.988 (rec:94.221, round:2322.767)   b=18.31 count=5500
Total loss:     2252.607 (rec:88.532, round:2164.076)   b=17.75 count=6000
Total loss:     2105.400 (rec:92.121, round:2013.279)   b=17.19 count=6500
Total loss:     1961.567 (rec:91.583, round:1869.984)   b=16.62 count=7000
Total loss:     1826.726 (rec:91.628, round:1735.097)   b=16.06 count=7500
Total loss:     1698.854 (rec:90.274, round:1608.580)   b=15.50 count=8000
Total loss:     1579.324 (rec:91.300, round:1488.024)   b=14.94 count=8500
Total loss:     1460.480 (rec:85.907, round:1374.573)   b=14.38 count=9000
Total loss:     1357.150 (rec:87.534, round:1269.616)   b=13.81 count=9500
Total loss:     1259.503 (rec:88.986, round:1170.517)   b=13.25 count=10000
Total loss:     1166.763 (rec:88.790, round:1077.973)   b=12.69 count=10500
Total loss:     1088.432 (rec:97.066, round:991.367)    b=12.12 count=11000
Total loss:     996.896 (rec:87.707, round:909.190)     b=11.56 count=11500
Total loss:     923.116 (rec:91.151, round:831.966)     b=11.00 count=12000
Total loss:     850.265 (rec:91.242, round:759.023)     b=10.44 count=12500
Total loss:     777.469 (rec:88.759, round:688.711)     b=9.88  count=13000
Total loss:     711.101 (rec:86.773, round:624.328)     b=9.31  count=13500
Total loss:     650.812 (rec:89.403, round:561.408)     b=8.75  count=14000
Total loss:     589.039 (rec:87.152, round:501.888)     b=8.19  count=14500
Total loss:     536.815 (rec:91.461, round:445.354)     b=7.62  count=15000
Total loss:     488.653 (rec:98.154, round:390.499)     b=7.06  count=15500
Total loss:     427.472 (rec:90.882, round:336.590)     b=6.50  count=16000
Total loss:     371.991 (rec:87.023, round:284.968)     b=5.94  count=16500
Total loss:     327.607 (rec:91.124, round:236.483)     b=5.38  count=17000
Total loss:     279.134 (rec:89.954, round:189.180)     b=4.81  count=17500
Total loss:     228.418 (rec:86.262, round:142.156)     b=4.25  count=18000
Total loss:     187.272 (rec:90.300, round:96.972)      b=3.69  count=18500
Total loss:     144.383 (rec:88.664, round:55.718)      b=3.12  count=19000
Total loss:     113.114 (rec:90.806, round:22.307)      b=2.56  count=19500
Total loss:     92.477 (rec:88.155, round:4.322)        b=2.00  count=20000
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
Test: [  0/157] Time 19.528 (19.528)    Acc@1   0.00 (  0.00)   Acc@5   0.00 (  0.00)
Test: [100/157] Time  0.055 ( 0.254)    Acc@1   0.00 (  0.00)   Acc@5   0.00 (  0.28)
 * Acc@1 0.010 Acc@5 0.340
Weight quantization accuracy: 0.009999999776482582
Ignore reconstruction of layer conv1
Reconstruction for block 0
Total loss:     0.060 (rec:0.060, round:0.000)  b=0.00  count=500
Total loss:     0.054 (rec:0.054, round:0.000)  b=0.00  count=1000
Total loss:     0.056 (rec:0.056, round:0.000)  b=0.00  count=1500
Total loss:     0.052 (rec:0.052, round:0.000)  b=0.00  count=2000
Total loss:     0.056 (rec:0.056, round:0.000)  b=0.00  count=2500
Total loss:     0.057 (rec:0.057, round:0.000)  b=0.00  count=3000
Total loss:     0.057 (rec:0.057, round:0.000)  b=0.00  count=3500
Total loss:     0.054 (rec:0.054, round:0.000)  b=0.00  count=4000
Total loss:     0.057 (rec:0.057, round:0.000)  b=0.00  count=4500
Total loss:     0.056 (rec:0.056, round:0.000)  b=0.00  count=5000
Reconstruction for block 1
Total loss:     0.163 (rec:0.163, round:0.000)  b=0.00  count=500
Total loss:     0.154 (rec:0.154, round:0.000)  b=0.00  count=1000
Total loss:     0.153 (rec:0.153, round:0.000)  b=0.00  count=1500
Total loss:     0.159 (rec:0.159, round:0.000)  b=0.00  count=2000
Total loss:     0.151 (rec:0.151, round:0.000)  b=0.00  count=2500
Total loss:     0.153 (rec:0.153, round:0.000)  b=0.00  count=3000
Total loss:     0.141 (rec:0.141, round:0.000)  b=0.00  count=3500
Total loss:     0.145 (rec:0.145, round:0.000)  b=0.00  count=4000
Total loss:     0.165 (rec:0.165, round:0.000)  b=0.00  count=4500
Total loss:     0.150 (rec:0.150, round:0.000)  b=0.00  count=5000
Reconstruction for block 0
Total loss:     0.118 (rec:0.118, round:0.000)  b=0.00  count=500
Total loss:     0.116 (rec:0.116, round:0.000)  b=0.00  count=1000
Total loss:     0.122 (rec:0.122, round:0.000)  b=0.00  count=1500
Total loss:     0.116 (rec:0.116, round:0.000)  b=0.00  count=2000
Total loss:     0.119 (rec:0.119, round:0.000)  b=0.00  count=2500
Total loss:     0.122 (rec:0.122, round:0.000)  b=0.00  count=3000
Total loss:     0.118 (rec:0.118, round:0.000)  b=0.00  count=3500
Total loss:     0.118 (rec:0.118, round:0.000)  b=0.00  count=4000
Total loss:     0.115 (rec:0.115, round:0.000)  b=0.00  count=4500
Total loss:     0.124 (rec:0.124, round:0.000)  b=0.00  count=5000
Reconstruction for block 1
Total loss:     0.199 (rec:0.199, round:0.000)  b=0.00  count=500
Total loss:     0.183 (rec:0.183, round:0.000)  b=0.00  count=1000
Total loss:     0.185 (rec:0.185, round:0.000)  b=0.00  count=1500
Total loss:     0.208 (rec:0.208, round:0.000)  b=0.00  count=2000
Total loss:     0.190 (rec:0.190, round:0.000)  b=0.00  count=2500
Total loss:     0.172 (rec:0.172, round:0.000)  b=0.00  count=3000
Total loss:     0.205 (rec:0.205, round:0.000)  b=0.00  count=3500
Total loss:     0.205 (rec:0.205, round:0.000)  b=0.00  count=4000
Total loss:     0.190 (rec:0.190, round:0.000)  b=0.00  count=4500
Total loss:     0.210 (rec:0.210, round:0.000)  b=0.00  count=5000
Reconstruction for block 0
Total loss:     0.170 (rec:0.170, round:0.000)  b=0.00  count=500
Total loss:     0.157 (rec:0.157, round:0.000)  b=0.00  count=1000
Total loss:     0.161 (rec:0.161, round:0.000)  b=0.00  count=1500
Total loss:     0.165 (rec:0.165, round:0.000)  b=0.00  count=2000
Total loss:     0.160 (rec:0.160, round:0.000)  b=0.00  count=2500
Total loss:     0.161 (rec:0.161, round:0.000)  b=0.00  count=3000
Total loss:     0.153 (rec:0.153, round:0.000)  b=0.00  count=3500
Total loss:     0.153 (rec:0.153, round:0.000)  b=0.00  count=4000
Total loss:     0.167 (rec:0.167, round:0.000)  b=0.00  count=4500
Total loss:     0.160 (rec:0.160, round:0.000)  b=0.00  count=5000
Reconstruction for block 1
Total loss:     0.227 (rec:0.227, round:0.000)  b=0.00  count=500
Total loss:     0.218 (rec:0.218, round:0.000)  b=0.00  count=1000
Total loss:     0.211 (rec:0.211, round:0.000)  b=0.00  count=1500
Total loss:     0.226 (rec:0.226, round:0.000)  b=0.00  count=2000
Total loss:     0.214 (rec:0.214, round:0.000)  b=0.00  count=2500
Total loss:     0.221 (rec:0.221, round:0.000)  b=0.00  count=3000
Total loss:     0.214 (rec:0.214, round:0.000)  b=0.00  count=3500
Total loss:     0.218 (rec:0.218, round:0.000)  b=0.00  count=4000
Total loss:     0.213 (rec:0.213, round:0.000)  b=0.00  count=4500
Total loss:     0.213 (rec:0.213, round:0.000)  b=0.00  count=5000
Reconstruction for block 0
Total loss:     0.501 (rec:0.501, round:0.000)  b=0.00  count=500
Total loss:     0.462 (rec:0.462, round:0.000)  b=0.00  count=1000
Total loss:     0.490 (rec:0.490, round:0.000)  b=0.00  count=1500
Total loss:     0.513 (rec:0.513, round:0.000)  b=0.00  count=2000
Total loss:     0.481 (rec:0.481, round:0.000)  b=0.00  count=2500
Total loss:     0.530 (rec:0.530, round:0.000)  b=0.00  count=3000
Total loss:     0.537 (rec:0.537, round:0.000)  b=0.00  count=3500
Total loss:     0.485 (rec:0.485, round:0.000)  b=0.00  count=4000
Total loss:     0.480 (rec:0.480, round:0.000)  b=0.00  count=4500
Total loss:     0.517 (rec:0.517, round:0.000)  b=0.00  count=5000
Reconstruction for block 1
Total loss:     300.731 (rec:300.731, round:0.000)      b=0.00  count=500
Total loss:     263.687 (rec:263.687, round:0.000)      b=0.00  count=1000
Total loss:     260.488 (rec:260.488, round:0.000)      b=0.00  count=1500
Total loss:     268.951 (rec:268.951, round:0.000)      b=0.00  count=2000
Total loss:     258.230 (rec:258.230, round:0.000)      b=0.00  count=2500
Total loss:     267.259 (rec:267.259, round:0.000)      b=0.00  count=3000
Total loss:     279.053 (rec:279.053, round:0.000)      b=0.00  count=3500
Total loss:     272.420 (rec:272.420, round:0.000)      b=0.00  count=4000
Total loss:     269.046 (rec:269.046, round:0.000)      b=0.00  count=4500
Total loss:     257.309 (rec:257.309, round:0.000)      b=0.00  count=5000
Reconstruction for layer fc
Total loss:     48.623 (rec:48.623, round:0.000)        b=0.00  count=500
Total loss:     46.298 (rec:46.298, round:0.000)        b=0.00  count=1000
Total loss:     43.821 (rec:43.821, round:0.000)        b=0.00  count=1500
Total loss:     45.067 (rec:45.067, round:0.000)        b=0.00  count=2000
Total loss:     37.050 (rec:37.050, round:0.000)        b=0.00  count=2500
Total loss:     49.344 (rec:49.344, round:0.000)        b=0.00  count=3000
Total loss:     46.815 (rec:46.815, round:0.000)        b=0.00  count=3500
Total loss:     45.719 (rec:45.719, round:0.000)        b=0.00  count=4000
Total loss:     46.137 (rec:46.137, round:0.000)        b=0.00  count=4500
Total loss:     44.667 (rec:44.667, round:0.000)        b=0.00  count=5000
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
You are using fake SyncBatchNorm2d who is actually the official BatchNorm2d
Test: [  0/157] Time 13.934 (13.934)    Acc@1   0.00 (  0.00)   Acc@5   0.00 (  0.00)
Test: [100/157] Time  0.109 ( 0.251)    Acc@1   0.00 (  0.02)   Acc@5   0.00 (  0.39)
 * Acc@1 0.020 Acc@5 0.410
Full quantization (W2A4) accuracy: 0.019999999552965164