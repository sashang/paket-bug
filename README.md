# Demonstrates a stackoverflow

## Instructions to repro issue
Clone this repo
```
chmod +x .paket/paket.exe
.paket/paket.exe install
```
chmod +x .paket/paket.exe
.paket/paket.exe install




## Expected output
```
The process is taking longer than expected.
Paket may still find a valid resolution, but this might take a while.
Stack overflow in unmanaged: IP: 0x55cd65713c2d, fault addr: 0x7ffefb4cde88
Stack overflow: IP: 0x55cd656fa3dd, fault addr: 0x7ffefb4c5f80
Stacktrace:
```

## Workaround

Remove the `paket.lock` file.





