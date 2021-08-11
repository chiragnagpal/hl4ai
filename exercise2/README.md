# Exercise 2: FST for Somali Morphophonology

## 1.A list of posited root words 
|          |         |         |         |        |
| ---------| --------|---------|---------|---------|
| `daar`   | `gees`  | `laf`   | `lug`   |  `kab`  | 
| `naag`   | `tib`   | `sab`   | `bad`   |  `sid`  |
| `d͡ʒid`   | `feeɖ`  | `ʕiir`  | `ʔul`   | `dil`  |
| `bil`    | `meel`  | `kaliil`| `najl`  | `gan`  |
| `sun`    | `laan`  | `sin`   | `dan`   |  `tun`  |
| `daan`   | `saan`  | `nirig` | `gaβaɖ` |  `arag` |
| `hoglo`  | `bagal` | `wah̵ar` | `irbad` |  `gudub`|
| `kefed`  | `d͡ʒilin`| `bohol` | `jirid` | `qosol` |
| `ʔaajad` | `gaʕan` | `ʔinan` | `sug`   | `hadal` |


## 1.B underlying representations for each suffix

|             |           | 
| ------------| ----------|
| **SG.DEF**  | `-ta`     |
| **PL**      | `-o`      |
| **3SG.MASC**| `-aj`     |
| **3SG.FEM** | `-taj`    |
| **1PL.PAST**| `-naj`    |
|  	      | 	  |

## 1.C Notes on Implementation



## 2 The Foma Script `somali.xsft`

To run to transduce down:
```console
$ foma -l somali.xsft -e "apply down" 
```

To transduce all the words in the `words.txt`:
```console
$ cat words.txt | foma -l somali.xsft -e "apply down" -p > output.txt 
```

3