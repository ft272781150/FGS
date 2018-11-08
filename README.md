# FGS
## This repository includes model code of FGS and model checker NuSMV.

### STEP1: Getting NuSMV

1: if your computer environment is windows x64, you can download the NuSMV-2.6.0-win64.zip directly.

2: if not, you can also explore the website of NuSMV (http://nusmv.fbk.eu/NuSMV/download/getting-v2.html), in this page you can click Pre-compiled version of NuSMV.

![Image text](https://github.com/ft272781150/FGS/blob/master/img/1.jpg)

And then, you need enter the check word and click Do not Register.

![Image text](https://github.com/ft272781150/FGS/blob/master/img/2.jpg)
      
Finally, you can download the correct version for you computer environment!

![Image text](https://github.com/ft272781150/FGS/blob/master/img/3.jpg)

### STEP2: Run the FGS mode through NuSMV

In command line, you can enter the NuSMV catalog and then input: NuSMV -int

![Image text](https://github.com/ft272781150/FGS/blob/master/img/4.jpg)

After that, you should input the following command:

read_model -i "your smv file path"

go

check_ctlspec

![Image text](https://github.com/ft272781150/FGS/blob/master/img/5.jpg)
