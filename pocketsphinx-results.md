# Pockestphinx results, plain text - Draft

pocketsphinx plain text as extracted from video grep 

```json
<s> 0.160 0.180 0.998501
how 0.190 0.340 0.070404
do 0.350 0.510 0.740274
you 0.520 0.890 0.979021
destroy 0.900 1.260 0.768872
i 1.270 1.490 0.201456
said 1.500 1.700 0.611245
<sil> 1.710 2.050 0.992924
i 2.060 2.240 0.329978
needed(2) 2.250 2.640 0.435223
</s> 2.650 3.040 1.000000
```

s tags enclose a stence `</s>`

```json
how 0.190 0.340 0.070404
```

first word is the text, then start time, end time, and accuracy. 


Need to verify if pocketsphinx always exports like this or this is specific of videogrep implementation.