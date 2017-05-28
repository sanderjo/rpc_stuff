# rpc_stuff
RPC Stuff

Trying to get 1990's technology RPC working ...

# LinuxJournal

Taken from https://www.linuxjournal.com/article/2204?page=0,1

# Input files

```
avg.x # the definition file for RPCGEN
ravg.c  # The RPC client
avg_proc.c # The RPC server (definition)
Makefile
```

Make it:
```
make
```

Start server:
```
./avg_svc
```

Start client:
```
./ravg localhost 33 92.33 555.555
value   = 3.300000e+01
value   = 9.233000e+01
value   = 5.555550e+02
average = 2.269617e+02
```
