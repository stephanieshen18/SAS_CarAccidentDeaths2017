/*chart that displays states with deaths greater than six hundred and how often they occur*/
/*NOTE: six hundred was arbitrarily selectd. It may be replaced with any number*/

data CarAccidentDeaths2017;
input State$ Deaths;
cards;
Alabama 948
Alaska 79
Arizona 1000
Arkansas 493
California 3602
Colorado 648
Connecticut 278
Delaware 119
Florida 3112
Georgia 1540
Hawaii 107
Idaho 244
Illinois 1097
Indiana 914
Iowa 330
Kansas 461
Kentucky 782
Louisiana 760
Maine 172
Maryland 550
Massachusetts 350
Michigan 1030
Minnesota 357
Mississippi 690
Missouri 930
Montana 186
Nebraska 228
Nevada 309
New_Hampshire 102
New_Jersey 624
New_Mexico 379
New_York 999
North_Carolina 1412
North_Dakota 115
Ohio 1179
Oklahoma 655
Oregon 437
Pennsylvania 1137
Rhode_Island 83
South_Carolina 988
Tennessee 1040
Texas 3722
Utah 273
Vermont 69
Virginia 839
Washington 565
West_Virginia 303
Wisconsin 613
Wyoming 123
;
run;
title "Frequency of States with Death Rates Greater Than 600";
proc freq data=CarAccidentDeaths2017;
where Deaths gt 600;
run;
