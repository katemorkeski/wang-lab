## Running CHANOS documentation
Dylan Titmuss

### Peristaltic pump flow rates
_(measured Sep 14, 2022)_

**Acid**
| RPM | mL/min |
|---|---|
| 0.5 | 0.025 |

**Indicator**
| RPM | mL/min |
|---|---|
| 3 | 0.15 |
| 4 | 0.20 |

**Seawater**
| RPM | mL/min |
|---|---|
| 20 | . |
| 30 | . |
| 40 | . |
| 45 | . |
| 55 | . |

### Fitting specifics
List of parts, product numbers, and purchase links [here](https://docs.google.com/spreadsheets/d/1qeb6Xm3a77qfnudg0RbO5zIJ3JhFE3r3gQCl5yniu-8/)

### Switching laptop functionality to prevent/allow connection to WHOI network
_in command line:_

`ssh root@192.168.0.50` or `ssh root@fnsembed3.whoi.edu`  
navigate to parent directory of `etc`  
`cd etc`  
`cd network`  
`cp interfaces.local interfaces` or  

check that file sizes align as expected:  
`ls -l`
