

### A miner needs a hotkey
### A hotkey needs a coldkey.


## Did you already create a coldkey and hotkeys?

### No:

```bash
#If the following command is ran it is possible to try to create a new coldkey:```

btcli new_coldkey

#If the following command is ran it is possible to try to create a new hotkey:

btcli new_hotkey
```

### Yes:

```bash
#If the following command is ran it is possible to try to regenerate a coldkey:

btcli regen_coldkey

#If the following command is ran it is possible to try to regenerate a hotkey:

btcli regen_hotkey --wallet.name <COLDKEY_NAME>
        
```





