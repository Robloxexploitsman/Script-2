--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v82=v2(v0(v30,16));if v19 then local v87=0;local v88;while true do if (0==v87) then v88=v5(v82,v19);v19=nil;v87=1;end if (v87==1) then return v88;end end else return v82;end end end);local function v20(v31,v32,v33) if v33 then local v83=(v31/((1 + 1)^(v32-(2 -1))))%((5 -3)^(((v33-(1 -0)) -(v32-((879 -(282 + 595)) -1))) + ((156 + 464) -(555 + 64)))) ;return v83-(v83%(932 -(857 + 74))) ;else local v84=2^(v32-(569 -(367 + 201))) ;return (((v31%(v84 + v84))>=v84) and 1) or (927 -(214 + 713)) ;end end local function v21() local v34=1637 -(1523 + 114) ;local v35;while true do if (v34==(0 + 0)) then v35=v1(v16,v18,v18);v18=v18 + (1 -0) ;v34=1;end if (v34==(1066 -(68 + (2267 -(226 + 1044))))) then return v35;end end end local function v22() local v36,v37=v1(v16,v18,v18 + 2 );v18=v18 + (8 -6) ;return (v37 * (373 -(32 + 85))) + v36 ;end local function v23() local v38=0 + (180 -(67 + 113)) ;local v39;local v40;local v41;local v42;while true do if ((0 + 0)==v38) then v39,v40,v41,v42=v1(v16,v18,v18 + (960 -(892 + 65)) );v18=v18 + 4 ;v38=2 -1 ;end if (1==v38) then return (v42 * (31011612 -14234396)) + (v41 * (120312 -54776)) + (v40 * (606 -(87 + 263))) + v39 ;end end end local function v24() local v43=v23();local v44=v23();local v45=1 + (18 -(10 + 8)) ;local v46=(v20(v44,1,49 -29 ) * ((7 -5)^(24 + 8))) + v43 ;local v47=v20(v44,83 -62 ,983 -(802 + 149 + 1) );local v48=((v20(v44,32)==(2 -1)) and  -((792 -(368 + 423)) -0)) or (1 + 0) ;if (v47==(997 -(915 + (524 -(416 + 26))))) then if (v46==(0 -(0 -0))) then return v48 * 0 ;else v47=1 + 0 + 0 ;v45=0 -0 ;end elseif (v47==(2691 -644)) then return ((v46==(1187 -(1069 + 118))) and (v48 * ((2 -1)/(0 -0)))) or (v48 * NaN) ;end return v8(v48,v47-(178 + 845) ) * (v45 + (v46/(((9 -6) -1)^(490 -(145 + 293))))) ;end local function v25(v49) local v50=430 -(44 + 386) ;local v51;local v52;while true do if (1==v50) then v51=v3(v16,v18,(v18 + v49) -(1487 -(998 + 488)) );v18=v18 + v49 ;v50=1 + 1 ;end if (v50==(3 + 0)) then return v6(v52);end if (v50==0) then v51=nil;if  not v49 then local v95=0;while true do if (v95==(772 -((733 -532) + 571))) then v49=v23();if (v49==0) then return "";end break;end end end v50=1;end if (v50==(1140 -((411 -295) + 1022))) then v52={};for v89=4 -3 , #v51 do v52[v89]=v2(v1(v3(v51,v89,v89)));end v50=2 + 1 ;end end end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v53=(function() return 0;end)();local v54=(function() return;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();local v58=(function() return;end)();local v59=(function() return;end)();local v60=(function() return;end)();while true do local v67=(function() return 1636 -(1373 + 263) ;end)();while true do if (v67~=(1001 -(451 + 549))) then else if (v53==(1 + 0)) then local v98=(function() return 0 -0 ;end)();while true do if (v98~=0) then else v57=(function() return {};end)();v58=(function() return {v55,v56,nil,v57};end)();v98=(function() return 1385 -(746 + 638) ;end)();end if (v98==(1 + 0)) then v59=(function() return v23();end)();v53=(function() return 2 -0 ;end)();break;end end end if (v53~=(343 -(218 + 123))) then else local v99=(function() return 1581 -(1535 + 46) ;end)();while true do if ((1 + 0)==v99) then v58[ #"xxx"]=(function() return v21();end)();v53=(function() return 1 + 2 ;end)();break;end if (v99~=(560 -(306 + 254))) then else v60=(function() return {};end)();for v110= #"!",v59 do local v111=(function() return 0;end)();local v112=(function() return;end)();local v113=(function() return;end)();local v114=(function() return;end)();while true do if (v111==(0 + 0)) then local v123=(function() return 0;end)();while true do if (v123~=1) then else v111=(function() return 1 -0 ;end)();break;end if (v123==(1467 -(899 + 568))) then v112=(function() return 0 + 0 ;end)();v113=(function() return nil;end)();v123=(function() return 1;end)();end end end if (1==v111) then v114=(function() return nil;end)();while true do if (v112==1) then if (v113== #"[") then v114=(function() return v21()~=(0 -0) ;end)();elseif (v113==(605 -(268 + 335))) then v114=(function() return v24();end)();elseif (v113== #"91(") then v114=(function() return v25();end)();end v60[v110]=(function() return v114;end)();break;end if (v112==0) then v113=(function() return v21();end)();v114=(function() return nil;end)();v112=(function() return 1;end)();end end break;end end end v99=(function() return 1;end)();end end end break;end if (v67==(290 -(60 + 230))) then if (v53~=3) then else for v101= #"|",v23() do local v102=(function() return v21();end)();if (v20(v102, #"\\", #"\\")==(572 -(426 + 146))) then local v105=(function() return 0;end)();local v106=(function() return;end)();local v107=(function() return;end)();local v108=(function() return;end)();local v109=(function() return;end)();while true do if (v105==(1 + 1)) then while true do if (v106~= #"asd") then else if (v20(v108, #"xxx", #"asd")~= #"}") then else v109[ #".dev"]=(function() return v60[v109[ #".com"]];end)();end v55[v101]=(function() return v109;end)();break;end if (v106== #"~") then local v125=(function() return 1456 -(282 + 1174) ;end)();local v126=(function() return;end)();while true do if (v125==0) then v126=(function() return 0;end)();while true do if (v126~=1) then else v106=(function() return 813 -(569 + 242) ;end)();break;end if ((0 -0)==v126) then v109=(function() return {v22(),v22(),nil,nil};end)();if (v107==0) then local v392=(function() return 0;end)();local v393=(function() return;end)();while true do if (v392~=0) then else v393=(function() return 0 + 0 ;end)();while true do if (v393==(1024 -(706 + 318))) then v109[ #"asd"]=(function() return v22();end)();v109[ #"asd1"]=(function() return v22();end)();break;end end break;end end elseif (v107== #",") then v109[ #"91("]=(function() return v23();end)();elseif (v107==(1253 -(721 + 530))) then v109[ #"19("]=(function() return v23() -(2^16) ;end)();elseif (v107== #"xxx") then local v400=(function() return 1271 -(945 + 326) ;end)();local v401=(function() return;end)();while true do if (v400==0) then v401=(function() return 0;end)();while true do if (v401~=(0 -0)) then else v109[ #"xnx"]=(function() return v23() -(2^16) ;end)();v109[ #"0313"]=(function() return v22();end)();break;end end break;end end end v126=(function() return 1 + 0 ;end)();end end break;end end end if (v106==(702 -(271 + 429))) then local v127=(function() return 0 + 0 ;end)();local v128=(function() return;end)();while true do if (v127~=(1500 -(1408 + 92))) then else v128=(function() return 1086 -(461 + 625) ;end)();while true do if (v128==1) then v106=(function() return  #"19(";end)();break;end if (v128==0) then if (v20(v108, #"}", #"{")~= #"}") then else v109[2]=(function() return v60[v109[2]];end)();end if (v20(v108,1290 -(993 + 295) ,2)~= #",") then else v109[ #"xnx"]=(function() return v60[v109[ #"19("]];end)();end v128=(function() return 1;end)();end end break;end end end if (v106==0) then local v129=(function() return 0;end)();local v130=(function() return;end)();while true do if (v129~=(0 + 0)) then else v130=(function() return 1171 -(418 + 753) ;end)();while true do if (v130==(0 + 0)) then v107=(function() return v20(v102,1 + 1 , #"xxx");end)();v108=(function() return v20(v102, #"xnxx",2 + 4 );end)();v130=(function() return 1;end)();end if ((1 + 0)==v130) then v106=(function() return  #"/";end)();break;end end break;end end end end break;end if (v105==1) then local v120=(function() return 0;end)();while true do if (v120==(529 -(406 + 123))) then v108=(function() return nil;end)();v109=(function() return nil;end)();v120=(function() return 1770 -(1749 + 20) ;end)();end if (v120==(1 + 0)) then v105=(function() return 2;end)();break;end end end if (v105==(1322 -(1249 + 73))) then local v121=(function() return 0 + 0 ;end)();local v122=(function() return;end)();while true do if (v121==0) then v122=(function() return 0;end)();while true do if (v122~=(1146 -(466 + 679))) then else v105=(function() return 2 -1 ;end)();break;end if ((0 -0)==v122) then v106=(function() return 0;end)();v107=(function() return nil;end)();v122=(function() return 1901 -(106 + 1794) ;end)();end end break;end end end end end end for v103= #"}",v23() do v56,v103,v28=(function() return v54(v56,v103,v28);end)();end return v58;end if (v53==(0 + 0)) then local v100=(function() return 0 + 0 ;end)();while true do if (v100==(0 -0)) then v54=(function() return function(v115,v116,v117) local v118=(function() return 0 -0 ;end)();local v119=(function() return;end)();while true do if (v118~=0) then else v119=(function() return 0;end)();while true do if (v119~=0) then else local v235=(function() return 114 -(4 + 110) ;end)();while true do if (v235==0) then v115[v116-#"~" ]=(function() return v117();end)();return v115,v116,v117;end end end end break;end end end;end)();v55=(function() return {};end)();v100=(function() return 1;end)();end if (v100==1) then v56=(function() return {};end)();v53=(function() return 585 -(57 + 527) ;end)();break;end end end v67=(function() return 1428 -(41 + 1386) ;end)();end end end end local function v29(v61,v62,v63) local v64=v61[104 -(17 + 86) ];local v65=v61[2 + 0 ];local v66=v61[3];return function(...) local v68=v64;local v69=v65;local v70=v66;local v71=v27;local v72=1 -0 ;local v73= -(2 -1);local v74={};local v75={...};local v76=v12("#",...) -(1 -0) ;local v77={};local v78={};for v85=0 -0 ,v76 do if (v85>=v70) then v74[v85-v70 ]=v75[v85 + 1 + 0 ];else v78[v85]=v75[v85 + 1 + (0 -0) ];end end local v79=(v76-v70) + (1 -0) ;local v80;local v81;while true do local v86=0;while true do if (v86==(66 -(30 + 35))) then if (v81<=16) then if (v81<=(5 + (5 -3))) then if ((2613<=2680) and (v81<=3)) then if (v81<=(1258 -(1043 + 214))) then if (v81==(0 -0)) then v72=v80[1215 -(323 + (2715 -1826)) ];else local v132=0 -(0 -0) ;local v133;local v134;local v135;local v136;while true do if ((v132==(18 -11)) or (1482>=4288)) then v80=v68[v72];v78[v80[5 -3 ]]=v78[v80[583 -(361 + 219) ]]%v78[v80[324 -(53 + 267) ]] ;v72=v72 + ((3029 -(389 + 1391)) -(70 + 41 + 1137)) ;v80=v68[v72];v78[v80[2]]=v80[1 + 2 ] + v78[v80[417 -(15 + 398) ]] ;v72=v72 + (983 -(2 + 16 + 964)) ;v80=v68[v72];v132=531 -((962 -539) + 100) ;end if ((v132==(37 -27)) or (2462>4426)) then v73=(v135 + v136) -(1 + (951 -(783 + 168))) ;v133=0 + 0 ;for v342=v136,v73 do local v343=0 + 0 ;while true do if ((4774==4774) and (v343==(850 -(20 + 830)))) then v133=v133 + 1 + 0 ;v78[v342]=v134[v133];break;end end end v72=v72 + 1 ;v80=v68[v72];v136=v80[8 -(19 -13) ];v134,v135=v71(v78[v136](v13(v78,v136 + (127 -(116 + 10)) ,v73)));v132=25 -14 ;end if ((715 -(530 + 181))==v132) then v134,v135=v71(v78[v136](v13(v78,v136 + 1 + 0 ,v80[35 -(19 + 13) ])));v73=(v135 + v136) -(739 -(542 + 196)) ;v133=0 -0 ;for v344=v136,v73 do local v345=0 + 0 ;while true do if (v345==(0 + 0)) then v133=v133 + 1 + 0 ;v78[v344]=v134[v133];break;end end end v72=v72 + (2 -1) ;v80=v68[v72];v136=v80[4 -2 ];v132=1556 -(1126 + 425) ;end if (v132==(416 -(118 + 287))) then v73=(v135 + v136) -(1813 -(1293 + 511 + 8)) ;v133=0 -0 ;for v346=v136,v73 do v133=v133 + (1122 -(118 + 1003)) ;v78[v346]=v134[v133];end v72=v72 + (1 -0) ;v80=v68[v72];v136=v80[(316 -(309 + 2)) -3 ];v78[v136]=v78[v136](v13(v78,v136 + (378 -(142 + 235)) ,v73));v132=54 -42 ;end if ((566<=960) and (v132==(2 + 6))) then v78[v80[1 + (2 -1) ]]= #v78[v80[980 -(553 + 424) ]];v72=v72 + (1 -0) ;v80=v68[v72];v78[v80[2 + 0 ]]=v78[v80[3 + 0 ]]%v78[v80[3 + 1 ]] ;v72=v72 + 1 + 0 ;v80=v68[v72];v78[v80[2 + 0 ]]=v80[6 -3 ] + v78[v80[11 -7 ]] ;v132=19 -10 ;end if (v132==(3 + 6)) then v72=v72 + (4 -3) ;v80=v68[v72];v78[v80[755 -(239 + (1726 -(1090 + 122))) ]]=v78[v80[3 -0 ]] + v80[1 + 3 ] ;v72=v72 + 1 + 0 ;v80=v68[v72];v136=v80[1331 -(797 + 532) ];v134,v135=v71(v78[v136](v13(v78,v136 + (1881 -(446 + 1434)) ,v80[3 + 0 ])));v132=4 + 6 ;end if (v132==(13 -7)) then v72=v72 + (1203 -(373 + 829)) ;v80=v68[v72];v78[v80[456 -(13 + 441) ]]=v78[v80[734 -(476 + 255) ]];v72=v72 + (1131 -(369 + 761)) ;v80=v68[v72];v78[v80[2 + 0 ]]= #v78[v80[(2 + 3) -2 ]];v72=v72 + 1 + (0 -0) ;v132=7;end if (v132==(24 -11)) then v73=(v135 + v136) -(239 -(44 + 20 + 174)) ;v133=0 + 0 ;for v349=v136,v73 do local v350=0 -0 ;while true do if (v350==(336 -((1262 -(628 + 490)) + 192))) then v133=v133 + (217 -(42 + 174)) ;v78[v349]=v134[v133];break;end end end v72=v72 + 1 + 0 + (0 -0) ;v80=v68[v72];v136=v80[2];v78[v136](v13(v78,v136 + (4 -3) ,v73));break;end if (v132==(5 + 0)) then v78[v136]=v78[v136](v13(v78,v136 + (775 -(431 + 343)) + 0 ,v73));v72=v72 + 1 + 0 ;v80=v68[v72];v78[v80[1506 -(363 + 1141) ]]=v62[v80[(3196 -1613) -(1183 + 397) ]];v72=v72 + (434 -(153 + 280)) ;v80=v68[v72];v78[v80[5 -3 ]]=v62[v80[3 + 0 ]];v132=6 + 0 ;end if (v132==(5 + 7)) then v72=v72 + 1 + 0 ;v80=v68[v72];v78[v80[1977 -(1913 + 62) ]]=v78[v80[3]]%v80[(8 -5) + 1 ] ;v72=v72 + (2 -1) ;v80=v68[v72];v136=v80[(1529 + 406) -(565 + 1368) ];v134,v135=v71(v78[v136](v78[v136 + (3 -2) ]));v132=9 + 4 ;end if (v132==((213 + 1448) -(1477 + 184))) then v133=nil;v134,v135=nil;v136=nil;v78[v80[2 -(1695 -(556 + 1139)) ]]=v78[v80[3 + 0 ]];v72=v72 + 1 ;v80=v68[v72];v78[v80[858 -(564 + 292) ]]=v62[v80[4 -1 ]];v132=2 -1 ;end if ((v132==(1 + 0)) or (2910<=1930)) then v72=v72 + (305 -(244 + 60)) ;v80=v68[v72];v78[v80[2 + 0 ]]=v62[v80[479 -(41 + (450 -(6 + 9))) ]];v72=v72 + (1002 -(172 + 766 + 63)) ;v80=v68[v72];v78[v80[2 + 0 ]]=v62[v80[3]];v72=v72 + (1126 -(480 + 456 + 189)) ;v132=(170 -(28 + 141)) + 1 + 0 ;end if (v132==(1616 -(1565 + (58 -10)))) then v78[v80[2 + 0 ]]=v78[v80[1141 -(782 + 253 + 103) ]];v72=v72 + ((1585 -(486 + 831)) -(176 + 91)) ;v80=v68[v72];v78[v80[4 -2 ]]=v78[v80[4 -1 ]] + v80[1096 -((2537 -1562) + (411 -294)) ] ;v72=v72 + 1 + 0 ;v80=v68[v72];v136=v80[1877 -(30 + 127 + 1718) ];v132=(12 -8) + 0 ;end if ((5 -3)==v132) then v80=v68[v72];v78[v80[2 + 0 ]]=v62[v80[10 -7 ]];v72=v72 + ((1753 -(668 + 595)) -(457 + 32)) ;v80=v68[v72];v78[v80[6 -4 ]]=v78[v80[1021 -(697 + 321) ]];v72=v72 + (2 -1) ;v80=v68[v72];v132=5 -2 ;end end end elseif ((v81==(1 + 0 + 1)) or (19>452)) then local v137=v80[2];do return v78[v137](v13(v78,v137 + (2 -(1 + 0)) ,v80[2 + 1 ]));end else do return;end end elseif (v81<=(9 -4)) then if (v81==(10 -6)) then v78[v80[1229 -(322 + 905) ]]={};v72=v72 + ((2 -1) -0) ;v80=v68[v72];v78[v80[(903 -(23 + 267)) -((2546 -(1129 + 815)) + (396 -(371 + 16))) ]]=v63[v80[656 -(232 + (2171 -(1326 + 424))) ]];v72=v72 + (1190 -(449 + 740)) ;v80=v68[v72];v78[v80[874 -(826 + 46) ]]=v78[v80[950 -(245 + 702) ]][v80[7 -3 ]];v72=v72 + (3 -2) ;v80=v68[v72];v78[v80[1 + 1 ]]=v63[v80[1901 -(260 + 1638) ]];v72=v72 + (441 -(382 + 58)) ;v80=v68[v72];v78[v80[6 -4 ]]=v78[v80[3 + (0 -0) ]][v80[8 -(122 -(88 + 30)) ]];v72=v72 + (2 -1) ;v80=v68[v72];v78[v80[1207 -(902 + 303) ]]=v63[v80[5 -2 ]];v72=v72 + (255 -(79 + 175)) ;v80=v68[v72];v78[v80[4 -2 ]]=v78[v80[3]][v80[(772 -(720 + 51)) + 3 ]];v72=v72 + (1691 -(1121 + 569)) ;v80=v68[v72];v78[v80[216 -(22 + 192) ]]=v63[v80[686 -(483 + 200) ]];v72=v72 + (1464 -(1404 + 59)) ;v80=v68[v72];if  not v78[v80[5 -3 ]] then v72=v72 + (1 -0) ;else v72=v80[5 -2 ];end else local v154=v80[2 + 0 ];local v155=v78[v154 + (767 -((1040 -572) + 297)) ];local v156=v78[v154] + v155 ;v78[v154]=v156;if ((v155>(0 -0)) or (907>3152)) then if (v156<=v78[v154 + 1 + 0 ]) then local v351=(2338 -(421 + 1355)) -(334 + 228) ;while true do if ((v351==(0 -0)) or (2505>4470)) then v72=v80[6 -3 ];v78[v154 + 2 + 1 ]=v156;break;end end end elseif (v156>=v78[v154 + (1 -0) ]) then local v352=0 -0 ;while true do if (v352==(0 + 0)) then v72=v80[1 + 2 ];v78[v154 + ((393 -154) -(141 + 95)) ]=v156;break;end end end end elseif ((v81>(6 + 0)) or (3711>4062)) then v78[v80[4 -(1 + 1) ]]=v80[6 -3 ] + v78[v80[(1084 -(286 + 797)) + 3 ]] ;else v78[v80[5 -3 ]]=v63[v80[3 + 0 ]];end elseif ((420==420) and (v81<=(6 + 5))) then if (v81<=(12 -3)) then if (v81>((18 -13) + 3)) then local v161=789 -(766 + 23) ;local v162;while true do if (v161==(163 -(92 + 71))) then v162=v80[1 + 1 ];v78[v162]=v78[v162]();break;end end else local v163=v80[2 -0 ];local v164=v78[v163];local v165=v78[v163 + (6 -4) ];if (v165>0) then if (v164>v78[v163 + ((1778 -704) -(1036 + 37)) ]) then v72=v80[768 -(574 + 191) ];else v78[v163 + 3 + 0 ]=v164;end elseif ((v164<v78[v163 + (2 -1) ]) or (33>=3494)) then v72=v80[2 + 1 ];else v78[v163 + 3 + (439 -(397 + 42)) ]=v164;end end elseif (v81==(859 -(254 + 595))) then v78[v80[128 -(55 + 23 + 48) ]]=v80[3 -0 ];else local v168;v78[v80[1792 -(573 + (2017 -(24 + 776))) ]]=v78[v80[(2598 -911) -(1466 + 218) ]];v72=v72 + (2 -1) ;v80=v68[v72];v78[v80[1 + 1 ]]=v80[4 -(786 -(222 + 563)) ];v72=v72 + (940 -(714 + 225)) ;v80=v68[v72];v78[v80[5 -3 ]]=v80[10 -(14 -7) ];v72=v72 + (1 -0) ;v80=v68[v72];v168=v80[2 + 0 ];v78[v168]=v78[v168](v13(v78,v168 + (1 -0) ,v80[3]));v72=v72 + 1 + 0 ;v80=v68[v72];v78[v80[(2 + 0) -0 ]][v80[809 -(118 + 688) ]]=v78[v80[52 -(25 + 23) ]];v72=v72 + (1390 -(135 + 1254)) ;v80=v68[v72];v78[v80[2]]=v78[v80[1 + 2 ]];v72=v72 + (1887 -(927 + 959)) ;v80=v68[v72];v78[v80[6 -4 ]]=v80[735 -(16 + 716) ];v72=v72 + (1 -0) ;v80=v68[v72];v78[v80[99 -(11 + 86) ]]=v80[(196 -(23 + 167)) -3 ];v72=v72 + (286 -(175 + (1908 -(690 + 1108)))) ;v80=v68[v72];v168=v80[2 + 0 ];v78[v168]=v78[v168](v13(v78,v168 + (1546 -(320 + 442 + 783)) ,v80[3]));v72=v72 + (2 -1) ;v80=v68[v72];v78[v80[9 -7 ]][v80[1799 -(503 + 1293) ]]=v78[v80[11 -7 ]];end elseif (v81<=(1872 -(821 + 1038))) then if ((v81>(9 + 3)) or (1267==4744)) then local v188=v80[1063 -(810 + 251) ];v78[v188](v13(v78,v188 + 1 + 0 + 0 ,v80[2 + 1 ]));else v78[v80[1 + 1 ]]= #v78[v80[1029 -(834 + 192) ]];end elseif (v81<=(1 + (861 -(40 + 808)))) then local v190;local v191;local v192;v78[v80[2 + 0 ]]={};v72=v72 + (534 -(43 + 490)) ;v80=v68[v72];v78[v80[735 -(711 + 22) ]]=v80[11 -8 ];v72=v72 + (860 -(240 + 619)) ;v80=v68[v72];v78[v80[1 + 1 ]]= #v78[v80[3]];v72=v72 + (1 -0) ;v80=v68[v72];v78[v80[1 + 1 ]]=v80[2 + 1 ];v72=v72 + (1745 -(1344 + 66 + 334)) ;v80=v68[v72];v192=v80[407 -(255 + 150) ];v191=v78[v192];v190=v78[v192 + 2 + 0 ];if ((2428<3778) and (v190>(0 + 0))) then if (v191>v78[v192 + 1 + 0 ]) then v72=v80[2 + 1 ];else v78[v192 + (12 -9) ]=v191;end elseif (v191<v78[v192 + (3 -2) ]) then v72=v80[9 -6 ];else v78[v192 + (1742 -(404 + 1335)) ]=v191;end elseif ((v81>(421 -(183 + 223))) or (2946<=1596)) then v78[v80[2 -0 ]]=v78[v80[2 + 1 ]];else local v239=0 + 0 ;local v240;while true do if (v239==0) then v240=v80[(325 + 14) -(10 + 327) ];v78[v240](v13(v78,v240 + 1 + 0 ,v73));break;end end end elseif (v81<=(363 -(118 + 220))) then if ((4433>3127) and (v81<=(622 -(512 + 48 + 42)))) then if (v81<=18) then if ((4300>=2733) and (v81==(1923 -(1665 + 241)))) then v78[v80[1 + 1 ]]=v78[v80[452 -(108 + 341) ]][v80[2 + 2 ]];else local v204=0 -0 ;local v205;local v206;local v207;local v208;while true do if ((4829==4829) and (v204==(1493 -(711 + 782)))) then v205=v80[3 -1 ];v206,v207=v71(v78[v205](v13(v78,v205 + (1100 -(20 + 15 + (1635 -(47 + 524)))) ,v73)));v204=470 -(270 + 199) ;end if ((4 -(2 + 0))==v204) then for v361=v205,v73 do local v362=0 + 0 ;while true do if (v362==((4972 -3153) -(580 + 1239))) then v208=v208 + (2 -(1 -0)) ;v78[v361]=v206[v208];break;end end end break;end if (v204==(1 + 0)) then v73=(v207 + v205) -(1 + 0) ;v208=0 + 0 ;v204=1 + 1 ;end end end elseif ((1683<=4726) and (v81==(49 -30))) then local v209=v80[2 + 0 ];v78[v209]=v78[v209](v13(v78,v209 + 1 + (0 -0) ,v80[1170 -((2371 -(1165 + 561)) + 522) ]));else v78[v80[2]]=v78[v80[1793 -(1010 + 780) ]]%v80[4 + 0 ] ;end elseif (v81<=((4 + 100) -82)) then if (v81==(61 -40)) then local v212=v80[1838 -((3236 -2191) + 791) ];local v213,v214=v71(v78[v212](v78[v212 + (2 -1) ]));v73=(v214 + v212) -((114 + 184) -(36 + 261)) ;local v215=0 -0 ;for v231=v212,v73 do v215=v215 + (506 -(351 + 154)) ;v78[v231]=v213[v215];end else local v216=(2053 -(341 + 138)) -(1281 + 293) ;local v217;while true do if (v216==(266 -(28 + 238))) then v217=v80[4 -(1 + 1) ];v78[v217]=v78[v217](v13(v78,v217 + (1560 -(1381 + 178)) ,v73));break;end end end elseif (v81<=(22 + 1)) then v78[v80[2 + (0 -0) ]]=v78[v80[3 + 0 ]]%v78[v80[2 + 2 ]] ;elseif (v81==(82 -58)) then local v241=v80[2 + 0 ];do return v13(v78,v241,v73);end else v78[v80[970 -(478 + 490) ]][v80[473 -(381 + (415 -(89 + 237))) ]]=v78[v80[4 + (0 -0) ]];end elseif (v81<=(20 + 9)) then if (v81<=(45 -18)) then if (v81==(1182 -(1074 + 82))) then v78[v80[2]]={};elseif ((4835>=3669) and  not v78[v80[(2907 -1526) -(1055 + 324) ]]) then v72=v72 + 1 ;else v72=v80[6 -3 ];end elseif (v81>(25 + 3)) then local v220=(881 -(581 + 300)) + 0 ;local v221;local v222;local v223;while true do if (v220==(1786 -(214 + 1570))) then for v363=1456 -(990 + (1685 -(855 + 365))) ,v80[2 + 2 ] do v72=v72 + 1 + 0 ;local v364=v68[v72];if ((2851>1859) and (v364[1 + 0 ]==(62 -46))) then v223[v363-(1727 -(1668 + 58)) ]={v78,v364[3 + 0 ]};else v223[v363-1 ]={v62,v364[3]};end v77[ #v77 + (689 -(364 + 324)) ]=v223;end v78[v80[1 + 1 ]]=v29(v221,v222,v63);break;end if (v220==(0 + 0 + 0)) then v221=v69[v80[3]];v222=nil;v220=1 + 0 ;end if (v220==1) then v223={};v222=v10({},{__index=function(v366,v367) local v368=v223[v367];return v368[3 -2 ][v368[1996 -(109 + 1885) ]];end,__newindex=function(v369,v370,v371) local v372=v223[v370];v372[1470 -(1269 + 200) ][v372[3 -1 ]]=v371;end});v220=817 -(98 + 717) ;end end else local v224=1268 -(1249 + 19) ;local v225;local v226;while true do if (v224==(826 -(802 + 24))) then v225=nil;v226=nil;v226=v80[2 -0 ];v225=v78[v80[3 -0 ]];v78[v226 + (287 -(156 + 130)) + 0 ]=v225;v224=1 + 0 ;end if ((3848>2323) and ((1 + 0)==v224)) then v78[v226]=v225[v80[(2 -1) + (4 -1) ]];v72=v72 + (2 -1) ;v80=v68[v72];v78[v80[6 -(7 -3) ]]=v78[v80[(3 + 6) -6 ]][v80[5 -(1 + 0) ]];v72=v72 + (70 -(10 + 59)) + 0 ;v224=1 + 1 ;end if (v224==(2 + 2)) then v78[v226 + 1 + 0 ]=v225;v78[v226]=v225[v80[7 -3 ]];v72=v72 + 1 + 0 ;v80=v68[v72];v78[v80[1 + 1 ]]=v78[v80[(407 + 1029) -((3925 -3128) + (1799 -(671 + 492))) ]][v80[19 -15 ]];v224=(1293 + 331) -(1427 + 192) ;end if (v224==(2 + (1216 -(369 + 846)))) then v78[v80[4 -2 ]]=v78[v80[1 + 2 + 0 ]][v80[2 + 2 ]];v72=v72 + (3 -2) ;v80=v68[v72];v226=v80[3 -1 ];v225=v78[v80[(281 + 48) -(192 + 134) ]];v224=4;end if ((2836>469) and (v224==6)) then v226=v80[1278 -(316 + 960) ];v78[v226](v13(v78,v226 + 1 + 0 ,v80[3 + 0 ]));v72=v72 + (3 -2) ;v80=v68[v72];v72=v80[(1948 -(1036 + 909)) + 0 ];break;end if (v224==(7 -5)) then v80=v68[v72];v226=v80[553 -(83 + 468) ];v78[v226]=v78[v226](v13(v78,v226 + (1807 -(1202 + 604)) ,v80[13 -10 ]));v72=v72 + (1 -0) ;v80=v68[v72];v224=1456 -(23 + 5 + 1425) ;end if ((v224==5) or (2096<=540)) then v72=v72 + (1994 -(941 + 1052)) ;v80=v68[v72];v78[v80[5 -3 ]]=v80[(550 -222) -(45 + 280) ];v72=v72 + (1515 -(822 + 692)) ;v80=v68[v72];v224=7 -1 ;end end end elseif (v81<=(30 + 1)) then if (v81>30) then if v78[v80[2 + 0 ]] then v72=v72 + 1 + 0 ;else v72=v80[(205 -(11 + 192)) + 1 ];end else v78[v80[1 + 1 ]]=v78[v80[5 -2 ]] + v80[1915 -(340 + 794 + 777) ] ;end elseif (v81<=((220 -(135 + 40)) -13)) then v78[v80[1 + 1 ]]=v62[v80[2 + 1 ]];elseif (v81==(1805 -(1733 + 39))) then local v246=v80[3 -1 ];local v247=v78[v80[8 -5 ]];v78[v246 + (1207 -((1795 -1054) + 465)) ]=v247;v78[v246]=v247[v80[(626 + 412) -((275 -150) + 909) ]];else local v251=v80[1950 -(1096 + 852) ];local v252,v253=v71(v78[v251](v13(v78,v251 + 1 + 0 ,v80[3 -(0 -0) ])));v73=(v253 + v251) -(1 + 0) ;local v254=(176 -(50 + 126)) -(0 -0) ;for v340=v251,v73 do local v341=512 -(409 + 103) ;while true do if (((236 -(46 + 190))==v341) or (3183<2645)) then v254=v254 + ((22 + 74) -(51 + 44)) ;v78[v340]=v252[v254];break;end end end end v72=v72 + 1 + 0 ;break;end if ((3230<=3760) and (v86==(1317 -(1114 + 203)))) then v80=v68[v72];v81=v80[1 + 0 ];v86=727 -(228 + (1911 -(1233 + 180))) ;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!153Q0003063Q00737472696E6703043Q006368617203043Q00627974652Q033Q0073756203053Q0062697433322Q033Q0062697403043Q0062786F7203053Q007461626C6503063Q00636F6E63617403063Q00696E73657274026Q00104003023Q0073EC03053Q009C43AD4AA5026Q00F03F03113Q00E3C6CB29EFB8C60AD4C7E831E9A9C619D403083Q007EB1A3BB4586DBA703043Q007761697403043Q0067616D65030A3Q004765745365727669636503053Q00547261696E030A3Q004669726553657276657200304Q00047Q00122Q000100013Q00202Q00010001000200122Q000200013Q00202Q00020002000300122Q000300013Q00202Q00030003000400122Q000400053Q00062Q0004000B0001000100044Q000B0001001206000400063Q002011000500040007001206000600083Q002011000600060009001206000700083Q00201100070007000A00061D00083Q000100062Q00103Q00074Q00103Q00014Q00103Q00054Q00103Q00024Q00103Q00034Q00103Q00064Q000B000900083Q00122Q000A000C3Q00122Q000B000D6Q0009000B000200104Q000B00094Q000900083Q00122Q000A000F3Q00122Q000B00106Q0009000B000200104Q000E0009001206000900114Q000900090001000200061F0009002F00013Q00044Q002F0001001206000900123Q00201C00090009001300202Q000B3Q000E4Q0009000B000200202Q00090009001400202Q00090009001500202Q000B3Q000B00122Q000C000E6Q0009000C000100044Q002100012Q00033Q00013Q00013Q00023Q00026Q00F03F026Q00704002264Q000E00025Q00122Q000300016Q00045Q00122Q000500013Q00042Q0003002100012Q002000076Q0001000800026Q000900016Q000A00026Q000B00036Q000C00046Q000D8Q000E00063Q00202Q000F000600014Q000C000F6Q000B3Q00024Q000C00036Q000D00046Q000E00016Q000F00016Q000F0006000F00102Q000F0001000F4Q001000016Q00100006001000102Q00100001001000202Q0010001000014Q000D00106Q000C8Q000A3Q000200202Q000A000A00024Q0009000A6Q00073Q00010004050003000500012Q0020000300054Q0010000400024Q0002000300044Q001800036Q00033Q00017Q00",v9(),...);