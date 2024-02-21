sum by (instance)(irate(node_cpu_seconds_total{mode!="idle"}[5m])) > 0
node_memory_Mem -> RAM
sum by (instance)(irate(node_cpu_seconds_total{mode!="idle"}[5m])) > 0
max by(instance) (time() - node_boot_time_seconds{instance=~"$servers"})
