sum by (instance)(irate(node_cpu_seconds_total{mode!="idle"}[5m])) > 0 <br>
node_memory_Mem -> RAM <br>
sum by (instance)(irate(node_cpu_seconds_total{mode!="idle"}[5m])) > 0 <br>
max by(instance) (time() - node_boot_time_seconds{instance=~"$servers"}) <br>
sum by(state)(engine_daemon_container_states_containers{}) <br>
