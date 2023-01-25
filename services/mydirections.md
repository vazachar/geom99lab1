# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
[https://vazachar.github.io/geom99lab1/services/directions.html](https://maps.googleapis.com/maps/api/directions/json?avoid=toll&depature_time=1674175000&origin=place_id:ChIJpWu8v2pX04kRNsXIQ-K509k&waypoints=place_id:ChIJkSMJK-xY04kRJPootH8cj8w&destination=place_id:ChIJZWITMHFf04kRzGlJxm2J9jc&key=AIzaSyDv3MGflguusDaLmV_-BUlmuoUI4EbM88w)
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJpWu8v2pX04kRNsXIQ-K509k",
         "types" : [ "establishment", "park", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJkSMJK-xY04kRJPootH8cj8w",
         "types" : [ "establishment", "food", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJZWITMHFf04kRzGlJxm2J9jc",
         "types" : [ "establishment", "lodging", "point_of_interest" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.2548391,
               "lng" : -79.07076620000001
            },
            "southwest" : {
               "lat" : 43.2135734,
               "lng" : -79.22261859999999
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "9.8 km",
                  "value" : 9767
               },
               "duration" : {
                  "text" : "13 mins",
                  "value" : 761
               },
               "end_address" : "1096 Lakeshore Rd, Niagara-on-the-Lake, ON L0S 1J0, Canada",
               "end_location" : {
                  "lat" : 43.2498805,
                  "lng" : -79.14116360000001
               },
               "start_address" : "Sunset Beach, 1 Lombardy Ave, St. Catharines, ON L2M 1H8, Canada",
               "start_location" : {
                  "lat" : 43.2264364,
                  "lng" : -79.220597
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 377
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 110
                     },
                     "end_location" : {
                        "lat" : 43.2234227,
                        "lng" : -79.22001019999999
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e toward \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "polyline" : {
                        "points" : "gtyfGvwobNL}@BMBSBIBG@C@ADEBCDCDCFARAR?v@Jn@N`@Jf@H^BpDLRCLA@?LARIh@Y"
                     },
                     "start_location" : {
                        "lat" : 43.2264364,
                        "lng" : -79.220597
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "76 m",
                        "value" : 76
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 43.2228391,
                        "lng" : -79.22030459999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBogart St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kayfG`tobNH\\FHDFHBH@fAB"
                     },
                     "start_location" : {
                        "lat" : 43.2234227,
                        "lng" : -79.22001019999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 188
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 43.2227925,
                        "lng" : -79.22261859999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBeachaven Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "w}xfGzuobNB`B@tCBvE"
                     },
                     "start_location" : {
                        "lat" : 43.2228391,
                        "lng" : -79.22030459999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1026
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 109
                     },
                     "end_location" : {
                        "lat" : 43.2135734,
                        "lng" : -79.22221949999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eArthur St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "m}xfGjdpbN`CEp@AtAEtAEb@Ab@?l@?`AAfAC~@AfCIrBAzGKvBGpHOt@AtA?dA?"
                     },
                     "start_location" : {
                        "lat" : 43.2227925,
                        "lng" : -79.22261859999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "8.1 km",
                        "value" : 8100
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 492
                     },
                     "end_location" : {
                        "lat" : 43.2498805,
                        "lng" : -79.14116360000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLakeshore Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRegional Rd 87\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Regional Rd 87\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ycwfGzapbNi@aD_A_GaAwFIi@Kk@_@aC[wBOw@u@oEo@mDG_@o@oDI_@_@}BAIgAeGa@{BiAgGMm@w@iF_AcGU{A_@qBi@{CgAiGi@uCMm@?E{@wEYcBo@cEaAoGmAoH_AiFY{AKg@SgAa@mBCMmAgGS}@SaAUaAMi@YkAMc@k@{Bq@eCoCkKe@cB}@gDqBoHKa@oA{EEQg@gBc@aBCKK_@Ok@[gAEOg@iBKe@GS[kAuBsFoDqJuA{DwCkI}BqGkE}La@mA_@eAsB}Fi@}AoAsDM[Qi@]}@gAaDmAuDk@iBa@qAi@eBq@uBc@oAQk@Qi@Ok@IU[gAIYCIGMKUKUMQMSWWQO]QMGSGQEMAYA]?SAO@{FLyHNaCDA?kBDqAA{@MQEWIMIUSOOSWMQWm@GIOc@u@kBg@qA{@{ByBwFqB{EYm@We@oB_E_@o@ACOWGMGOIOIUCGCISq@G[Mu@Gc@YmCE]k@mFUuB?EGa@Oy@Q}@CKOg@eAsDaAaDi@gBCG}AqF_AwCiAkDu@{BUo@Wm@Ue@We@]k@IKo@{@sB_DYa@Wc@EGs@oAIQ"
                     },
                     "start_location" : {
                        "lat" : 43.2135734,
                        "lng" : -79.22221949999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "6.4 km",
                  "value" : 6369
               },
               "duration" : {
                  "text" : "8 mins",
                  "value" : 483
               },
               "end_address" : "6 Picton St, Niagara-on-the-Lake, ON L0S 1J0, Canada",
               "end_location" : {
                  "lat" : 43.2546332,
                  "lng" : -79.07076620000001
               },
               "start_address" : "1096 Lakeshore Rd, Niagara-on-the-Lake, ON L0S 1J0, Canada",
               "start_location" : {
                  "lat" : 43.2498805,
                  "lng" : -79.14116360000001
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "4.9 km",
                        "value" : 4860
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 309
                     },
                     "end_location" : {
                        "lat" : 43.2529755,
                        "lng" : -79.08382859999999
                     },
                     "html_instructions" : "Head \u003cb\u003enortheast\u003c/b\u003e on \u003cb\u003eLakeshore Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRegional Rd 87\u003c/b\u003e toward \u003cb\u003eFirelane 5\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Regional Rd 87\u003c/div\u003e",
                     "polyline" : {
                        "points" : "wf~fGfg`bNEGQc@Us@K_@I]}@eEgBoJc@{B[{AUoAa@uBSiAYuAi@sCq@wDIe@Y}AYyACQO{@i@}DWyBSmBOgBEe@Q}BCq@Ew@?u@@a@?I@W@Y@OD_@?CPoANw@j@uBv@wBr@uBHy@Ba@@U@M?S?UAQAE?KAQCS?AE[COESW{AG[Gg@Ge@Gw@SgCc@mGW}CU{BK}@Iy@E{@E{@Ay@?{@?]@M@cC@aBBwFBsD?A@eA@_B@]BkAH}BF{AHm@L{CZaH`@cKJeCDkAHcEJaE@wA@eB?G?u@Cm@?QGaAO_BK}@UiBGc@Go@OsAM{@Im@CQG]Km@Km@Kg@AEe@iCKo@UoAKo@AKQyAIo@AK]aCCSEYCUGi@GqAIwAUsFUmDSkDCk@?EKuBKwAC_@A]?e@Bg@HaAf@aBjB{Ep@cBp@cB~@sBl@uA"
                     },
                     "start_location" : {
                        "lat" : 43.2498805,
                        "lng" : -79.14116360000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 744
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 74
                     },
                     "end_location" : {
                        "lat" : 43.2491886,
                        "lng" : -79.0762589
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eMary St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cz~fG|`uaNl@yAnB}EhAoCfAoC|CqHhBqEl@}A`AiCf@sAd@qA"
                     },
                     "start_location" : {
                        "lat" : 43.2529755,
                        "lng" : -79.08382859999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 752
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 43.2546946,
                        "lng" : -79.07089640000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eKing St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mb~fGrqsaNgHyG_DuCeB_BwBoB{BuByAwAeAgAIWW_@gBaB"
                     },
                     "start_location" : {
                        "lat" : 43.2491886,
                        "lng" : -79.0762589
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "13 m",
                        "value" : 13
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 43.2546332,
                        "lng" : -79.07076620000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePicton St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yd_gGbpraNJY"
                     },
                     "start_location" : {
                        "lat" : 43.2546946,
                        "lng" : -79.07089640000001
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "gtyfGvwobNXiBLSVMf@AfBZhATpEPp@GRIh@YH\\LPRDfABB`BDlJ~ISvDCfCEfCIrBArKSfJQzC?iBaLwBoMk@oDeB}JaBmJuDsS{CwR{DmTcBoJqBsMmCyO{AyHyBuKkA{EsGqVaJ}\\uCsKeHeRmFgOiIoUaAsC{FkPeE_MaGiRs@aCSc@Yg@e@k@o@a@a@O_@G{AAwTb@mBDqAA{@Mi@Oc@]c@g@e@_AuBkFuDsJkCiGiDyGi@eAe@yAUqAa@qDgAgKm@eDaEeNaByFiCcIkAkDm@sA_A}AcD{Eq@eAiAqBg@wAU}@}@eEgBoJ_AwEeBeJ_CoM]kBy@yFk@gFUmCUoDEmBD}AXcCz@mDjBmFP_CCaAEs@g@{COcAO}Aw@uKm@yGUwBKwB?aDJqSDeELiEF{AHm@h@}Ll@iONoGLyG@mBCcBGsA[}Cu@qGc@yCyBcMkAgJO{B_@kIm@kK]kGBmAHaAf@aB|C_IpBwEzAoDxDmJ|JqVhB}Ed@qAgHyGeGuFsFeF_D_DIWW_@gBaBJY"
         },
         "summary" : "Regional Rd 87",
         "warnings" : [],
         "waypoint_order" : [ 0 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
