# AES vs Local Rankings Report

- Generated (UTC): 2026-03-24 02:57:59
- Local model used: massey
- AES algorithm: usav (national), season start year 2025

## Method Notes (AES)

- AES publishes USAV and AES ranking algorithms and refresh metadata through ranking endpoints.
- This comparison used USAV national ranking mode and compared by overlapping age/gender divisions.
- Reference links:
  - https://www.advancedeventsystems.com/rankings/usav
  - http://aes-help.sportsengine.com/en/articles/8242388-power-rankings-faqs
  - https://aes-help.sportsengine.com/en/collections/7045603-usa-volleyball-national-rankings

## Overlapping Divisions

| Pool | AES URL |
|---|---|
| B14 | https://www.advancedeventsystems.com/rankings/Male/U14/usav |
| B15 | https://www.advancedeventsystems.com/rankings/Male/U15/usav |
| B16 | https://www.advancedeventsystems.com/rankings/Male/U16/usav |
| B17 | https://www.advancedeventsystems.com/rankings/Male/U17/usav |
| B18 | https://www.advancedeventsystems.com/rankings/Male/U18/usav |
| G12 | https://www.advancedeventsystems.com/rankings/Female/U12/usav |
| G13 | https://www.advancedeventsystems.com/rankings/Female/U13/usav |
| G14 | https://www.advancedeventsystems.com/rankings/Female/U14/usav |
| G15 | https://www.advancedeventsystems.com/rankings/Female/U15/usav |
| G16 | https://www.advancedeventsystems.com/rankings/Female/U16/usav |
| G17 | https://www.advancedeventsystems.com/rankings/Female/U17/usav |
| G18 | https://www.advancedeventsystems.com/rankings/Female/U18/usav |

## Division Consistency

| Pool | AES Teams | Local Teams | Matched | Coverage | Spearman | Mean Abs Rank Diff | Top5 Overlap | Top10 Overlap |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| B14 | 261 | 21 | 12 | 4.6% | 0.727 | 141.25 | 0 | 0 |
| B15 | 208 | 27 | 22 | 10.6% | 0.659 | 103.59 | 0 | 0 |
| B16 | 406 | 46 | 35 | 8.6% | 0.837 | 208.31 | 0 | 1 |
| B17 | 327 | 51 | 40 | 12.2% | 0.710 | 149.05 | 0 | 0 |
| B18 | 537 | 63 | 48 | 8.9% | 0.812 | 256.19 | 0 | 0 |
| G12 | 2541 | 49 | 23 | 0.9% | 0.814 | 1761.30 | 0 | 0 |
| G13 | 3073 | 95 | 54 | 1.8% | 0.669 | 1738.04 | 0 | 0 |
| G14 | 4528 | 162 | 78 | 1.7% | 0.665 | 2389.01 | 0 | 0 |
| G15 | 3851 | 197 | 115 | 3.0% | 0.659 | 2078.36 | 0 | 0 |
| G16 | 3765 | 228 | 140 | 3.7% | 0.780 | 1996.42 | 0 | 0 |
| G17 | 2388 | 158 | 108 | 4.5% | 0.727 | 1290.91 | 0 | 0 |
| G18 | 1876 | 128 | 88 | 4.7% | 0.784 | 1101.92 | 0 | 0 |

## NYC Open Predictive Comparison

- NYC Open known-result matches: 1781
- Local picks: 1781 | Accuracy: 85.74%
- AES picks: 685 | Accuracy: 69.78%
- Better on NYC Open: Local (+15.96 percentage points local-aes)

### NYC Open by Division

| Pool | Matches | Local Picks | Local Acc | AES Picks | AES Acc |
|---|---:|---:|---:|---:|---:|
| B14 | 45 | 45 | 86.7% | 11 | 72.7% |
| B15 | 53 | 53 | 83.0% | 28 | 53.6% |
| B16 | 75 | 75 | 88.0% | 41 | 85.4% |
| B17 | 95 | 95 | 78.9% | 58 | 67.2% |
| B18 | 110 | 110 | 80.0% | 60 | 71.7% |
| G12 | 65 | 65 | 92.3% | 8 | 87.5% |
| G13 | 147 | 147 | 90.5% | 47 | 66.0% |
| G14 | 208 | 208 | 86.5% | 35 | 68.6% |
| G15 | 257 | 257 | 87.9% | 101 | 72.3% |
| G16 | 293 | 293 | 81.2% | 88 | 68.2% |
| G17 | 252 | 252 | 89.3% | 132 | 69.7% |
| G18 | 181 | 181 | 84.5% | 76 | 67.1% |

