
## Common Commands

SETNX - Set **key** to hold **value** if **key** does not exist
``` bash
SETNX key value  
```

EXPIRE - Set a timeout on **key**
```bash
EXPIRE key seconds [NX | XX | GT | LT]
```
* Options
	* NX - Set expiry only when the key has no expiry
	* XX - Set expiry only when the key has an existing expiry
	* GT - Set expiry only when the new expiry is greater than current one
	* LT - Set expiry only when the new expiry is less than current one

FLUSHALL - 