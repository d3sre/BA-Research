# BA-Research
print.awk: adds pooltag information to pool-tracker exported view. make sure to adjust pool-tracker file by using 
```
awk '{print $1, $2, $3, $4, $5, $6, $7}' FS=" +" OFS=" - " 00_pool-tracker.txt > 00_pool-tracker-delimitted.txt 
```
