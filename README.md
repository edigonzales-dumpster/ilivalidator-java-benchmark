# ilivalidator-java-benchmark

## 254600.ITF
```
time java -jar /Users/stefan/apps/ilivalidator-1.11.6/ilivalidator-1.11.6.jar 254600.ITF
```

```
sdk u java 8.0.252.hs-adpt
```

real	1m7,347s
user	1m29,287s
sys	0m10,802s


real	1m8,306s
user	1m27,882s
sys	0m10,851s


real	1m7,397s
user	1m28,563s
sys	0m10,781s


```
sdk u java 11.0.7.hs-adpt
```

real	1m2,856s
user	1m42,379s
sys	0m11,055s

real	1m0,673s
user	1m44,069s
sys	0m10,693s

real	1m1,119s
user	1m35,818s
sys	0m10,675s

```
sdk u java 20.1.0.r8-grl
```

real	1m6,230s
user	1m10,665s
sys	0m10,812s

real	1m5,727s
user	1m11,663s
sys	0m10,222s

real	1m3,600s
user	1m10,484s
sys	0m9,651s

real	1m3,983s
user	1m11,023s
sys	0m9,757s

```
sdk u java 20.1.0.r11-grl
```

real	1m1,114s
user	1m13,816s
sys	0m9,518s

real	1m0,775s
user	1m12,614s
sys	0m9,488s

real	1m1,136s
user	1m12,936s
sys	0m9,913s

## Oereb

```
time java -jar /Users/stefan/apps/ilivalidator-1.11.6/ilivalidator-1.11.6.jar --allObjectsAccessible OeREBKRM_V1_1_Gesetze_20180501.xml ch.so.sk.gesetze.xtf ch.so.arp.nutzungsplanung.oereb.xtf



time java -jar ilivalidator-1.11.7-SNAPSHOT-all.jar --allObjectsAccessible OeREBKRM_V1_1_Gesetze_20180501.xml ch.so.sk.gesetze.xtf ch.so.arp.nutzungsplanung.oereb.xtf
time java -Xmx20G -jar ilivalidator-1.11.7-SNAPSHOT-all.jar --allObjectsAccessible OeREBKRM_V1_1_Gesetze_20180501.xml ch.so.sk.gesetze.xtf ch.so.arp.nutzungsplanung.oereb.xtf


time java -XX:+UnlockExperimentalVMOptions -XX:+UseShenandoahGC -jar ilivalidator-1.11.7-SNAPSHOT-all.jar --allObjectsAccessible OeREBKRM_V1_1_Gesetze_20180501.xml ch.so.sk.gesetze.xtf ch.so.arp.nutzungsplanung.oereb.xtf


```

```
sdk u java 8.0.252.hs-adpt
```

real	2m0,010s
user	2m21,274s
sys	0m4,175s

real	2m4,327s
user	2m19,585s
sys	0m4,513s

real	1m53,479s
user	2m10,185s
sys	0m4,256s

real	2m5,809s
user	2m23,545s
sys	0m4,970s

```
sdk u java 11.0.7.hs-adpt
```
real	2m28,149s
user	2m54,106s
sys	0m5,315s

real	2m20,742s
user	2m42,520s
sys	0m4,634s

real	2m18,605s
user	2m45,670s
sys	0m4,945s

```
sdk u java 20.1.0.r8-grl
```

real	1m51,374s
user	1m53,173s
sys	0m5,324s

real	1m41,555s
user	1m49,621s
sys	0m3,611s

real	1m40,917s
user	1m48,687s
sys	0m3,513s

```
sdk u java 20.1.0.r11-grl
```

real	2m8,574s
user	2m18,699s
sys	0m3,542s

real	2m6,058s
user	2m16,885s
sys	0m3,458s

real	2m10,417s
user	2m21,574s
sys	0m3,448s

------

time java -Xmx2G -jar /Users/stefan/apps/ilivalidator-1.11.6/ilivalidator-1.11.6.jar --allObjectsAccessible OeREBKRM_V1_1_Gesetze_20180501.xml ch.so.sk.gesetze.xtf ch.so.arp.nutzungsplanung.oereb.xtf
