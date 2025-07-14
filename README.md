# 🏏 Cricket T20 World Cup 2022 Data Analysis

## Overview
Built an end-to-end pipeline to select the best 11 players from the T20 World Cup 2022 using:

- Web scraping (Bright Data + ESPN Cricinfo)  
- Data transformation (Python & Pandas)  
- Interactive dashboard (Power BI)

## Tools Used
- Bright Data  
- Python & Pandas  
- Power BI (DAX & Power Query)  

---
## Dashboard Screenshots

### Player Hover Popups
| Batsman View | Bowler View | All-Rounder View |
|:--:|:--:|:--:|
| ![Batsman Hover](dashboard_screenshots/player-hover-batsman.png) | ![Bowler Hover](dashboard_screenshots/player-hover-bowler.png) | ![All-Rounder Hover](dashboard_screenshots/player-hover-allrounder.png) |

### Openers / Power Hitters
| Top Openers Statistics | Selected Openers Statistics |
|:--:|:--:|
| ![Top Openers](dashboard_screenshots/openers-top-stats.png) | ![Selected Openers](dashboard_screenshots/openers-selected-stats.png) |

### Anchors / Middle Order
| Top Anchors Statistics | Selected Anchors Statistics |
|:--:|:--:|
| ![Top Anchors](dashboard_screenshots/anchors-top-stats.png) | ![Selected Anchors](dashboard_screenshots/anchors-selected-stats.png) |

### Finishers
| Top Finishers Statistics | Selected Finishers Statistics |
|:--:|:--:|
| ![Top Finishers](dashboard_screenshots/finishers-top-stats.png) | ![Selected Finishers](dashboard_screenshots/finishers-selected-stats.png) |

### All-Rounders
| Top All-Rounders Statistics | Selected All-Rounders Statistics |
|:--:|:--:|
| ![Top All-Rounders](dashboard_screenshots/allrounders-top-stats.png) | ![Selected All-Rounders](dashboard_screenshots/allrounders-selected-stats.png) |

### Fast Bowlers
| Top Fast Bowlers Statistics | Selected Fast Bowlers Statistics |
|:--:|:--:|
| ![Top Fast Bowlers](dashboard_screenshots/fastbowlers-top-stats.png) | ![Selected Fast Bowlers](dashboard_screenshots/fastbowlers-selected-stats.png) |

### Final 11 Team Selection
| Selected Final XI - Top Order | Selected Final XI - Lower Order |
|:--:|:--:|
| ![Top Order](dashboard_screenshots/finalxi-top-order.png) | ![Lower Order](dashboard_screenshots/finalxi-lower-order.png) |


---
## Player Role Criteria

**Openers:** Avg > 30 | SR > 140 | Inns > 3 | Boundary % > 50 | Batting Pos < 4  
**Anchors:** Avg > 40 | SR > 125 | Inns > 3 | Balls Faced > 20 | Batting Pos > 2  
**Finishers:** Avg > 25 | SR > 130 | Inns > 3 | Balls Faced > 12 | Batting Pos > 4 | Bowling Inns > 1  
**All-Rounders:** Batting Avg > 15 | SR > 140 | Bowling Inns > 2 | Economy < 7 | Bowling SR < 20  
**Fast Bowlers:** Bowling Inns > 4 | Economy < 7 | Bowling SR < 16 | Style = "Fast" | Dot Ball % > 40

## Dashboard Highlights
- Player stat popups on hover  
- Filters by roles (Openers, Anchors, etc.)  
- KPI-based shortlisting  
- Final 11 team view