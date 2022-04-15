# <device_name_here_as_the_file_name>

## Time

2022/4/15

## Device

\<Provider>-\<Category>-\<Location>-\<OS>-\<Storage>-\<CPUCore>-\<Memory>-\<OtherInfo>  
e.g.
Vultr-HighFrequency-Tokyo-CentOS 8 x64-384GB NVMe-4CPU-16384MB-5000GB Bandwidth

## Price

\<Price>  
e.g.
$0.143/h

## Algo

\<Algorithm(rx/0 only)>  
rx/0

## MiningPool

e.g.
c3pool.com

## HalfHourShares

\<SubmittedSharesIn0.5Hour>  
e.g.
3444301

## Estimate1MonthAmount

\<EstimateSharesIn1Month>  
e.g.
4,959,793,440

## Estimate1MonthProfit(XMR)

0.0143937929

## Rate

\<ProfitRate=EstimateProfit/VPSProfit>  
e.g.
3.80%

## HashRate

e.g.
1800H/s

## CPU Usage

e.g.
407%

## Log

```
e.g.
[root@vultrguest xmrig]# ./xmrig
 * ABOUT        XMRig/6.9.0 gcc/5.4.0
 * LIBS         libuv/1.40.0 OpenSSL/1.1.1i hwloc/2.4.0
 * HUGE PAGES   supported
 * 1GB PAGES    unavailable
 * CPU          Intel Core Processor (Skylake, IBRS) (1) 64-bit AES VM
                L2:8.0 MB L3:16.0 MB 2C/4T NUMA:1
 * MEMORY       2.7/15.5 GB (18%)
                DIMM 0: 16 GB RAM @ 0 MHz DIMM 0
 * MOTHERBOARD  Vultr - HFC
 * DONATE       1%
 * ASSEMBLY     auto:intel
 * POOL #1      mine.c3pool.cn:15555 algo auto
 * COMMANDS     hashrate, pause, resume, results, connection
 * OPENCL       disabled
 * CUDA         disabled
[2021-06-20 07:13:38.937]  net      use pool mine.c3pool.cn:15555  49.234.165.103
[2021-06-20 07:13:38.937]  net      new job from mine.c3pool.cn:15555 diff 50000 algo rx/0 height 2387167
[2021-06-20 07:13:38.937]  cpu      use argon2 implementation AVX2
[2021-06-20 07:13:38.940]  msr      cannot read MSR 0x000001a4
[2021-06-20 07:13:38.940]  msr      FAILED TO APPLY MSR MOD, HASHRATE WILL BE LOW
[2021-06-20 07:13:38.940]  randomx  init dataset algo rx/0 (4 threads) seed 82cc97d1ad029f9e...
[2021-06-20 07:13:39.057]  randomx  allocated 2336 MB (2080+256) huge pages 100% 1168/1168 +JIT (118 ms)
[2021-06-20 07:13:45.310]  randomx  dataset ready (6252 ms)
[2021-06-20 07:13:45.310]  cpu      use profile  rx  (4 threads) scratchpad 2048 KB
[2021-06-20 07:13:45.316]  cpu      READY threads 4/4 (4) huge pages 100% 4/4 memory 8192 KB (7 ms)
[2021-06-20 07:13:57.279]  cpu      accepted (1/0) diff 50000 (417 ms)
[2021-06-20 07:14:36.294]  net      new job from mine.c3pool.cn:15555 diff 26162 algo rx/0 height 2387167
[2021-06-20 07:14:36.658]  cpu      accepted (2/0) diff 26162 (299 ms)
[2021-06-20 07:14:45.414]  miner    speed 10s/60s/15m 1860.8 n/a n/a H/s max 1953.5 H/s
[2021-06-20 07:15:01.431]  cpu      accepted (3/0) diff 26162 (299 ms)
[2021-06-20 07:15:02.999]  cpu      accepted (4/0) diff 26162 (313 ms)
[2021-06-20 07:15:10.816]  cpu      accepted (5/0) diff 26162 (298 ms)
[2021-06-20 07:15:19.977]  cpu      accepted (6/0) diff 26162 (300 ms)
[2021-06-20 07:15:36.304]  net      new job from mine.c3pool.cn:15555 diff 46225 algo rx/0 height 2387167
[2021-06-20 07:15:43.315]  cpu      accepted (7/0) diff 46225 (1396 ms)
[2021-06-20 07:15:44.144]  cpu      accepted (8/0) diff 46225 (1586 ms)
[2021-06-20 07:15:45.515]  miner    speed 10s/60s/15m 1725.5 1807.5 n/a H/s max 1995.4 H/s
[2021-06-20 07:16:45.616]  miner    speed 10s/60s/15m 1739.4 1757.5 n/a H/s max 1995.4 H/s
[2021-06-20 07:17:11.568]  cpu      accepted (9/0) diff 46225 (274 ms)
[2021-06-20 07:17:27.996]  cpu      accepted (10/0) diff 46225 (324 ms)
[2021-06-20 07:17:37.314]  cpu      accepted (11/0) diff 46225 (274 ms)
[2021-06-20 07:17:38.424]  cpu      accepted (12/0) diff 46225 (297 ms)
 - RESULTS
 * accepted         12 (100.0%)
 * pool-side hashes 458160 avg 38180
 * difficulty       46225
 * avg result time  20.5s
 - TOP 10
  # | DIFFICULTY | EFFORT % |
  1 |      1028K |    44.54 |
  2 |     780354 |    58.71 |
  3 |     146389 |   312.97 |
  4 |     115107 |   398.03 |
  5 |     111342 |   411.49 |
  6 |     100059 |   457.89 |
  7 |      93977 |   487.52 |
  8 |      80105 |   571.95 |
  9 |      70641 |   648.58 |
 10 |      68825 |   665.69 |
[2021-06-20 07:17:45.723]  miner    speed 10s/60s/15m 1806.0 1899.6 n/a H/s max 2092.6 H/s
[2021-06-20 07:18:45.840]  miner    speed 10s/60s/15m 2036.0 1876.0 n/a H/s max 2092.6 H/s
 - CONNECTION
 * pool address     mine.c3pool.cn:15555 (49.234.165.103)
 * algorithm        rx/0
 * difficulty       46225
 * ping time        300ms
 * connection time  350s
[2021-06-20 07:19:30.226]  cpu      accepted (13/0) diff 46225 (275 ms)
[2021-06-20 07:19:37.940]  cpu      accepted (14/0) diff 46225 (275 ms)
[2021-06-20 07:19:45.961]  miner    speed 10s/60s/15m 2061.1 1913.0 n/a H/s max 2092.6 H/s
[2021-06-20 07:19:48.012]  cpu      accepted (15/0) diff 46225 (283 ms)
[2021-06-20 07:20:01.759]  cpu      accepted (16/0) diff 46225 (276 ms)
[2021-06-20 07:20:02.013]  cpu      accepted (17/0) diff 46225 (367 ms)
[2021-06-20 07:20:06.339]  cpu      accepted (18/0) diff 46225 (274 ms)
[2021-06-20 07:20:07.634]  cpu      accepted (19/0) diff 46225 (294 ms)
[2021-06-20 07:20:31.519]  cpu      accepted (20/0) diff 46225 (276 ms)
[2021-06-20 07:20:36.793]  net      new job from mine.c3pool.cn:15555 diff 59510 algo rx/0 height 2387167
[2021-06-20 07:20:46.068]  miner    speed 10s/60s/15m 1573.8 1843.9 n/a H/s max 2092.6 H/s
[2021-06-20 07:21:09.425]  cpu      accepted (21/0) diff 59510 (276 ms)
[2021-06-20 07:21:10.357]  net      new job from mine.c3pool.cn:15555 diff 59510 algo rx/0 height 2387168
[2021-06-20 07:21:27.506]  cpu      accepted (22/0) diff 59510 (279 ms)
[2021-06-20 07:21:46.184]  miner    speed 10s/60s/15m 1909.4 1659.7 n/a H/s max 2092.6 H/s
[2021-06-20 07:21:48.992]  cpu      accepted (23/0) diff 59510 (276 ms)
[2021-06-20 07:21:54.097]  cpu      accepted (24/0) diff 59510 (274 ms)
[2021-06-20 07:22:06.109]  cpu      accepted (25/0) diff 59510 (275 ms)
[2021-06-20 07:22:31.495]  cpu      accepted (26/0) diff 59510 (299 ms)
[2021-06-20 07:22:46.293]  miner    speed 10s/60s/15m 1654.1 1667.9 n/a H/s max 2092.6 H/s
[2021-06-20 07:23:10.455]  cpu      accepted (27/0) diff 59510 (276 ms)
[2021-06-20 07:23:46.391]  miner    speed 10s/60s/15m 1490.2 1892.2 n/a H/s max 2092.6 H/s
[2021-06-20 07:24:11.200]  cpu      accepted (28/0) diff 59510 (286 ms)
[2021-06-20 07:24:14.184]  net      new job from mine.c3pool.cn:15555 diff 62496 algo rx/0 height 2387169
[2021-06-20 07:24:46.496]  miner    speed 10s/60s/15m 1791.3 1682.1 n/a H/s max 2092.6 H/s
 - RESULTS
 * accepted         28 (100.0%)
 * pool-side hashes 1304040 avg 46573
 * difficulty       62496
 * avg result time  24.7s
 - TOP 10
  # | DIFFICULTY | EFFORT % |
  1 |      1028K |   126.78 |
  2 |     780354 |   167.11 |
  3 |     579476 |   225.04 |
  4 |     342546 |   380.69 |
  5 |     174214 |   748.53 |
  6 |     151022 |   863.48 |
  7 |     146389 |   890.80 |
  8 |     131727 |   989.96 |
  9 |     131409 |   992.35 |
 10 |     115107 |  1132.89 |
[2021-06-20 07:25:19.653]  net      new job from mine.c3pool.cn:15555 diff 59505 algo rx/0 height 2387170
[2021-06-20 07:25:46.602]  miner    speed 10s/60s/15m 1692.0 1725.4 n/a H/s max 2092.6 H/s
[2021-06-20 07:26:06.267]  cpu      accepted (29/0) diff 59505 (274 ms)
[2021-06-20 07:26:06.828]  cpu      accepted (30/0) diff 59505 (278 ms)
[2021-06-20 07:26:19.044]  cpu      accepted (31/0) diff 59505 (274 ms)
[2021-06-20 07:26:43.435]  net      new job from mine.c3pool.cn:15555 diff 57207 algo rx/0 height 2387171
[2021-06-20 07:26:46.718]  miner    speed 10s/60s/15m 1540.4 1594.0 n/a H/s max 2092.6 H/s
[2021-06-20 07:26:53.859]  cpu      accepted (32/0) diff 57207 (280 ms)
[2021-06-20 07:27:08.920]  net      new job from mine.c3pool.cn:15555 diff 57207 algo rx/0 height 2387172
[2021-06-20 07:27:23.319]  cpu      accepted (33/0) diff 57207 (276 ms)
[2021-06-20 07:27:26.052]  cpu      accepted (34/0) diff 57207 (860 ms)
[2021-06-20 07:27:32.311]  cpu      accepted (35/0) diff 57207 (282 ms)
[2021-06-20 07:27:46.840]  miner    speed 10s/60s/15m 1989.6 1805.8 n/a H/s max 2092.6 H/s
[2021-06-20 07:28:03.339]  cpu      accepted (36/0) diff 57207 (274 ms)
[2021-06-20 07:28:13.470]  cpu      accepted (37/0) diff 57207 (277 ms)
[2021-06-20 07:28:15.275]  cpu      accepted (38/0) diff 57207 (276 ms)
[2021-06-20 07:28:46.956]  miner    speed 10s/60s/15m 1908.5 1780.5 1782.4 H/s max 2092.6 H/s
[2021-06-20 07:29:24.544]  cpu      accepted (39/0) diff 57207 (276 ms)
[2021-06-20 07:29:47.072]  miner    speed 10s/60s/15m 1993.8 1730.9 1774.5 H/s max 2092.6 H/s
[2021-06-20 07:29:51.129]  net      new job from mine.c3pool.cn:15555 diff 60791 algo rx/0 height 2387173
[2021-06-20 07:30:24.516]  cpu      accepted (40/0) diff 60791 (274 ms)
[2021-06-20 07:30:32.022]  cpu      accepted (41/0) diff 60791 (275 ms)
[2021-06-20 07:30:47.183]  miner    speed 10s/60s/15m 1872.3 1856.8 1778.8 H/s max 2092.6 H/s
[2021-06-20 07:30:58.520]  cpu      accepted (42/0) diff 60791 (275 ms)
[2021-06-20 07:31:06.539]  cpu      accepted (43/0) diff 60791 (275 ms)
[2021-06-20 07:31:19.009]  cpu      accepted (44/0) diff 60791 (282 ms)
[2021-06-20 07:31:34.916]  net      new job from mine.c3pool.cn:15555 diff 60790 algo rx/0 height 2387174
[2021-06-20 07:31:47.282]  miner    speed 10s/60s/15m 1646.0 1868.6 1786.4 H/s max 2092.6 H/s
[2021-06-20 07:31:52.942]  cpu      accepted (45/0) diff 60790 (280 ms)
[2021-06-20 07:32:00.490]  net      new job from mine.c3pool.cn:15555 diff 62482 algo rx/0 height 2387175
[2021-06-20 07:32:26.078]  net      new job from mine.c3pool.cn:15555 diff 62482 algo rx/0 height 2387176
[2021-06-20 07:32:27.800]  net      new job from mine.c3pool.cn:15555 diff 62482 algo rx/0 height 2387177
[2021-06-20 07:32:32.206]  cpu      accepted (46/0) diff 62482 (275 ms)
 - RESULTS
 * accepted         46 (100.0%)
 * pool-side hashes 2367438 avg 51466
 * difficulty       62482
 * avg result time  24.9s
 - TOP 10
  # | DIFFICULTY | EFFORT % |
  1 |      1028K |   230.16 |
  2 |     780354 |   303.38 |
  3 |     644202 |   367.50 |
  4 |     579476 |   408.55 |
  5 |     342546 |   691.13 |
  6 |     200597 |  1180.20 |
  7 |     174214 |  1358.93 |
  8 |     161771 |  1463.45 |
  9 |     159136 |  1487.68 |
 10 |     151022 |  1567.61 |
[2021-06-20 07:32:47.391]  miner    speed 10s/60s/15m 1680.5 1662.2 1770.2 H/s max 2092.6 H/s
[2021-06-20 07:32:54.314]  cpu      accepted (47/0) diff 62482 (277 ms)
[2021-06-20 07:33:47.493]  miner    speed 10s/60s/15m 1686.2 1733.0 1760.6 H/s max 2092.6 H/s
[2021-06-20 07:33:49.849]  net      new job from mine.c3pool.cn:15555 diff 60874 algo rx/0 height 2387178
[2021-06-20 07:34:01.386]  cpu      accepted (48/0) diff 60874 (275 ms)
[2021-06-20 07:34:01.713]  cpu      accepted (49/0) diff 60874 (278 ms)
[2021-06-20 07:34:11.385]  net      new job from mine.c3pool.cn:15555 diff 60874 algo rx/0 height 2387179
[2021-06-20 07:34:32.679]  cpu      accepted (50/0) diff 60874 (275 ms)
[2021-06-20 07:34:47.602]  miner    speed 10s/60s/15m 1457.3 1598.6 1739.3 H/s max 2092.6 H/s
[2021-06-20 07:34:48.168]  cpu      accepted (51/0) diff 60874 (316 ms)
[2021-06-20 07:34:50.200]  net      new job from mine.c3pool.cn:15555 diff 62325 algo rx/0 height 2387180
[2021-06-20 07:34:54.728]  net      new job from mine.c3pool.cn:15555 diff 62325 algo rx/0 height 2387181
|    CPU # | AFFINITY | 10s H/s | 60s H/s | 15m H/s |
|        0 |        0 |   368.5 |   371.8 |   431.2 |
|        1 |        1 |   413.7 |   386.4 |   433.5 |
|        2 |        2 |   419.9 |   392.4 |   434.0 |
|        3 |        3 |   372.3 |   376.9 |   432.0 |
|        - |        - |  1574.4 |  1527.5 |  1730.6 |
[2021-06-20 07:35:03.863]  miner    speed 10s/60s/15m 1574.4 1527.5 1730.6 H/s max 2092.6 H/s
[2021-06-20 07:35:47.718]  miner    speed 10s/60s/15m 1704.3 1596.5 1723.9 H/s max 2092.6 H/s
[2021-06-20 07:36:13.499]  cpu      accepted (52/0) diff 62325 (753 ms)
[2021-06-20 07:36:20.354]  cpu      accepted (53/0) diff 62325 (276 ms)
[2021-06-20 07:36:47.830]  miner    speed 10s/60s/15m 1671.4 1709.1 1726.3 H/s max 2092.6 H/s
[2021-06-20 07:37:47.947]  miner    speed 10s/60s/15m 1802.5 1804.4 1735.7 H/s max 2092.6 H/s
[2021-06-20 07:37:48.160]  cpu      accepted (54/0) diff 62325 (277 ms)
[2021-06-20 07:38:05.403]  net      new job from mine.c3pool.cn:15555 diff 58391 algo rx/0 height 2387182
 - RESULTS
 * accepted         54 (100.0%)
 * pool-side hashes 2860391 avg 52970
 * difficulty       58391
 * avg result time  27.9s
 - TOP 10
  # | DIFFICULTY | EFFORT % |
  1 |      1157K |   247.04 |
  2 |      1028K |   278.09 |
  3 |     780354 |   366.55 |
  4 |     649696 |   440.27 |
  5 |     644202 |   444.02 |
  6 |     579476 |   493.62 |
  7 |     342546 |   835.04 |
  8 |     200597 |  1425.94 |
  9 |     174214 |  1641.88 |
 10 |     161771 |  1768.17 |
[2021-06-20 07:38:48.063]  miner    speed 10s/60s/15m 1779.2 1796.5 1729.9 H/s max 2092.6 H/s
[2021-06-20 07:38:54.813]  cpu      accepted (55/0) diff 58391 (278 ms)
[2021-06-20 07:38:55.309]  cpu      accepted (56/0) diff 58391 (279 ms)
[2021-06-20 07:39:00.470]  cpu      accepted (57/0) diff 58391 (276 ms)
[2021-06-20 07:39:48.185]  miner    speed 10s/60s/15m 1661.9 1740.8 1733.6 H/s max 2092.6 H/s
[2021-06-20 07:40:01.829]  cpu      accepted (58/0) diff 58391 (285 ms)
[2021-06-20 07:40:48.294]  miner    speed 10s/60s/15m 1526.7 1546.7 1722.0 H/s max 2092.6 H/s
[2021-06-20 07:40:50.682]  cpu      accepted (59/0) diff 58391 (754 ms)
[2021-06-20 07:41:00.978]  cpu      accepted (60/0) diff 58391 (275 ms)
[2021-06-20 07:41:34.376]  cpu      accepted (61/0) diff 58391 (275 ms)
[2021-06-20 07:41:39.992]  cpu      accepted (62/0) diff 58391 (276 ms)
[2021-06-20 07:41:48.405]  miner    speed 10s/60s/15m 1755.8 1730.7 1730.7 H/s max 2092.6 H/s
[2021-06-20 07:42:48.505]  miner    speed 10s/60s/15m 1968.1 1983.0 1741.9 H/s max 2092.6 H/s
[2021-06-20 07:43:02.806]  cpu      accepted (63/0) diff 58391 (316 ms)
[2021-06-20 07:43:25.030]  cpu      accepted (64/0) diff 58391 (277 ms)
 - RESULTS
 * accepted         64 (100.0%)
 * pool-side hashes 3444301 avg 53817
 * difficulty       58391
 * avg result time  28.1s
 - TOP 10
  # | DIFFICULTY | EFFORT % |
  1 |      1157K |   297.47 |
  2 |      1028K |   334.85 |
  3 |     990466 |   347.75 |
  4 |     842715 |   408.71 |
  5 |     780354 |   441.38 |
  6 |     707497 |   486.83 |
  7 |     649696 |   530.14 |
  8 |     644202 |   534.66 |
  9 |     579476 |   594.38 |
 10 |     378173 |   910.77 |
|    CPU # | AFFINITY | 10s H/s | 60s H/s | 15m H/s |
|        0 |        0 |   478.1 |   454.5 |   435.9 |
|        1 |        1 |   470.3 |   454.0 |   435.8 |
|        2 |        2 |   465.5 |   458.3 |   438.8 |
|        3 |        3 |   458.0 |   450.0 |   433.8 |
|        - |        - |  1871.9 |  1816.7 |  1744.4 |
[2021-06-20 07:43:39.170]  miner    speed 10s/60s/15m 1871.9 1816.7 1744.4 H/s max 2092.6 H/s
[2021-06-20 07:43:40.682]  signal   Ctrl+C received, exiting
[2021-06-20 07:43:40.684]  cpu      stopped (2 ms)
[root@vultrguest xmrig]# 
```
