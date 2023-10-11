# Setup

- We have enough instances for you to work in pairs

```
    csc-2023-07.cern.ch
    csc-2023-08.cern.ch
    …
    csc-2023-19.cern.ch
```

- (with some spares)

## Proxying

- Included for reference 
- These instances are **not** available publicly, requiring proxying through `lxplus`
    - `ssh –D 50000 –q –C –N lxplus`
	- Can of course use a port other thatn 50000
- Set up web browser to use SOCKS proxy, `localhost:50000`
- `https://csc-2023-XY.cern.ch` should then yield these docs