## Unmatched Teams

- Unmatched AES teams: 22998
| Pool | AES Team | AES Code | AES Rank |
|---|---|---|---:|
| B14 | HPSTL B14 Royal | B14HPSTL1GW | 1 |
| B14 | MOD B14 Blue | B14MODVB1GL | 2 |
| B14 | Aspire Kennedy | B14ASPIR4AZ | 3 |
| B14 | MKE Sting 14-1 | B14MLWST1BG | 4 |
| B14 | Kaizen Boys 14 Black | B14KZNJR1OK | 5 |
| B14 | Boys BSVBC 14 Black | B14BLSTL1GW | 6 |
| B14 | WPVC Boys 14 Armour Black | B14WPVCB1FL | 7 |
| B14 | A5 Boys 14 Umar | B14AFIVE1SO | 8 |
| B14 | Bay to Bay 14-1 | B14BYTBY1NC | 9 |
| B14 | 315 VC 14-1 | B14315VB1XL | 10 |
| B14 | Balboa Bay 14Blue | B14BALBY1SC | 11 |
| B14 | TU Boys 14-Elite | B14TRDUN1CR | 12 |
| B14 | MN Select Boys 14-1 | B14MNSEL1NO | 13 |
| B14 | COAST Boys 14-1 Bela | B14COAST1SC | 14 |
| B14 | Pulse 14-Daniel | B14PULSE1SC | 15 |
| B14 | Aspire 14 Groot | B14ASPIR1AZ | 16 |
| B14 | MB Surf ASICS 14's 1 | B14MBSUR1SC | 17 |
| B14 | Roch PaceBootleggr14 Blk | B14PACEB1WE | 18 |
| B14 | Evolution 14 Elite Kalea | B14EVOVB1SC | 19 |
| B14 | MVVC B 14 Black | B14MOUVI2NC | 20 |
| B14 | Bay to Bay 14-Club | B14BYTBY2NC | 21 |
| B14 | MVVC B 14 Red | B14MOUVI1NC | 22 |
| B14 | HPSTL B14 White | B14HPSTL3GW | 23 |
| B14 | High Flyers 14 Red | B14HIFLY1GP | 24 |
| B14 | LVC 14BLUE | B14LOCKP2WE | 25 |
| B14 | ECVBA 14-1 Anthony | B14ECVBA1SC | 26 |
| B14 | Sky High Adidas B14-1 | B14SKYHI1GL | 27 |
| B14 | Miami United 14 N Jon | B14MUTED1FL | 28 |
| B14 | AZ LEGACY 14 APEX | B14LEGVB1AZ | 29 |
| B14 | JJVA Boys 14 Teal | B14JAXJR1FL | 30 |
| B14 | EXCEL 14N Red | B14EXCEL1NT | 31 |
| B14 | NW Jrs. 14 UA Slate | B14NWEST1PS | 32 |
| B14 | SPORTIME 14-1 | B14SPTMC1GE | 33 |
| B14 | NPJ Seattle 14B National | B14NPJSE1PS | 34 |
| B14 | MKE Sting 14-2 | B14MLWST2BG | 35 |
| B14 | AZ Fear 14 Black | B14FEAR11AZ | 36 |
| B14 | MKE Sting 14-3 | B14MLWST3BG | 37 |
| B14 | Ultimate B14 Gold | B14ULTIM1GL | 38 |
| B14 | LVC 14BLACK | B14LOCKP1WE | 39 |
| B14 | Forza - Boys 14-Blk | B14FORZA1GL | 40 |
| B14 | Team Rockstar 14 Anjinho | B14RSTAR1SC | 41 |
| B14 | Balboa Bay 14White | B14BALBY2SC | 42 |
| B14 | MVC 14-Dixon | B14NSMVC1BG | 43 |
| B14 | CVC 14-1 | B14CVBCO1OV | 44 |
| B14 | Academy Boys West 14-1 | B14ACDVP1NC | 45 |
| B14 | Cincy East Boys 14 Black | B14CEAST1OV | 46 |
| B14 | Tribe 14B Elite Cardinal | B14TRIBE1FL | 47 |
| B14 | Apex Boys VBC 14-1 | B14APEXV1SO | 48 |
| B14 | MVVC B 14 National | B14MOUVI3NC | 49 |
| B14 | Roch PaceBootleggr14 Blue | B14PACEB2WE | 51 |
| B14 | Triangle Boys 14 Black | B14TRNGL1CR | 52 |
| B14 | Quicksets 14 Black | B14QUICK1AH | 53 |
| B14 | Evolution 14 Elite Noah | B14EVOVB2SC | 54 |
| B14 | Team Rockstar 14 Joey | B14RSTAR2SC | 55 |
| B14 | Tyrants 14 Black | B14TYRTS1NC | 56 |
| B14 | HPSTL B14 Orange | B14HPSTL2GW | 57 |
| B14 | Chicago Elite B 14 Elite | B14CEVBC1GL | 58 |
| B14 | RootsVBA 14-Ashvale | B14RTVBAAHA | 59 |
| B14 | Hot Shots 14 Coastal | B14HSBOY2WE | 60 |
| B14 | Molten 14 Black | B14MOLTN1AZ | 61 |
| B14 | Emerald Rain Boys 14 E | B14EMRVB1PS | 62 |
| B14 | CHAOS BOYS 14U GOLD | B14CHAOS1CE | 63 |
| B14 | OVC B14 | B14OZVBC1BG | 64 |
| B14 | Orlando Gold 14 Black | B14OGOLD1FL | 65 |
| B14 | OMNI 14-1 National | B14OMNIV1NC | 66 |
| B14 | Cincy Elite 14-1 | B14CINEL1OV | 67 |
| B14 | Red Rock Boys 14-1 | B14RROCK1NC | 68 |
| B14 | Ultimate B14 Blue | B14ULTIM2GL | 69 |
| B14 | MVC 14 Black Developmental | B14MOMTM2AZ | 70 |
| B14 | HVA 14 YOUNG GUNS RED | B14HVAVB1LS | 72 |
| B14 | Sky High Adidas B14-2 | B14SKYHI2GL | 73 |
| B14 | MTRX 14-1 | B14MATRX1AZ | 74 |
| B14 | Uno Boys 14 Elite | B14UNOVB1GL | 75 |
| B14 | MADFROG 14'S BOYS | B14FROGS1NT | 76 |
| B14 | MN Select Boys 14-2 | B14MNSEL2NO | 77 |
| B14 | WSA Gators 14 Elite Boys | B14WELLN1FL | 78 |
| B14 | Aspire Troy | B14ASPIR8AZ | 79 |
| B14 | HHVBC 14 Hawks | B14HMRHK1IA | 80 |
| B14 | PEVA Boys 14 Elite | B14PGHEL1KE | 81 |
| B14 | Annapolis 14U | B14ANNAP1CH | 82 |
| B14 | Aspire Brian | B14ASPIR6AZ | 83 |
| B14 | Victory 14 Black | B14VCVBC1AZ | 84 |
| B14 | MN Select Boys 14-3 | B14MNSEL3NO | 85 |
| B14 | MVA 14 Boys | B14MVASC1PM | 86 |
| B14 | MAVS 14 Red | B14MAVSB1HA | 87 |
| B14 | BVP 14 | B14BVPVA1OV | 88 |
| B14 | 808AC 14 Austin | B14808AC1AH | 89 |
| B14 | Bay to Bay 14-Premier | B14BYTBY4NC | 90 |
| B14 | SERV 14 Beast | B14SERVA1OD | 91 |
| B14 | TU Boys 14-Select | B14TRDUN2CR | 92 |
| B14 | BAVC 14-1 Boys | B14BABLV1NC | 93 |
| B14 | MVC 14-Sean | B14NSMVC2BG | 95 |
| B14 | CJVA Boys 14 Black | B14CJVBA2GE | 96 |
| B14 | Ohana 14U Regional Boys | B14OHANA1IA | 97 |
| B14 | NC Power & Sand 14 Black | B14NCPWR1CR | 98 |
| B14 | Roanoke United 14 Boys | B14RUVJR1OD | 99 |
| B14 | WAVE 14-Cole | B14WVEVB1SC | 100 |
| B14 | KC Legends 14-1 | B14JVABS1HA | 101 |
| B14 | Volitude 14 Ian | B14VOLIT1SC | 102 |
| B14 | FRVBC 14-1 | B14FRVBC1RM | 103 |
| B14 | MVC 14 Red (Developmental) | B14MOMTM3AZ | 104 |
| B14 | Lakas 13/14  JM | B14LAIAT1NC | 105 |
| B14 | Seaside 14-Black | B14SEASI1SC | 106 |
| B14 | Maverick 14 Jester | B14MAVVB3AZ | 107 |
| B14 | MVVC B 14 Club | B14MOUVI4NC | 108 |
| B14 | Hot Shots 14 Regional - Purple | B14HSBOY4WE | 109 |
| B14 | 630 Volleyball 14-1 | B14630VB1GL | 110 |
| B14 | WPVC Boys 14 Armour Orng | B14WPVCB2FL | 111 |
| B14 | FALLS 14 | B14MFJRP9BG | 112 |
| B14 | Aspire 14 Rocket | B14ASPIR2AZ | 113 |
| B14 | AFVBC 14 Apex | B14ARCAD1SC | 114 |
| B14 | Roch PaceBootleggr14 Grn | B14PACEB3WE | 115 |
| B14 | Mintonette Sports b.41 | B14MSPRT1OV | 116 |
| B14 | WAVE 14-Justin | B14WVEVB2SC | 117 |
| B14 | No Panic 14 Boys | B14BNPVB1CH | 118 |
| B14 | OCVC14 Slunks | B14OCVBC1SC | 119 |
| B14 | Bay to Bay 14-National | B14BYTBY5NC | 120 |
| B14 | Buckeye Boys 14 Red | B14BKEYE1OV | 121 |
| B14 | LVC 14WHITE | B14LOCKP3WE | 123 |
| B14 | Epic United 14 Red | B14EPICU1GL | 124 |
| B14 | SC Legends 14-Elite | B14SCLEG1SC | 125 |
| B14 | Velocity B14 Red | B14VELOC1GL | 126 |
| B14 | Miami United 14 Matt | B14MUTED2FL | 127 |
| B14 | Maverick 14 Warlock | B14MAVVB4AZ | 128 |
| B14 | KeAloha 141 Rogue | B14KEAMF1HO | 129 |
| B14 | GP 14 Black | B14GPONT1FL | 130 |
| B14 | AJV Boys 14 adidas | B14AJVBA1LS | 132 |
| B14 | Aspire Micah | B14ASPIR7AZ | 133 |
| B14 | Epic B14-Adidas | B14EPVBC1BG | 134 |
| B14 | SNVF U14 GLACIER PEAK | B14SPACN1PS | 135 |
| B14 | Hot Shots 14 National | B14HSBOY1WE | 136 |
| B14 | Elevate 14-1 | B14ELEV81GW | 137 |
| B14 | AJAXVB 14-1 Gold | B14AJAXB1CE | 138 |
| B14 | Momentum 14-Orange | B14430261OV | 139 |
| B14 | Aspire Shawn | B14ASPIR5AZ | 140 |
| B14 | MVC 14 Black | B14MOMTM1AZ | 141 |
| B14 | CCVBC 14-1 | B14XSCRT1BG | 142 |
| B14 | BAVC Boys 14-1 | B14BAVBC1OK | 143 |
| B14 | KU`IKAHI 14 Red RoShamBo | B14KUIKA1AH | 144 |
| B14 | Club W 14-Black | B14CLUBW1BG | 145 |
| B14 | SKY 14-1 | B14SKYVB1CA | 147 |
| B14 | RVA Boys 14 Navy | B14RVAWI1BG | 148 |
| B14 | KC United 14 Navy | B14UNVBC1HA | 149 |
| B14 | Ozark Boys 14 | B14OJVBC1DE | 150 |
| B14 | Ultimate B14 Black | B14ULTIM3GL | 151 |
| B14 | Southport B14-Blue | B14SPORT1BG | 152 |
| B14 | RUSH 14 Black - Spring | B14RUSHV1AZ | 153 |
| B14 | HEAT 14 Travel | B14NXLKD1NC | 154 |
| B14 | TU Boys 14-Prime | B14TRDUN3CR | 155 |
| B14 | Vegas Aces 14-1 | B14VACES1SC | 156 |
| B14 | MVP Boys 14 Blue | B14MOTVP1BG | 157 |
| B14 | FVC 14-1 | B14FTIER1WE | 158 |
| B14 | United 14 Boys | B14UNITD1SO | 159 |
| B14 | BVA BOYS 14U | B14BUFAC1WE | 160 |
| B14 | VC United B141 Elite | B14VCUTD1GL | 161 |
| B14 | Beach Cities 14 Black | B14BCHCT1SC | 163 |
| B14 | Elevation 14 Peak Boys | B14ELEVB1RM | 164 |
| B14 | A2 14 Scarlet | B14AAVBC2OV | 165 |
| B14 | Mamba 14 Black | B14MAMBA1BG | 166 |
| B14 | Aspire Monte | B14ASPIR9AZ | 167 |
| B14 | Ignite 14 Boys Fury | B14IGNIT1AZ | 168 |
| B14 | Seaside 14 Green | B14SEASI2SC | 169 |
| B14 | Stormbreaker 13/14 Titans | B14STRMB1SC | 170 |
| B14 | Blue Royals 14 Elite | B14BRVBA1PS | 171 |
| B14 | A2 14 Red | B14AAVBC1OV | 172 |
| B14 | PARADOX 14U | B14PARDX1LS | 173 |
| B14 | Alpha Omega Boys 14-1 | B14AOVBL1HA | 174 |
| B14 | CNVKC Mizuno Boys 14-1 | B14CNVKC1HA | 175 |
| B14 | Club 1 B 14 Skronkstrong | B14CLUB11GL | 176 |
| B14 | CJVA Boys 14 Onyx | B14CJVBA1GE | 177 |
| B14 | 630 Volleyball 14-2 | B14630VB2GL | 178 |
| B14 | AZ Fear 14 Blue | B14FEAR12AZ | 180 |
| B14 | MTRX 14-2 | B14MATRX2AZ | 181 |
| B14 | CA Volley 14 | B14CAVBC1SC | 182 |
| B14 | Sidewinder 14-2 | B14SWVBA2AZ | 183 |
| B14 | NW Jrs. 14 UA Onyx | B14NWEST2PS | 184 |
| B14 | COAST Boys 14-2 Colton | B14COAST2SC | 185 |
| B14 | Maverick 14 Fanboy | B14MAVVB1AZ | 187 |
| B14 | AVA 14 Boys | B14ALLIN1FL | 188 |
| B14 | Iowa Galaxy 14-1 | B14CENTL1IA | 189 |
| B14 | Alta 14 | B14ALTAV1AZ | 190 |
| B14 | NF 14 Crimson | B14FRONT2WE | 191 |
| B14 | CCVBC14-2 | B14XSCRT2BG | 192 |
| B14 | Austin Velocity Boys 141 | B14AVVBC1LS | 193 |
| B14 | Power Volleyball 14 | B14PWRVC1GW | 194 |
| B14 | CLE SEL 14 White | B14CLESV2OV | 195 |
| B14 | Orlando Gold 14 Gold | B14OGOLD2FL | 197 |
| B14 | Ignite 14 National Boys | B14IVBCF1SC | 198 |
| B14 | HVA 14 YOUNG GUNS BLUE | B14HVAVB2LS | 199 |
| B14 | Champion 14 Boys | B14CHMPV1CR | 200 |
| B14 | Aspire 14 Ant Man | B14ASPIR3AZ | 201 |
| B14 | Maverick 13 Coyote | B14MAVVB5AZ | 202 |
| B14 | BVC 14u Blue | B14BRIVC1WE | 203 |
| B14 | Chicago Elite B 14 Nike | B14CEVBC2GL | 204 |
| B14 | RCVA 14 National | B14RCVBA1OD | 205 |
| B14 | Battle 14 Black | B14BTVBC1CH | 206 |
| B14 | Piedmont VBC 14 Sparta | B14PIEDM1CR | 207 |
| B14 | OVA 14 Region | B14VVCAZ3AZ | 208 |
| B14 | Maverick 14 Payback | B14MAVVB2AZ | 209 |
| B14 | KIVA 14B Red | B14AKIVA1PR | 210 |