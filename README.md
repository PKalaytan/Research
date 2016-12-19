# FX-Python-Public
> This is repository to share my research and FX - Python related work


## /cAlgo-tick-data
```
When testing with cAlgo tick data, I've discovered trades closing immedieately after opening with profit.
Tested tick data from calgo that I've exported using cBot http://ctdn.com/algos/cbots/show/588. for some reason I've discovered on many accations Bid price been above Ask price. See steps taken and results described in Notebooks.

### Results:
 if(ask<bid) check in cBot returned nothing. But I have a mystery opens with immediate close positions in cAlgo.
```

