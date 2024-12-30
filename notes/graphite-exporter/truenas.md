# HELP clock_offset Graphite metric clock_offset
# TYPE clock_offset gauge
clock_offset{instance="nas",job="truenas"} 0
# HELP clock_status Graphite metric clock_status
# TYPE clock_status gauge
clock_status{instance="nas",job="truenas",state="clockerr"} 0
clock_status{instance="nas",job="truenas",state="unsync"} 0
# HELP clock_synced Graphite metric clock_synced
# TYPE clock_synced gauge
clock_synced{instance="nas",job="truenas"} 1
# HELP context_switches Graphite metric context_switches
# TYPE context_switches gauge
context_switches{instance="nas",job="truenas"} 3193.6898
# HELP cpu_frequency Graphite metric cpu_frequency
# TYPE cpu_frequency gauge
cpu_frequency{cpu="cpu0",instance="nas",job="truenas"} 1210.103
cpu_frequency{cpu="cpu1",instance="nas",job="truenas"} 1203.8
cpu_frequency{cpu="cpu2",instance="nas",job="truenas"} 1200
cpu_frequency{cpu="cpu3",instance="nas",job="truenas"} 1202.302
# HELP cpu_idlestate Graphite metric cpu_idlestate
# TYPE cpu_idlestate gauge
cpu_idlestate{cpu="cpu0",instance="nas",job="truenas",state="C0__active_"} 22.408779
cpu_idlestate{cpu="cpu0",instance="nas",job="truenas",state="C1"} 0.3165321
cpu_idlestate{cpu="cpu0",instance="nas",job="truenas",state="C6"} 77.271335
cpu_idlestate{cpu="cpu0",instance="nas",job="truenas",state="POLL"} 0.0033536
cpu_idlestate{cpu="cpu1",instance="nas",job="truenas",state="C0__active_"} 20.3937781
cpu_idlestate{cpu="cpu1",instance="nas",job="truenas",state="C1"} 0.4135243
cpu_idlestate{cpu="cpu1",instance="nas",job="truenas",state="C6"} 79.188923
cpu_idlestate{cpu="cpu1",instance="nas",job="truenas",state="POLL"} 0.0037737
cpu_idlestate{cpu="cpu2",instance="nas",job="truenas",state="C0__active_"} 24.818823
cpu_idlestate{cpu="cpu2",instance="nas",job="truenas",state="C1"} 0.4188733
cpu_idlestate{cpu="cpu2",instance="nas",job="truenas",state="C6"} 74.761884
cpu_idlestate{cpu="cpu2",instance="nas",job="truenas",state="POLL"} 0.0004177
cpu_idlestate{cpu="cpu3",instance="nas",job="truenas",state="C0__active_"} 23.737442
cpu_idlestate{cpu="cpu3",instance="nas",job="truenas",state="C1"} 0.1490333
cpu_idlestate{cpu="cpu3",instance="nas",job="truenas",state="C6"} 76.112551
cpu_idlestate{cpu="cpu3",instance="nas",job="truenas",state="POLL"} 0.0009737
# HELP cpu_softirq Graphite metric cpu_softirq
# TYPE cpu_softirq gauge
cpu_softirq{cpu="cpu0",instance="nas",job="truenas"} 0.3104646
cpu_softirq{cpu="cpu1",instance="nas",job="truenas"} 0.6188365
cpu_softirq{cpu="cpu2",instance="nas",job="truenas"} 0.8980332
cpu_softirq{cpu="cpu3",instance="nas",job="truenas"} 0.502241
# HELP cpu_temperature Graphite metric cpu_temperature
# TYPE cpu_temperature gauge
cpu_temperature{cpu="cpu0",instance="nas",job="truenas"} 60.4
cpu_temperature{cpu="cpu1",instance="nas",job="truenas"} 60
cpu_temperature{cpu="cpu2",instance="nas",job="truenas"} 60.8
cpu_temperature{cpu="cpu3",instance="nas",job="truenas"} 60.2
# HELP cpu_throttling Graphite metric cpu_throttling
# TYPE cpu_throttling gauge
cpu_throttling{cpu="cpu0",instance="nas",job="truenas"} 0
cpu_throttling{cpu="cpu1",instance="nas",job="truenas"} 0
cpu_throttling{cpu="cpu2",instance="nas",job="truenas"} 0
cpu_throttling{cpu="cpu3",instance="nas",job="truenas"} 0
# HELP cpu_total Graphite metric cpu_total
# TYPE cpu_total gauge
cpu_total{instance="nas",job="truenas",kind="guest"} 0
cpu_total{instance="nas",job="truenas",kind="guest_nice"} 0
cpu_total{instance="nas",job="truenas",kind="idle"} 76.484068
cpu_total{instance="nas",job="truenas",kind="iowait"} 1.0570464
cpu_total{instance="nas",job="truenas",kind="irq"} 0
cpu_total{instance="nas",job="truenas",kind="nice"} 0.5571429
cpu_total{instance="nas",job="truenas",kind="steal"} 0
cpu_total{instance="nas",job="truenas",kind="system"} 21.341941
cpu_total{instance="nas",job="truenas",kind="user"} 0.0249377
# HELP cpu_usage Graphite metric cpu_usage
# TYPE cpu_usage gauge
cpu_usage{cpu="cpu0",instance="nas",job="truenas",kind="guest"} 0
cpu_usage{cpu="cpu0",instance="nas",job="truenas",kind="guest_nice"} 0
cpu_usage{cpu="cpu0",instance="nas",job="truenas",kind="idle"} 76.454977
cpu_usage{cpu="cpu0",instance="nas",job="truenas",kind="iowait"} 1.3083451
cpu_usage{cpu="cpu0",instance="nas",job="truenas",kind="irq"} 0
cpu_usage{cpu="cpu0",instance="nas",job="truenas",kind="nice"} 0.9136167
cpu_usage{cpu="cpu0",instance="nas",job="truenas",kind="steal"} 0
cpu_usage{cpu="cpu0",instance="nas",job="truenas",kind="system"} 20.913587
cpu_usage{cpu="cpu0",instance="nas",job="truenas",kind="user"} 0.0990099
cpu_usage{cpu="cpu1",instance="nas",job="truenas",kind="guest"} 0
cpu_usage{cpu="cpu1",instance="nas",job="truenas",kind="guest_nice"} 0
cpu_usage{cpu="cpu1",instance="nas",job="truenas",kind="idle"} 79.176853
cpu_usage{cpu="cpu1",instance="nas",job="truenas",kind="iowait"} 1.3607456
cpu_usage{cpu="cpu1",instance="nas",job="truenas",kind="irq"} 0
cpu_usage{cpu="cpu1",instance="nas",job="truenas",kind="nice"} 0.2931847
cpu_usage{cpu="cpu1",instance="nas",job="truenas",kind="steal"} 0
cpu_usage{cpu="cpu1",instance="nas",job="truenas",kind="system"} 18.5503794
cpu_usage{cpu="cpu1",instance="nas",job="truenas",kind="user"} 0
cpu_usage{cpu="cpu2",instance="nas",job="truenas",kind="guest"} 0
cpu_usage{cpu="cpu2",instance="nas",job="truenas",kind="guest_nice"} 0
cpu_usage{cpu="cpu2",instance="nas",job="truenas",kind="idle"} 75.2326
cpu_usage{cpu="cpu2",instance="nas",job="truenas",kind="iowait"} 0
cpu_usage{cpu="cpu2",instance="nas",job="truenas",kind="irq"} 0
cpu_usage{cpu="cpu2",instance="nas",job="truenas",kind="nice"} 1.0079524
cpu_usage{cpu="cpu2",instance="nas",job="truenas",kind="steal"} 0
cpu_usage{cpu="cpu2",instance="nas",job="truenas",kind="system"} 22.8614162
cpu_usage{cpu="cpu2",instance="nas",job="truenas",kind="user"} 0
cpu_usage{cpu="cpu3",instance="nas",job="truenas",kind="guest"} 0
cpu_usage{cpu="cpu3",instance="nas",job="truenas",kind="guest_nice"} 0
cpu_usage{cpu="cpu3",instance="nas",job="truenas",kind="idle"} 74.962305
cpu_usage{cpu="cpu3",instance="nas",job="truenas",kind="iowait"} 1.5306122
cpu_usage{cpu="cpu3",instance="nas",job="truenas",kind="irq"} 0
cpu_usage{cpu="cpu3",instance="nas",job="truenas",kind="nice"} 0
cpu_usage{cpu="cpu3",instance="nas",job="truenas",kind="steal"} 0
cpu_usage{cpu="cpu3",instance="nas",job="truenas",kind="system"} 22.9028004
cpu_usage{cpu="cpu3",instance="nas",job="truenas",kind="user"} 0.1020408
# HELP disk_await Graphite metric disk_await
# TYPE disk_await gauge
disk_await{disk="sda",instance="nas",job="truenas",op="discards"} 0
disk_await{disk="sda",instance="nas",job="truenas",op="flushes"} 0
disk_await{disk="sda",instance="nas",job="truenas",op="reads"} 0
disk_await{disk="sda",instance="nas",job="truenas",op="writes"} 0
disk_await{disk="sdb",instance="nas",job="truenas",op="discards"} 0
disk_await{disk="sdb",instance="nas",job="truenas",op="flushes"} 0
disk_await{disk="sdb",instance="nas",job="truenas",op="reads"} 0
disk_await{disk="sdb",instance="nas",job="truenas",op="writes"} 0
disk_await{disk="sdc",instance="nas",job="truenas",op="discards"} 0
disk_await{disk="sdc",instance="nas",job="truenas",op="flushes"} 5.1
disk_await{disk="sdc",instance="nas",job="truenas",op="reads"} 7.5
disk_await{disk="sdc",instance="nas",job="truenas",op="writes"} -0.2
disk_await{disk="sdd",instance="nas",job="truenas",op="discards"} 0
disk_await{disk="sdd",instance="nas",job="truenas",op="flushes"} 0
disk_await{disk="sdd",instance="nas",job="truenas",op="reads"} 0
disk_await{disk="sdd",instance="nas",job="truenas",op="writes"} 0
disk_await{disk="sde",instance="nas",job="truenas",op="discards"} 0
disk_await{disk="sde",instance="nas",job="truenas",op="flushes"} 0
disk_await{disk="sde",instance="nas",job="truenas",op="reads"} 0
disk_await{disk="sde",instance="nas",job="truenas",op="writes"} 0
disk_await{disk="sdf",instance="nas",job="truenas",op="discards"} 0
disk_await{disk="sdf",instance="nas",job="truenas",op="flushes"} 0
disk_await{disk="sdf",instance="nas",job="truenas",op="reads"} 0
disk_await{disk="sdf",instance="nas",job="truenas",op="writes"} 0
disk_await{disk="sdg",instance="nas",job="truenas",op="discards"} 0
disk_await{disk="sdg",instance="nas",job="truenas",op="flushes"} 5.4
disk_await{disk="sdg",instance="nas",job="truenas",op="reads"} 23.6
disk_await{disk="sdg",instance="nas",job="truenas",op="writes"} -0.3
disk_await{disk="sdh",instance="nas",job="truenas",op="discards"} 0
disk_await{disk="sdh",instance="nas",job="truenas",op="flushes"} 5.9
disk_await{disk="sdh",instance="nas",job="truenas",op="reads"} 19.9
disk_await{disk="sdh",instance="nas",job="truenas",op="writes"} -0.4
disk_await{disk="sdi",instance="nas",job="truenas",op="discards"} 0
disk_await{disk="sdi",instance="nas",job="truenas",op="flushes"} 5.7
disk_await{disk="sdi",instance="nas",job="truenas",op="reads"} 12.3
disk_await{disk="sdi",instance="nas",job="truenas",op="writes"} -0.2
# HELP disk_busy Graphite metric disk_busy
# TYPE disk_busy gauge
disk_busy{disk="sda",instance="nas",job="truenas"} 0
disk_busy{disk="sdb",instance="nas",job="truenas"} 0
disk_busy{disk="sdc",instance="nas",job="truenas"} 774.78016
disk_busy{disk="sdd",instance="nas",job="truenas"} 0
disk_busy{disk="sde",instance="nas",job="truenas"} 0
disk_busy{disk="sdf",instance="nas",job="truenas"} 0
disk_busy{disk="sdg",instance="nas",job="truenas"} 980.74485
disk_busy{disk="sdh",instance="nas",job="truenas"} 914.3328
disk_busy{disk="sdi",instance="nas",job="truenas"} 963.28803
# HELP disk_io Graphite metric disk_io
# TYPE disk_io gauge
disk_io{disk="sda",instance="nas",job="truenas",op="discards"} 0
disk_io{disk="sda",instance="nas",job="truenas",op="reads"} 0
disk_io{disk="sda",instance="nas",job="truenas",op="writes"} 0
disk_io{disk="sdb",instance="nas",job="truenas",op="discards"} 0
disk_io{disk="sdb",instance="nas",job="truenas",op="reads"} 0
disk_io{disk="sdb",instance="nas",job="truenas",op="writes"} 0
disk_io{disk="sdc",instance="nas",job="truenas",op="discards"} 0
disk_io{disk="sdc",instance="nas",job="truenas",op="merged_discards"} 0
disk_io{disk="sdc",instance="nas",job="truenas",op="merged_reads"} 0.1
disk_io{disk="sdc",instance="nas",job="truenas",op="merged_writes"} 0
disk_io{disk="sdc",instance="nas",job="truenas",op="reads"} 226071.11
disk_io{disk="sdc",instance="nas",job="truenas",op="writes"} -94.72043
disk_io{disk="sdd",instance="nas",job="truenas",op="discards"} 0
disk_io{disk="sdd",instance="nas",job="truenas",op="merged_discards"} 0
disk_io{disk="sdd",instance="nas",job="truenas",op="merged_reads"} 0
disk_io{disk="sdd",instance="nas",job="truenas",op="merged_writes"} 0
disk_io{disk="sdd",instance="nas",job="truenas",op="reads"} 0
disk_io{disk="sdd",instance="nas",job="truenas",op="writes"} 0
disk_io{disk="sde",instance="nas",job="truenas",op="discards"} 0
disk_io{disk="sde",instance="nas",job="truenas",op="merged_discards"} 0
disk_io{disk="sde",instance="nas",job="truenas",op="merged_reads"} 0
disk_io{disk="sde",instance="nas",job="truenas",op="merged_writes"} 0
disk_io{disk="sde",instance="nas",job="truenas",op="reads"} 0
disk_io{disk="sde",instance="nas",job="truenas",op="writes"} 0
disk_io{disk="sdf",instance="nas",job="truenas",op="discards"} 0
disk_io{disk="sdf",instance="nas",job="truenas",op="merged_discards"} 0
disk_io{disk="sdf",instance="nas",job="truenas",op="merged_reads"} 0
disk_io{disk="sdf",instance="nas",job="truenas",op="merged_writes"} 0
disk_io{disk="sdf",instance="nas",job="truenas",op="reads"} 0
disk_io{disk="sdf",instance="nas",job="truenas",op="writes"} 0
disk_io{disk="sdg",instance="nas",job="truenas",op="discards"} 0
disk_io{disk="sdg",instance="nas",job="truenas",op="merged_discards"} 0
disk_io{disk="sdg",instance="nas",job="truenas",op="merged_reads"} 0.1
disk_io{disk="sdg",instance="nas",job="truenas",op="merged_writes"} 0
disk_io{disk="sdg",instance="nas",job="truenas",op="reads"} 121558.308
disk_io{disk="sdg",instance="nas",job="truenas",op="writes"} -48.585266
disk_io{disk="sdh",instance="nas",job="truenas",op="discards"} 0
disk_io{disk="sdh",instance="nas",job="truenas",op="merged_discards"} 0
disk_io{disk="sdh",instance="nas",job="truenas",op="merged_reads"} 0.1
disk_io{disk="sdh",instance="nas",job="truenas",op="merged_writes"} 0
disk_io{disk="sdh",instance="nas",job="truenas",op="reads"} 122205.88
disk_io{disk="sdh",instance="nas",job="truenas",op="writes"} -48.582847
disk_io{disk="sdi",instance="nas",job="truenas",op="discards"} 0
disk_io{disk="sdi",instance="nas",job="truenas",op="merged_discards"} 0
disk_io{disk="sdi",instance="nas",job="truenas",op="merged_reads"} 0
disk_io{disk="sdi",instance="nas",job="truenas",op="merged_writes"} 0
disk_io{disk="sdi",instance="nas",job="truenas",op="reads"} 225219.43
disk_io{disk="sdi",instance="nas",job="truenas",op="writes"} -94.71146
# HELP disk_io_backlog Graphite metric disk_io_backlog
# TYPE disk_io_backlog gauge
disk_io_backlog{disk="sda",instance="nas",job="truenas"} 0
disk_io_backlog{disk="sdb",instance="nas",job="truenas"} 0
disk_io_backlog{disk="sdc",instance="nas",job="truenas"} 2300.5369
disk_io_backlog{disk="sdd",instance="nas",job="truenas"} 0
disk_io_backlog{disk="sde",instance="nas",job="truenas"} 0
disk_io_backlog{disk="sdf",instance="nas",job="truenas"} 0
disk_io_backlog{disk="sdg",instance="nas",job="truenas"} 2921.4833
disk_io_backlog{disk="sdh",instance="nas",job="truenas"} 2733.8474
disk_io_backlog{disk="sdi",instance="nas",job="truenas"} 2885.9619
# HELP disk_io_ops Graphite metric disk_io_ops
# TYPE disk_io_ops gauge
disk_io_ops{disk="sda",instance="nas",job="truenas",op="discards"} 0
disk_io_ops{disk="sda",instance="nas",job="truenas",op="flushes"} 0
disk_io_ops{disk="sda",instance="nas",job="truenas",op="reads"} 0
disk_io_ops{disk="sda",instance="nas",job="truenas",op="writes"} 0
disk_io_ops{disk="sdb",instance="nas",job="truenas",op="discards"} 0
disk_io_ops{disk="sdb",instance="nas",job="truenas",op="flushes"} 0
disk_io_ops{disk="sdb",instance="nas",job="truenas",op="reads"} 0
disk_io_ops{disk="sdb",instance="nas",job="truenas",op="writes"} 0
disk_io_ops{disk="sdc",instance="nas",job="truenas",op="discards"} 0
disk_io_ops{disk="sdc",instance="nas",job="truenas",op="flushes"} 0.3050652
disk_io_ops{disk="sdc",instance="nas",job="truenas",op="reads"} 300.42362
disk_io_ops{disk="sdc",instance="nas",job="truenas",op="writes"} -6.743725
disk_io_ops{disk="sdd",instance="nas",job="truenas",op="discards"} 0
disk_io_ops{disk="sdd",instance="nas",job="truenas",op="flushes"} 0
disk_io_ops{disk="sdd",instance="nas",job="truenas",op="reads"} 0
disk_io_ops{disk="sdd",instance="nas",job="truenas",op="writes"} 0
disk_io_ops{disk="sde",instance="nas",job="truenas",op="discards"} 0
disk_io_ops{disk="sde",instance="nas",job="truenas",op="flushes"} 0
disk_io_ops{disk="sde",instance="nas",job="truenas",op="reads"} 0
disk_io_ops{disk="sde",instance="nas",job="truenas",op="writes"} 0
disk_io_ops{disk="sdf",instance="nas",job="truenas",op="discards"} 0
disk_io_ops{disk="sdf",instance="nas",job="truenas",op="flushes"} 0
disk_io_ops{disk="sdf",instance="nas",job="truenas",op="reads"} 0
disk_io_ops{disk="sdf",instance="nas",job="truenas",op="writes"} 0
disk_io_ops{disk="sdg",instance="nas",job="truenas",op="discards"} 0
disk_io_ops{disk="sdg",instance="nas",job="truenas",op="flushes"} 0.3050962
disk_io_ops{disk="sdg",instance="nas",job="truenas",op="reads"} 120.609079
disk_io_ops{disk="sdg",instance="nas",job="truenas",op="writes"} -4.8764584
disk_io_ops{disk="sdh",instance="nas",job="truenas",op="discards"} 0
disk_io_ops{disk="sdh",instance="nas",job="truenas",op="flushes"} 0.3050805
disk_io_ops{disk="sdh",instance="nas",job="truenas",op="reads"} 134.299097
disk_io_ops{disk="sdh",instance="nas",job="truenas",op="writes"} -4.8762242
disk_io_ops{disk="sdi",instance="nas",job="truenas",op="discards"} 0
disk_io_ops{disk="sdi",instance="nas",job="truenas",op="flushes"} 0.3050354
disk_io_ops{disk="sdi",instance="nas",job="truenas",op="reads"} 220.79128
disk_io_ops{disk="sdi",instance="nas",job="truenas",op="writes"} -6.343175
# HELP disk_io_size Graphite metric disk_io_size
# TYPE disk_io_size gauge
disk_io_size{disk="sda",instance="nas",job="truenas",op="discards"} 0
disk_io_size{disk="sda",instance="nas",job="truenas",op="reads"} 0
disk_io_size{disk="sda",instance="nas",job="truenas",op="writes"} 0
disk_io_size{disk="sdb",instance="nas",job="truenas",op="discards"} 0
disk_io_size{disk="sdb",instance="nas",job="truenas",op="reads"} 0
disk_io_size{disk="sdb",instance="nas",job="truenas",op="writes"} 0
disk_io_size{disk="sdc",instance="nas",job="truenas",op="discards"} 0
disk_io_size{disk="sdc",instance="nas",job="truenas",op="reads"} 765.7
disk_io_size{disk="sdc",instance="nas",job="truenas",op="writes"} -2.9
disk_io_size{disk="sdd",instance="nas",job="truenas",op="discards"} 0
disk_io_size{disk="sdd",instance="nas",job="truenas",op="reads"} 0
disk_io_size{disk="sdd",instance="nas",job="truenas",op="writes"} 0
disk_io_size{disk="sde",instance="nas",job="truenas",op="discards"} 0
disk_io_size{disk="sde",instance="nas",job="truenas",op="reads"} 0
disk_io_size{disk="sde",instance="nas",job="truenas",op="writes"} 0
disk_io_size{disk="sdf",instance="nas",job="truenas",op="discards"} 0
disk_io_size{disk="sdf",instance="nas",job="truenas",op="reads"} 0
disk_io_size{disk="sdf",instance="nas",job="truenas",op="writes"} 0
disk_io_size{disk="sdg",instance="nas",job="truenas",op="discards"} 0
disk_io_size{disk="sdg",instance="nas",job="truenas",op="reads"} 1007.4
disk_io_size{disk="sdg",instance="nas",job="truenas",op="writes"} -1.95
disk_io_size{disk="sdh",instance="nas",job="truenas",op="discards"} 0
disk_io_size{disk="sdh",instance="nas",job="truenas",op="reads"} 917.75
disk_io_size{disk="sdh",instance="nas",job="truenas",op="writes"} -1.95
disk_io_size{disk="sdi",instance="nas",job="truenas",op="discards"} 0
disk_io_size{disk="sdi",instance="nas",job="truenas",op="reads"} 1018.65
disk_io_size{disk="sdi",instance="nas",job="truenas",op="writes"} -3
# HELP disk_iotime Graphite metric disk_iotime
# TYPE disk_iotime gauge
disk_iotime{disk="sda",instance="nas",job="truenas",op="discards"} 0
disk_iotime{disk="sda",instance="nas",job="truenas",op="flushes"} 0
disk_iotime{disk="sda",instance="nas",job="truenas",op="reads"} 0
disk_iotime{disk="sda",instance="nas",job="truenas",op="writes"} 0
disk_iotime{disk="sdb",instance="nas",job="truenas",op="discards"} 0
disk_iotime{disk="sdb",instance="nas",job="truenas",op="flushes"} 0
disk_iotime{disk="sdb",instance="nas",job="truenas",op="reads"} 0
disk_iotime{disk="sdb",instance="nas",job="truenas",op="writes"} 0
disk_iotime{disk="sdc",instance="nas",job="truenas",op="discards"} 0
disk_iotime{disk="sdc",instance="nas",job="truenas",op="flushes"} 7.978989
disk_iotime{disk="sdc",instance="nas",job="truenas",op="reads"} 2282.8548
disk_iotime{disk="sdc",instance="nas",job="truenas",op="writes"} -9.756842
disk_iotime{disk="sdd",instance="nas",job="truenas",op="discards"} 0
disk_iotime{disk="sdd",instance="nas",job="truenas",op="flushes"} 0
disk_iotime{disk="sdd",instance="nas",job="truenas",op="reads"} 0
disk_iotime{disk="sdd",instance="nas",job="truenas",op="writes"} 0
disk_iotime{disk="sde",instance="nas",job="truenas",op="discards"} 0
disk_iotime{disk="sde",instance="nas",job="truenas",op="flushes"} 0
disk_iotime{disk="sde",instance="nas",job="truenas",op="reads"} 0
disk_iotime{disk="sde",instance="nas",job="truenas",op="writes"} 0
disk_iotime{disk="sdf",instance="nas",job="truenas",op="discards"} 0
disk_iotime{disk="sdf",instance="nas",job="truenas",op="flushes"} 0
disk_iotime{disk="sdf",instance="nas",job="truenas",op="reads"} 0
disk_iotime{disk="sdf",instance="nas",job="truenas",op="writes"} 0
disk_iotime{disk="sdg",instance="nas",job="truenas",op="discards"} 0
disk_iotime{disk="sdg",instance="nas",job="truenas",op="flushes"} 8.337409
disk_iotime{disk="sdg",instance="nas",job="truenas",op="reads"} 2903.3416
disk_iotime{disk="sdg",instance="nas",job="truenas",op="writes"} -9.710342
disk_iotime{disk="sdh",instance="nas",job="truenas",op="discards"} 0
disk_iotime{disk="sdh",instance="nas",job="truenas",op="flushes"} 9.236996
disk_iotime{disk="sdh",instance="nas",job="truenas",op="reads"} 2714.0022
disk_iotime{disk="sdh",instance="nas",job="truenas",op="writes"} -10.609866
disk_iotime{disk="sdi",instance="nas",job="truenas",op="discards"} 0
disk_iotime{disk="sdi",instance="nas",job="truenas",op="flushes"} 8.550858
disk_iotime{disk="sdi",instance="nas",job="truenas",op="reads"} 2866.7793
disk_iotime{disk="sdi",instance="nas",job="truenas",op="writes"} -10.63358
# HELP disk_qops Graphite metric disk_qops
# TYPE disk_qops gauge
disk_qops{disk="sdc",instance="nas",job="truenas"} 2
disk_qops{disk="sdg",instance="nas",job="truenas"} 3
disk_qops{disk="sdh",instance="nas",job="truenas"} 2.7
disk_qops{disk="sdi",instance="nas",job="truenas"} 2.5
# HELP disk_svctm Graphite metric disk_svctm
# TYPE disk_svctm gauge
disk_svctm{disk="sda",instance="nas",job="truenas"} 0
disk_svctm{disk="sdb",instance="nas",job="truenas"} 0
disk_svctm{disk="sdc",instance="nas",job="truenas"} 2.2
disk_svctm{disk="sdd",instance="nas",job="truenas"} 0
disk_svctm{disk="sde",instance="nas",job="truenas"} 0
disk_svctm{disk="sdf",instance="nas",job="truenas"} 0
disk_svctm{disk="sdg",instance="nas",job="truenas"} 7.3
disk_svctm{disk="sdh",instance="nas",job="truenas"} 6
disk_svctm{disk="sdi",instance="nas",job="truenas"} 3.7
# HELP disk_temperature Graphite metric disk_temperature
# TYPE disk_temperature gauge
disk_temperature{instance="nas",job="truenas",serial="200926A00B79"} 35
disk_temperature{instance="nas",job="truenas",serial="AA230529S304KG00519"} 40
disk_temperature{instance="nas",job="truenas",serial="AA230529S304KG00760"} 40
disk_temperature{instance="nas",job="truenas",serial="ZDH68VXJ"} 34
disk_temperature{instance="nas",job="truenas",serial="ZDH6ATVR"} 35
disk_temperature{instance="nas",job="truenas",serial="ZR50B2SD"} 45
disk_temperature{instance="nas",job="truenas",serial="ZR5ES506"} 44
disk_temperature{instance="nas",job="truenas",serial="ZR5F3Q6H"} 44
disk_temperature{instance="nas",job="truenas",serial="ZR70G3JY"} 45
# HELP disk_utilization Graphite metric disk_utilization
# TYPE disk_utilization gauge
disk_utilization{disk="sda",instance="nas",job="truenas"} 0
disk_utilization{disk="sdb",instance="nas",job="truenas"} 0
disk_utilization{disk="sdc",instance="nas",job="truenas"} 76
disk_utilization{disk="sdd",instance="nas",job="truenas"} 0
disk_utilization{disk="sde",instance="nas",job="truenas"} 0
disk_utilization{disk="sdf",instance="nas",job="truenas"} 0
disk_utilization{disk="sdg",instance="nas",job="truenas"} 97.1
disk_utilization{disk="sdh",instance="nas",job="truenas"} 90
disk_utilization{disk="sdi",instance="nas",job="truenas"} 94.9
# HELP go_gc_duration_seconds A summary of the wall-time pause (stop-the-world) duration in garbage collection cycles.
# TYPE go_gc_duration_seconds summary
go_gc_duration_seconds{quantile="0"} 2.7703e-05
go_gc_duration_seconds{quantile="0.25"} 5.565e-05
go_gc_duration_seconds{quantile="0.5"} 9.0123e-05
go_gc_duration_seconds{quantile="0.75"} 0.000123545
go_gc_duration_seconds{quantile="1"} 0.001232922
go_gc_duration_seconds_sum 0.058600275
go_gc_duration_seconds_count 563
# HELP go_gc_gogc_percent Heap size target percentage configured by the user, otherwise 100. This value is set by the GOGC environment variable, and the runtime/debug.SetGCPercent function. Sourced from /gc/gogc:percent
# TYPE go_gc_gogc_percent gauge
go_gc_gogc_percent 100
# HELP go_gc_gomemlimit_bytes Go runtime memory limit configured by the user, otherwise math.MaxInt64. This value is set by the GOMEMLIMIT environment variable, and the runtime/debug.SetMemoryLimit function. Sourced from /gc/gomemlimit:bytes
# TYPE go_gc_gomemlimit_bytes gauge
go_gc_gomemlimit_bytes 9.223372036854776e+18
# HELP go_goroutines Number of goroutines that currently exist.
# TYPE go_goroutines gauge
go_goroutines 14
# HELP go_info Information about the Go environment.
# TYPE go_info gauge
go_info{version="go1.23.2"} 1
# HELP go_memstats_alloc_bytes Number of bytes allocated in heap and currently in use. Equals to /memory/classes/heap/objects:bytes.
# TYPE go_memstats_alloc_bytes gauge
go_memstats_alloc_bytes 3.24496e+06
# HELP go_memstats_alloc_bytes_total Total number of bytes allocated in heap until now, even if released already. Equals to /gc/heap/allocs:bytes.
# TYPE go_memstats_alloc_bytes_total counter
go_memstats_alloc_bytes_total 1.047397704e+09
# HELP go_memstats_buck_hash_sys_bytes Number of bytes used by the profiling bucket hash table. Equals to /memory/classes/profiling/buckets:bytes.
# TYPE go_memstats_buck_hash_sys_bytes gauge
go_memstats_buck_hash_sys_bytes 1.479971e+06
# HELP go_memstats_frees_total Total number of heap objects frees. Equals to /gc/heap/frees:objects + /gc/heap/tiny/allocs:objects.
# TYPE go_memstats_frees_total counter
go_memstats_frees_total 1.6343037e+07
# HELP go_memstats_gc_sys_bytes Number of bytes used for garbage collection system metadata. Equals to /memory/classes/metadata/other:bytes.
# TYPE go_memstats_gc_sys_bytes gauge
go_memstats_gc_sys_bytes 2.990616e+06
# HELP go_memstats_heap_alloc_bytes Number of heap bytes allocated and currently in use, same as go_memstats_alloc_bytes. Equals to /memory/classes/heap/objects:bytes.
# TYPE go_memstats_heap_alloc_bytes gauge
go_memstats_heap_alloc_bytes 3.24496e+06
# HELP go_memstats_heap_idle_bytes Number of heap bytes waiting to be used. Equals to /memory/classes/heap/released:bytes + /memory/classes/heap/free:bytes.
# TYPE go_memstats_heap_idle_bytes gauge
go_memstats_heap_idle_bytes 8.282112e+06
# HELP go_memstats_heap_inuse_bytes Number of heap bytes that are in use. Equals to /memory/classes/heap/objects:bytes + /memory/classes/heap/unused:bytes
# TYPE go_memstats_heap_inuse_bytes gauge
go_memstats_heap_inuse_bytes 7.233536e+06
# HELP go_memstats_heap_objects Number of currently allocated objects. Equals to /gc/heap/objects:objects.
# TYPE go_memstats_heap_objects gauge
go_memstats_heap_objects 18792
# HELP go_memstats_heap_released_bytes Number of heap bytes released to OS. Equals to /memory/classes/heap/released:bytes.
# TYPE go_memstats_heap_released_bytes gauge
go_memstats_heap_released_bytes 6.71744e+06
# HELP go_memstats_heap_sys_bytes Number of heap bytes obtained from system. Equals to /memory/classes/heap/objects:bytes + /memory/classes/heap/unused:bytes + /memory/classes/heap/released:bytes + /memory/classes/heap/free:bytes.
# TYPE go_memstats_heap_sys_bytes gauge
go_memstats_heap_sys_bytes 1.5515648e+07
# HELP go_memstats_last_gc_time_seconds Number of seconds since 1970 of last garbage collection.
# TYPE go_memstats_last_gc_time_seconds gauge
go_memstats_last_gc_time_seconds 1.735500743421288e+09
# HELP go_memstats_mallocs_total Total number of heap objects allocated, both live and gc-ed. Semantically a counter version for go_memstats_heap_objects gauge. Equals to /gc/heap/allocs:objects + /gc/heap/tiny/allocs:objects.
# TYPE go_memstats_mallocs_total counter
go_memstats_mallocs_total 1.6361829e+07
# HELP go_memstats_mcache_inuse_bytes Number of bytes in use by mcache structures. Equals to /memory/classes/metadata/mcache/inuse:bytes.
# TYPE go_memstats_mcache_inuse_bytes gauge
go_memstats_mcache_inuse_bytes 12000
# HELP go_memstats_mcache_sys_bytes Number of bytes used for mcache structures obtained from system. Equals to /memory/classes/metadata/mcache/inuse:bytes + /memory/classes/metadata/mcache/free:bytes.
# TYPE go_memstats_mcache_sys_bytes gauge
go_memstats_mcache_sys_bytes 15600
# HELP go_memstats_mspan_inuse_bytes Number of bytes in use by mspan structures. Equals to /memory/classes/metadata/mspan/inuse:bytes.
# TYPE go_memstats_mspan_inuse_bytes gauge
go_memstats_mspan_inuse_bytes 228480
# HELP go_memstats_mspan_sys_bytes Number of bytes used for mspan structures obtained from system. Equals to /memory/classes/metadata/mspan/inuse:bytes + /memory/classes/metadata/mspan/free:bytes.
# TYPE go_memstats_mspan_sys_bytes gauge
go_memstats_mspan_sys_bytes 277440
# HELP go_memstats_next_gc_bytes Number of heap bytes when next garbage collection will take place. Equals to /gc/heap/goal:bytes.
# TYPE go_memstats_next_gc_bytes gauge
go_memstats_next_gc_bytes 6.715328e+06
# HELP go_memstats_other_sys_bytes Number of bytes used for other system allocations. Equals to /memory/classes/other:bytes.
# TYPE go_memstats_other_sys_bytes gauge
go_memstats_other_sys_bytes 2.417949e+06
# HELP go_memstats_stack_inuse_bytes Number of bytes obtained from system for stack allocator in non-CGO environments. Equals to /memory/classes/heap/stacks:bytes.
# TYPE go_memstats_stack_inuse_bytes gauge
go_memstats_stack_inuse_bytes 1.245184e+06
# HELP go_memstats_stack_sys_bytes Number of bytes obtained from system for stack allocator. Equals to /memory/classes/heap/stacks:bytes + /memory/classes/os-stacks:bytes.
# TYPE go_memstats_stack_sys_bytes gauge
go_memstats_stack_sys_bytes 1.245184e+06
# HELP go_memstats_sys_bytes Number of bytes obtained from system. Equals to /memory/classes/total:byte.
# TYPE go_memstats_sys_bytes gauge
go_memstats_sys_bytes 2.3942408e+07
# HELP go_sched_gomaxprocs_threads The current runtime.GOMAXPROCS setting, or the number of operating system threads that can execute user-level Go code simultaneously. Sourced from /sched/gomaxprocs:threads
# TYPE go_sched_gomaxprocs_threads gauge
go_sched_gomaxprocs_threads 10
# HELP go_threads Number of OS threads created.
# TYPE go_threads gauge
go_threads 13
# HELP graphite_exporter_build_info A metric with a constant '1' value labeled by version, revision, branch, goversion from which graphite_exporter was built, and the goos and goarch for the build.
# TYPE graphite_exporter_build_info gauge
graphite_exporter_build_info{branch="HEAD",goarch="amd64",goos="linux",goversion="go1.23.2",revision="27e7320279ddd399784af59a45fcb431273ea4c9",tags="unknown",version="0.16.0"} 1
# HELP graphite_last_processed_timestamp_seconds Unix timestamp of the last processed graphite metric.
# TYPE graphite_last_processed_timestamp_seconds gauge
graphite_last_processed_timestamp_seconds 1.7355007394903016e+09
# HELP graphite_sample_expiry_seconds How long in seconds a metric sample is valid for.
# TYPE graphite_sample_expiry_seconds gauge
graphite_sample_expiry_seconds 300
# HELP graphite_tag_parse_failures Total count of samples with invalid tags
# TYPE graphite_tag_parse_failures counter
graphite_tag_parse_failures 0
# HELP interface_carrierstate Graphite metric interface_carrierstate
# TYPE interface_carrierstate gauge
interface_carrierstate{instance="nas",interface="bond0",job="truenas",state="down"} 0
interface_carrierstate{instance="nas",interface="bond0",job="truenas",state="up"} 1
interface_carrierstate{instance="nas",interface="br_9ec03ffe33bb",job="truenas",state="down"} 0
interface_carrierstate{instance="nas",interface="br_9ec03ffe33bb",job="truenas",state="up"} 1
interface_carrierstate{instance="nas",interface="docker0",job="truenas",state="down"} 1
interface_carrierstate{instance="nas",interface="docker0",job="truenas",state="up"} 0
interface_carrierstate{instance="nas",interface="enp1s0f0",job="truenas",state="down"} 1
interface_carrierstate{instance="nas",interface="enp1s0f0",job="truenas",state="up"} 0
interface_carrierstate{instance="nas",interface="enp1s0f1",job="truenas",state="down"} 0
interface_carrierstate{instance="nas",interface="enp1s0f1",job="truenas",state="up"} 1
interface_carrierstate{instance="nas",interface="enp7s0",job="truenas",state="down"} 0
interface_carrierstate{instance="nas",interface="enp7s0",job="truenas",state="up"} 1
interface_carrierstate{instance="nas",interface="vlan1000",job="truenas",state="down"} 0
interface_carrierstate{instance="nas",interface="vlan1000",job="truenas",state="up"} 1
# HELP interface_duplex Graphite metric interface_duplex
# TYPE interface_duplex gauge
interface_duplex{instance="nas",interface="enp1s0f0",job="truenas",state="full"} 0
interface_duplex{instance="nas",interface="enp1s0f0",job="truenas",state="half"} 0
interface_duplex{instance="nas",interface="enp1s0f0",job="truenas",state="unknown"} 1
interface_duplex{instance="nas",interface="enp1s0f1",job="truenas",state="full"} 1
interface_duplex{instance="nas",interface="enp1s0f1",job="truenas",state="half"} 0
interface_duplex{instance="nas",interface="enp1s0f1",job="truenas",state="unknown"} 0
interface_duplex{instance="nas",interface="enp7s0",job="truenas",state="full"} 1
interface_duplex{instance="nas",interface="enp7s0",job="truenas",state="half"} 0
interface_duplex{instance="nas",interface="enp7s0",job="truenas",state="unknown"} 0
interface_duplex{instance="nas",interface="enp8s0",job="truenas",state="full"} 0
interface_duplex{instance="nas",interface="enp8s0",job="truenas",state="half"} 0
interface_duplex{instance="nas",interface="enp8s0",job="truenas",state="unknown"} 1
# HELP interface_io Graphite metric interface_io
# TYPE interface_io gauge
interface_io{instance="nas",interface="bond0",job="truenas",op="received"} 9.4960595
interface_io{instance="nas",interface="bond0",job="truenas",op="sent"} -47.8993969
interface_io{instance="nas",interface="br_9ec03ffe33bb",job="truenas",op="received"} 0
interface_io{instance="nas",interface="br_9ec03ffe33bb",job="truenas",op="sent"} 0
interface_io{instance="nas",interface="enp1s0f1",job="truenas",op="received"} 9.4960306
interface_io{instance="nas",interface="enp1s0f1",job="truenas",op="sent"} -47.8994004
interface_io{instance="nas",interface="enp7s0",job="truenas",op="received"} 0.701372
interface_io{instance="nas",interface="enp7s0",job="truenas",op="sent"} 0
interface_io{instance="nas",interface="vlan1000",job="truenas",op="received"} 8.3221932
interface_io{instance="nas",interface="vlan1000",job="truenas",op="sent"} -46.2626038
# HELP interface_mtu Graphite metric interface_mtu
# TYPE interface_mtu gauge
interface_mtu{instance="nas",interface="bond0",job="truenas"} 1500
interface_mtu{instance="nas",interface="br_9ec03ffe33bb",job="truenas"} 1500
interface_mtu{instance="nas",interface="docker0",job="truenas"} 1500
interface_mtu{instance="nas",interface="enp1s0f0",job="truenas"} 1500
interface_mtu{instance="nas",interface="enp1s0f1",job="truenas"} 1500
interface_mtu{instance="nas",interface="enp7s0",job="truenas"} 1500
interface_mtu{instance="nas",interface="enp8s0",job="truenas"} 1500
interface_mtu{instance="nas",interface="vlan1000",job="truenas"} 1500
# HELP interface_operationstate Graphite metric interface_operationstate
# TYPE interface_operationstate gauge
interface_operationstate{instance="nas",interface="bond0",job="truenas",state="dormant"} 0
interface_operationstate{instance="nas",interface="bond0",job="truenas",state="down"} 0
interface_operationstate{instance="nas",interface="bond0",job="truenas",state="lowerlayerdown"} 0
interface_operationstate{instance="nas",interface="bond0",job="truenas",state="notpresent"} 0
interface_operationstate{instance="nas",interface="bond0",job="truenas",state="testing"} 0
interface_operationstate{instance="nas",interface="bond0",job="truenas",state="unknown"} 0
interface_operationstate{instance="nas",interface="bond0",job="truenas",state="up"} 1
interface_operationstate{instance="nas",interface="br_9ec03ffe33bb",job="truenas",state="dormant"} 0
interface_operationstate{instance="nas",interface="br_9ec03ffe33bb",job="truenas",state="down"} 0
interface_operationstate{instance="nas",interface="br_9ec03ffe33bb",job="truenas",state="lowerlayerdown"} 0
interface_operationstate{instance="nas",interface="br_9ec03ffe33bb",job="truenas",state="notpresent"} 0
interface_operationstate{instance="nas",interface="br_9ec03ffe33bb",job="truenas",state="testing"} 0
interface_operationstate{instance="nas",interface="br_9ec03ffe33bb",job="truenas",state="unknown"} 0
interface_operationstate{instance="nas",interface="br_9ec03ffe33bb",job="truenas",state="up"} 1
interface_operationstate{instance="nas",interface="docker0",job="truenas",state="dormant"} 0
interface_operationstate{instance="nas",interface="docker0",job="truenas",state="down"} 1
interface_operationstate{instance="nas",interface="docker0",job="truenas",state="lowerlayerdown"} 0
interface_operationstate{instance="nas",interface="docker0",job="truenas",state="notpresent"} 0
interface_operationstate{instance="nas",interface="docker0",job="truenas",state="testing"} 0
interface_operationstate{instance="nas",interface="docker0",job="truenas",state="unknown"} 0
interface_operationstate{instance="nas",interface="docker0",job="truenas",state="up"} 0
interface_operationstate{instance="nas",interface="enp1s0f0",job="truenas",state="dormant"} 0
interface_operationstate{instance="nas",interface="enp1s0f0",job="truenas",state="down"} 1
interface_operationstate{instance="nas",interface="enp1s0f0",job="truenas",state="lowerlayerdown"} 0
interface_operationstate{instance="nas",interface="enp1s0f0",job="truenas",state="notpresent"} 0
interface_operationstate{instance="nas",interface="enp1s0f0",job="truenas",state="testing"} 0
interface_operationstate{instance="nas",interface="enp1s0f0",job="truenas",state="unknown"} 0
interface_operationstate{instance="nas",interface="enp1s0f0",job="truenas",state="up"} 0
interface_operationstate{instance="nas",interface="enp1s0f1",job="truenas",state="dormant"} 0
interface_operationstate{instance="nas",interface="enp1s0f1",job="truenas",state="down"} 0
interface_operationstate{instance="nas",interface="enp1s0f1",job="truenas",state="lowerlayerdown"} 0
interface_operationstate{instance="nas",interface="enp1s0f1",job="truenas",state="notpresent"} 0
interface_operationstate{instance="nas",interface="enp1s0f1",job="truenas",state="testing"} 0
interface_operationstate{instance="nas",interface="enp1s0f1",job="truenas",state="unknown"} 0
interface_operationstate{instance="nas",interface="enp1s0f1",job="truenas",state="up"} 1
interface_operationstate{instance="nas",interface="enp7s0",job="truenas",state="dormant"} 0
interface_operationstate{instance="nas",interface="enp7s0",job="truenas",state="down"} 0
interface_operationstate{instance="nas",interface="enp7s0",job="truenas",state="lowerlayerdown"} 0
interface_operationstate{instance="nas",interface="enp7s0",job="truenas",state="notpresent"} 0
interface_operationstate{instance="nas",interface="enp7s0",job="truenas",state="testing"} 0
interface_operationstate{instance="nas",interface="enp7s0",job="truenas",state="unknown"} 0
interface_operationstate{instance="nas",interface="enp7s0",job="truenas",state="up"} 1
interface_operationstate{instance="nas",interface="enp8s0",job="truenas",state="dormant"} 0
interface_operationstate{instance="nas",interface="enp8s0",job="truenas",state="down"} 1
interface_operationstate{instance="nas",interface="enp8s0",job="truenas",state="lowerlayerdown"} 0
interface_operationstate{instance="nas",interface="enp8s0",job="truenas",state="notpresent"} 0
interface_operationstate{instance="nas",interface="enp8s0",job="truenas",state="testing"} 0
interface_operationstate{instance="nas",interface="enp8s0",job="truenas",state="unknown"} 0
interface_operationstate{instance="nas",interface="enp8s0",job="truenas",state="up"} 0
interface_operationstate{instance="nas",interface="vlan1000",job="truenas",state="dormant"} 0
interface_operationstate{instance="nas",interface="vlan1000",job="truenas",state="down"} 0
interface_operationstate{instance="nas",interface="vlan1000",job="truenas",state="lowerlayerdown"} 0
interface_operationstate{instance="nas",interface="vlan1000",job="truenas",state="notpresent"} 0
interface_operationstate{instance="nas",interface="vlan1000",job="truenas",state="testing"} 0
interface_operationstate{instance="nas",interface="vlan1000",job="truenas",state="unknown"} 0
interface_operationstate{instance="nas",interface="vlan1000",job="truenas",state="up"} 1
# HELP interface_packets Graphite metric interface_packets
# TYPE interface_packets gauge
interface_packets{instance="nas",interface="bond0",job="truenas",op="multicast"} 4.0191295
interface_packets{instance="nas",interface="bond0",job="truenas",op="received"} 10.4810628
interface_packets{instance="nas",interface="bond0",job="truenas",op="sent"} -7.3000818
interface_packets{instance="nas",interface="br_9ec03ffe33bb",job="truenas",op="multicast"} 0
interface_packets{instance="nas",interface="br_9ec03ffe33bb",job="truenas",op="received"} 0
interface_packets{instance="nas",interface="br_9ec03ffe33bb",job="truenas",op="sent"} 0
interface_packets{instance="nas",interface="enp1s0f1",job="truenas",op="multicast"} 4.019188
interface_packets{instance="nas",interface="enp1s0f1",job="truenas",op="received"} 10.4810026
interface_packets{instance="nas",interface="enp1s0f1",job="truenas",op="sent"} -7.3000815
interface_packets{instance="nas",interface="enp7s0",job="truenas",op="multicast"} 35.2700931
interface_packets{instance="nas",interface="enp7s0",job="truenas",op="received"} 1.4612566
interface_packets{instance="nas",interface="enp7s0",job="truenas",op="sent"} 0
interface_packets{instance="nas",interface="vlan1000",job="truenas",op="multicast"} 4.246048
interface_packets{instance="nas",interface="vlan1000",job="truenas",op="received"} 10.4811179
interface_packets{instance="nas",interface="vlan1000",job="truenas",op="sent"} -4.2000815
# HELP interface_speed Graphite metric interface_speed
# TYPE interface_speed gauge
interface_speed{instance="nas",interface="enp1s0f1",job="truenas"} 1e+07
interface_speed{instance="nas",interface="enp7s0",job="truenas"} 1e+06
# HELP interrupts Graphite metric interrupts
# TYPE interrupts gauge
interrupts{instance="nas",job="truenas",kind="hard"} 1449.44403
interrupts{instance="nas",job="truenas",kind="soft"} 0.5348656
# HELP memory_available Graphite metric memory_available
# TYPE memory_available gauge
memory_available{instance="nas",job="truenas",kind="avail"} 26797.757
# HELP memory_committed Graphite metric memory_committed
# TYPE memory_committed gauge
memory_committed{instance="nas",job="truenas",kind="Committed_AS"} 3578.023
# HELP memory_kernel Graphite metric memory_kernel
# TYPE memory_kernel gauge
memory_kernel{instance="nas",job="truenas",kind="KernelStack"} 8.6234375
memory_kernel{instance="nas",job="truenas",kind="PageTables"} 9.285156
memory_kernel{instance="nas",job="truenas",kind="Percpu"} 2.15625
memory_kernel{instance="nas",job="truenas",kind="Slab"} 2351.9485
memory_kernel{instance="nas",job="truenas",kind="VmallocUsed"} 360.47893
# HELP memory_slab Graphite metric memory_slab
# TYPE memory_slab gauge
memory_slab{instance="nas",job="truenas",kind="reclaimable"} 304.10355
memory_slab{instance="nas",job="truenas",kind="unreclaimable"} 2047.845
# HELP memory_transparent_hugepages Graphite metric memory_transparent_hugepages
# TYPE memory_transparent_hugepages gauge
memory_transparent_hugepages{instance="nas",job="truenas",kind="anonymous"} 1089.2
memory_transparent_hugepages{instance="nas",job="truenas",kind="shmem"} 0
# HELP memory_writeback Graphite metric memory_writeback
# TYPE memory_writeback gauge
memory_writeback{instance="nas",job="truenas",kind="Bounce"} 0
memory_writeback{instance="nas",job="truenas",kind="Dirty"} 0
memory_writeback{instance="nas",job="truenas",kind="FuseWriteback"} 0
memory_writeback{instance="nas",job="truenas",kind="NfsWriteback"} 0
memory_writeback{instance="nas",job="truenas",kind="Writeback"} 0
# HELP nfs_net Graphite metric nfs_net
# TYPE nfs_net gauge
nfs_net{instance="nas",job="truenas",op="tcp"} 0
nfs_net{instance="nas",job="truenas",op="udp"} 0
# HELP nfs_proc4 Graphite metric nfs_proc4
# TYPE nfs_proc4 gauge
nfs_proc4{instance="nas",job="truenas",op="null"} 0
nfs_proc4{instance="nas",job="truenas",op="read"} 0
# HELP nfs_proc4ops Graphite metric nfs_proc4ops
# TYPE nfs_proc4ops gauge
nfs_proc4ops{instance="nas",job="truenas",op="access"} 0
nfs_proc4ops{instance="nas",job="truenas",op="allocate"} 0
nfs_proc4ops{instance="nas",job="truenas",op="backchannel_ctl"} 0
nfs_proc4ops{instance="nas",job="truenas",op="bind_conn_to_session"} 0
nfs_proc4ops{instance="nas",job="truenas",op="close"} 0
nfs_proc4ops{instance="nas",job="truenas",op="commit"} 0
nfs_proc4ops{instance="nas",job="truenas",op="copy"} 0
nfs_proc4ops{instance="nas",job="truenas",op="copy_notify"} 0
nfs_proc4ops{instance="nas",job="truenas",op="create"} 0
nfs_proc4ops{instance="nas",job="truenas",op="create_session"} 0
nfs_proc4ops{instance="nas",job="truenas",op="deallocate"} 0
nfs_proc4ops{instance="nas",job="truenas",op="delegpurge"} 0
nfs_proc4ops{instance="nas",job="truenas",op="delegreturn"} 0
nfs_proc4ops{instance="nas",job="truenas",op="destroy_clientid"} 0
nfs_proc4ops{instance="nas",job="truenas",op="destroy_session"} 0
nfs_proc4ops{instance="nas",job="truenas",op="exchange_id"} 0
nfs_proc4ops{instance="nas",job="truenas",op="free_stateid"} 0
nfs_proc4ops{instance="nas",job="truenas",op="future_op2"} 0
nfs_proc4ops{instance="nas",job="truenas",op="get_dir_delegation"} 0
nfs_proc4ops{instance="nas",job="truenas",op="getattr"} 0
nfs_proc4ops{instance="nas",job="truenas",op="getdeviceinfo"} 0
nfs_proc4ops{instance="nas",job="truenas",op="getdevicelist"} 0
nfs_proc4ops{instance="nas",job="truenas",op="getfh"} 0
nfs_proc4ops{instance="nas",job="truenas",op="ioadvise"} 0
nfs_proc4ops{instance="nas",job="truenas",op="layoutcommit"} 0
nfs_proc4ops{instance="nas",job="truenas",op="layouterror"} 0
nfs_proc4ops{instance="nas",job="truenas",op="layoutget"} 0
nfs_proc4ops{instance="nas",job="truenas",op="layoutreturn"} 0
nfs_proc4ops{instance="nas",job="truenas",op="layoutstats"} 0
nfs_proc4ops{instance="nas",job="truenas",op="link"} 0
nfs_proc4ops{instance="nas",job="truenas",op="lock"} 0
nfs_proc4ops{instance="nas",job="truenas",op="lockt"} 0
nfs_proc4ops{instance="nas",job="truenas",op="locku"} 0
nfs_proc4ops{instance="nas",job="truenas",op="lookup"} 0
nfs_proc4ops{instance="nas",job="truenas",op="lookup_root"} 0
nfs_proc4ops{instance="nas",job="truenas",op="nverify"} 0
nfs_proc4ops{instance="nas",job="truenas",op="offload_cancel"} 0
nfs_proc4ops{instance="nas",job="truenas",op="offload_status"} 0
nfs_proc4ops{instance="nas",job="truenas",op="open"} 0
nfs_proc4ops{instance="nas",job="truenas",op="open_confirm"} 0
nfs_proc4ops{instance="nas",job="truenas",op="open_downgrade"} 0
nfs_proc4ops{instance="nas",job="truenas",op="openattr"} 0
nfs_proc4ops{instance="nas",job="truenas",op="putfh"} 0
nfs_proc4ops{instance="nas",job="truenas",op="putpubfh"} 0
nfs_proc4ops{instance="nas",job="truenas",op="putrootfh"} 0
nfs_proc4ops{instance="nas",job="truenas",op="read"} 0
nfs_proc4ops{instance="nas",job="truenas",op="read_plus"} 0
nfs_proc4ops{instance="nas",job="truenas",op="readdir"} 0
nfs_proc4ops{instance="nas",job="truenas",op="readlink"} 0
nfs_proc4ops{instance="nas",job="truenas",op="reclaim_complete"} 0
nfs_proc4ops{instance="nas",job="truenas",op="release_lockowner"} 0
nfs_proc4ops{instance="nas",job="truenas",op="remove"} 0
nfs_proc4ops{instance="nas",job="truenas",op="rename"} 0
nfs_proc4ops{instance="nas",job="truenas",op="renew"} 0
nfs_proc4ops{instance="nas",job="truenas",op="restorefh"} 0
nfs_proc4ops{instance="nas",job="truenas",op="savefh"} 0
nfs_proc4ops{instance="nas",job="truenas",op="secinfo"} 0
nfs_proc4ops{instance="nas",job="truenas",op="secinfo_no_name"} 0
nfs_proc4ops{instance="nas",job="truenas",op="seek"} 0
nfs_proc4ops{instance="nas",job="truenas",op="sequence"} 0
nfs_proc4ops{instance="nas",job="truenas",op="set_ssv"} 0
nfs_proc4ops{instance="nas",job="truenas",op="setattr"} 0
nfs_proc4ops{instance="nas",job="truenas",op="setclientid"} 0
nfs_proc4ops{instance="nas",job="truenas",op="setclientid_confirm"} 0
nfs_proc4ops{instance="nas",job="truenas",op="test_stateid"} 0
nfs_proc4ops{instance="nas",job="truenas",op="unused_op0"} 0
nfs_proc4ops{instance="nas",job="truenas",op="unused_op1"} 0
nfs_proc4ops{instance="nas",job="truenas",op="verify"} 0
nfs_proc4ops{instance="nas",job="truenas",op="want_delegation"} 0
nfs_proc4ops{instance="nas",job="truenas",op="write"} 0
nfs_proc4ops{instance="nas",job="truenas",op="write_same"} 0
# HELP nfs_readcache Graphite metric nfs_readcache
# TYPE nfs_readcache gauge
nfs_readcache{instance="nas",job="truenas",op="hits"} 0
nfs_readcache{instance="nas",job="truenas",op="misses"} 0
nfs_readcache{instance="nas",job="truenas",op="nocache"} 0
# HELP nfs_rpc Graphite metric nfs_rpc
# TYPE nfs_rpc gauge
nfs_rpc{instance="nas",job="truenas",op="bad_auth"} 0
nfs_rpc{instance="nas",job="truenas",op="bad_format"} 0
nfs_rpc{instance="nas",job="truenas",op="calls"} 0
# HELP nfs_threads Graphite metric nfs_threads
# TYPE nfs_threads gauge
nfs_threads{instance="nas",job="truenas",op="threads"} 4
# HELP physical_memory Graphite metric physical_memory
# TYPE physical_memory gauge
physical_memory{instance="nas",job="truenas",kind="buffers"} 0.125
physical_memory{instance="nas",job="truenas",kind="cached"} 3663.105
physical_memory{instance="nas",job="truenas",kind="free"} 23593.308
physical_memory{instance="nas",job="truenas",kind="used"} 4823.3277
# HELP process_cpu_seconds_total Total user and system CPU time spent in seconds.
# TYPE process_cpu_seconds_total counter
process_cpu_seconds_total 20.05
# HELP process_max_fds Maximum number of open file descriptors.
# TYPE process_max_fds gauge
process_max_fds 1.048576e+06
# HELP process_network_receive_bytes_total Number of bytes received by the process over the network.
# TYPE process_network_receive_bytes_total counter
process_network_receive_bytes_total 1.9696229e+07
# HELP process_network_transmit_bytes_total Number of bytes sent by the process over the network.
# TYPE process_network_transmit_bytes_total counter
process_network_transmit_bytes_total 922392
# HELP process_open_fds Number of open file descriptors.
# TYPE process_open_fds gauge
process_open_fds 12
# HELP process_resident_memory_bytes Resident memory size in bytes.
# TYPE process_resident_memory_bytes gauge
process_resident_memory_bytes 2.1295104e+07
# HELP process_start_time_seconds Start time of the process since unix epoch in seconds.
# TYPE process_start_time_seconds gauge
process_start_time_seconds 1.73549705338e+09
# HELP process_virtual_memory_bytes Virtual memory size in bytes.
# TYPE process_virtual_memory_bytes gauge
process_virtual_memory_bytes 1.27029248e+09
# HELP process_virtual_memory_max_bytes Maximum amount of virtual memory available in bytes.
# TYPE process_virtual_memory_max_bytes gauge
process_virtual_memory_max_bytes 1.8446744073709552e+19
# HELP processes Graphite metric processes
# TYPE processes gauge
processes{instance="nas",job="truenas",kind="active"} 548.9
processes{instance="nas",job="truenas",kind="blocked"} -0.1
processes{instance="nas",job="truenas",kind="running"} 1.5
# HELP processes_forks Graphite metric processes_forks
# TYPE processes_forks gauge
processes_forks{instance="nas",job="truenas"} 0.3580023
# HELP promhttp_metric_handler_requests_in_flight Current number of scrapes being served.
# TYPE promhttp_metric_handler_requests_in_flight gauge
promhttp_metric_handler_requests_in_flight 1
# HELP promhttp_metric_handler_requests_total Total number of scrapes by HTTP status code.
# TYPE promhttp_metric_handler_requests_total counter
promhttp_metric_handler_requests_total{code="200"} 62
promhttp_metric_handler_requests_total{code="500"} 0
promhttp_metric_handler_requests_total{code="503"} 0
# HELP services_cpu Graphite metric services_cpu
# TYPE services_cpu gauge
services_cpu{instance="nas",job="truenas",service="avahi_daemon"} 0.045992
services_cpu{instance="nas",job="truenas",service="certmonger"} 0
services_cpu{instance="nas",job="truenas",service="chrony"} 0
services_cpu{instance="nas",job="truenas",service="containerd"} 0.0834046
services_cpu{instance="nas",job="truenas",service="cron"} 0
services_cpu{instance="nas",job="truenas",service="dbus"} 0
services_cpu{instance="nas",job="truenas",service="docker"} 0.0184915
services_cpu{instance="nas",job="truenas",service="gssproxy"} 0.00047
services_cpu{instance="nas",job="truenas",service="middlewared"} 0.056596
services_cpu{instance="nas",job="truenas",service="netdata"} 4.4812524
services_cpu{instance="nas",job="truenas",service="nfs_blkmap"} 0
services_cpu{instance="nas",job="truenas",service="nfs_idmapd"} 0
services_cpu{instance="nas",job="truenas",service="nfs_mountd"} 0
services_cpu{instance="nas",job="truenas",service="nfsdcld"} 0
services_cpu{instance="nas",job="truenas",service="nginx"} 0
services_cpu{instance="nas",job="truenas",service="nmbd"} 0.00298
services_cpu{instance="nas",job="truenas",service="nscd"} 0.069719
services_cpu{instance="nas",job="truenas",service="rpc_statd"} 0
services_cpu{instance="nas",job="truenas",service="rpcbind"} 0.00049
services_cpu{instance="nas",job="truenas",service="scst"} 0
services_cpu{instance="nas",job="truenas",service="smartmontools"} 0
services_cpu{instance="nas",job="truenas",service="smbd"} 0.0835412
services_cpu{instance="nas",job="truenas",service="syslog_ng"} 0
services_cpu{instance="nas",job="truenas",service="systemd_journald"} 0
services_cpu{instance="nas",job="truenas",service="systemd_logind"} 0
services_cpu{instance="nas",job="truenas",service="systemd_udevd"} 0
services_cpu{instance="nas",job="truenas",service="winbind"} 0.0008767
services_cpu{instance="nas",job="truenas",service="wsdd"} 0
services_cpu{instance="nas",job="truenas",service="zfs_zed"} 0
# HELP services_io Graphite metric services_io
# TYPE services_io gauge
services_io{instance="nas",job="truenas",op="read",service="avahi_daemon"} 0
services_io{instance="nas",job="truenas",op="read",service="certmonger"} 0
services_io{instance="nas",job="truenas",op="read",service="chrony"} 0
services_io{instance="nas",job="truenas",op="read",service="containerd"} 0
services_io{instance="nas",job="truenas",op="read",service="cron"} 0
services_io{instance="nas",job="truenas",op="read",service="dbus"} 0
services_io{instance="nas",job="truenas",op="read",service="docker"} 0
services_io{instance="nas",job="truenas",op="read",service="gssproxy"} 0
services_io{instance="nas",job="truenas",op="read",service="middlewared"} 0
services_io{instance="nas",job="truenas",op="read",service="netdata"} 0
services_io{instance="nas",job="truenas",op="read",service="nfs_blkmap"} 0
services_io{instance="nas",job="truenas",op="read",service="nfs_idmapd"} 0
services_io{instance="nas",job="truenas",op="read",service="nfs_mountd"} 0
services_io{instance="nas",job="truenas",op="read",service="nfsdcld"} 0
services_io{instance="nas",job="truenas",op="read",service="nginx"} 0
services_io{instance="nas",job="truenas",op="read",service="nmbd"} 0
services_io{instance="nas",job="truenas",op="read",service="nscd"} 0
services_io{instance="nas",job="truenas",op="read",service="rpc_statd"} 0
services_io{instance="nas",job="truenas",op="read",service="rpcbind"} 0
services_io{instance="nas",job="truenas",op="read",service="scst"} 0
services_io{instance="nas",job="truenas",op="read",service="smartmontools"} 0
services_io{instance="nas",job="truenas",op="read",service="smbd"} 0
services_io{instance="nas",job="truenas",op="read",service="syslog_ng"} 0
services_io{instance="nas",job="truenas",op="read",service="systemd_journald"} 0
services_io{instance="nas",job="truenas",op="read",service="systemd_logind"} 0
services_io{instance="nas",job="truenas",op="read",service="systemd_udevd"} 0
services_io{instance="nas",job="truenas",op="read",service="winbind"} 0
services_io{instance="nas",job="truenas",op="read",service="wsdd"} 0
services_io{instance="nas",job="truenas",op="read",service="zfs_zed"} 0
services_io{instance="nas",job="truenas",op="write",service="avahi_daemon"} 0
services_io{instance="nas",job="truenas",op="write",service="certmonger"} 0
services_io{instance="nas",job="truenas",op="write",service="chrony"} 0
services_io{instance="nas",job="truenas",op="write",service="containerd"} 0
services_io{instance="nas",job="truenas",op="write",service="cron"} 0
services_io{instance="nas",job="truenas",op="write",service="dbus"} 0
services_io{instance="nas",job="truenas",op="write",service="docker"} 0
services_io{instance="nas",job="truenas",op="write",service="gssproxy"} 0
services_io{instance="nas",job="truenas",op="write",service="middlewared"} 0
services_io{instance="nas",job="truenas",op="write",service="netdata"} 0
services_io{instance="nas",job="truenas",op="write",service="nfs_blkmap"} 0
services_io{instance="nas",job="truenas",op="write",service="nfs_idmapd"} 0
services_io{instance="nas",job="truenas",op="write",service="nfs_mountd"} 0
services_io{instance="nas",job="truenas",op="write",service="nfsdcld"} 0
services_io{instance="nas",job="truenas",op="write",service="nginx"} 0
services_io{instance="nas",job="truenas",op="write",service="nmbd"} 0
services_io{instance="nas",job="truenas",op="write",service="nscd"} 0
services_io{instance="nas",job="truenas",op="write",service="rpc_statd"} 0
services_io{instance="nas",job="truenas",op="write",service="rpcbind"} 0
services_io{instance="nas",job="truenas",op="write",service="scst"} 0
services_io{instance="nas",job="truenas",op="write",service="smartmontools"} 0
services_io{instance="nas",job="truenas",op="write",service="smbd"} 0
services_io{instance="nas",job="truenas",op="write",service="syslog_ng"} 0
services_io{instance="nas",job="truenas",op="write",service="systemd_journald"} 0
services_io{instance="nas",job="truenas",op="write",service="systemd_logind"} 0
services_io{instance="nas",job="truenas",op="write",service="systemd_udevd"} 0
services_io{instance="nas",job="truenas",op="write",service="winbind"} 0
services_io{instance="nas",job="truenas",op="write",service="wsdd"} 0
services_io{instance="nas",job="truenas",op="write",service="zfs_zed"} 0
# HELP services_iops Graphite metric services_iops
# TYPE services_iops gauge
services_iops{instance="nas",job="truenas",op="read",service="avahi_daemon"} 0
services_iops{instance="nas",job="truenas",op="read",service="certmonger"} 0
services_iops{instance="nas",job="truenas",op="read",service="chrony"} 0
services_iops{instance="nas",job="truenas",op="read",service="containerd"} 0
services_iops{instance="nas",job="truenas",op="read",service="cron"} 0
services_iops{instance="nas",job="truenas",op="read",service="dbus"} 0
services_iops{instance="nas",job="truenas",op="read",service="docker"} 0
services_iops{instance="nas",job="truenas",op="read",service="gssproxy"} 0
services_iops{instance="nas",job="truenas",op="read",service="middlewared"} 0
services_iops{instance="nas",job="truenas",op="read",service="netdata"} 0
services_iops{instance="nas",job="truenas",op="read",service="nfs_blkmap"} 0
services_iops{instance="nas",job="truenas",op="read",service="nfs_idmapd"} 0
services_iops{instance="nas",job="truenas",op="read",service="nfs_mountd"} 0
services_iops{instance="nas",job="truenas",op="read",service="nfsdcld"} 0
services_iops{instance="nas",job="truenas",op="read",service="nginx"} 0
services_iops{instance="nas",job="truenas",op="read",service="nmbd"} 0
services_iops{instance="nas",job="truenas",op="read",service="nscd"} 0
services_iops{instance="nas",job="truenas",op="read",service="rpc_statd"} 0
services_iops{instance="nas",job="truenas",op="read",service="rpcbind"} 0
services_iops{instance="nas",job="truenas",op="read",service="scst"} 0
services_iops{instance="nas",job="truenas",op="read",service="smartmontools"} 0
services_iops{instance="nas",job="truenas",op="read",service="smbd"} 0
services_iops{instance="nas",job="truenas",op="read",service="syslog_ng"} 0
services_iops{instance="nas",job="truenas",op="read",service="systemd_journald"} 0
services_iops{instance="nas",job="truenas",op="read",service="systemd_logind"} 0
services_iops{instance="nas",job="truenas",op="read",service="systemd_udevd"} 0
services_iops{instance="nas",job="truenas",op="read",service="winbind"} 0
services_iops{instance="nas",job="truenas",op="read",service="wsdd"} 0
services_iops{instance="nas",job="truenas",op="read",service="zfs_zed"} 0
services_iops{instance="nas",job="truenas",op="write",service="avahi_daemon"} 0
services_iops{instance="nas",job="truenas",op="write",service="certmonger"} 0
services_iops{instance="nas",job="truenas",op="write",service="chrony"} 0
services_iops{instance="nas",job="truenas",op="write",service="containerd"} 0
services_iops{instance="nas",job="truenas",op="write",service="cron"} 0
services_iops{instance="nas",job="truenas",op="write",service="dbus"} 0
services_iops{instance="nas",job="truenas",op="write",service="docker"} 0
services_iops{instance="nas",job="truenas",op="write",service="gssproxy"} 0
services_iops{instance="nas",job="truenas",op="write",service="middlewared"} 0
services_iops{instance="nas",job="truenas",op="write",service="netdata"} 0
services_iops{instance="nas",job="truenas",op="write",service="nfs_blkmap"} 0
services_iops{instance="nas",job="truenas",op="write",service="nfs_idmapd"} 0
services_iops{instance="nas",job="truenas",op="write",service="nfs_mountd"} 0
services_iops{instance="nas",job="truenas",op="write",service="nfsdcld"} 0
services_iops{instance="nas",job="truenas",op="write",service="nginx"} 0
services_iops{instance="nas",job="truenas",op="write",service="nmbd"} 0
services_iops{instance="nas",job="truenas",op="write",service="nscd"} 0
services_iops{instance="nas",job="truenas",op="write",service="rpc_statd"} 0
services_iops{instance="nas",job="truenas",op="write",service="rpcbind"} 0
services_iops{instance="nas",job="truenas",op="write",service="scst"} 0
services_iops{instance="nas",job="truenas",op="write",service="smartmontools"} 0
services_iops{instance="nas",job="truenas",op="write",service="smbd"} 0
services_iops{instance="nas",job="truenas",op="write",service="syslog_ng"} 0
services_iops{instance="nas",job="truenas",op="write",service="systemd_journald"} 0
services_iops{instance="nas",job="truenas",op="write",service="systemd_logind"} 0
services_iops{instance="nas",job="truenas",op="write",service="systemd_udevd"} 0
services_iops{instance="nas",job="truenas",op="write",service="winbind"} 0
services_iops{instance="nas",job="truenas",op="write",service="wsdd"} 0
services_iops{instance="nas",job="truenas",op="write",service="zfs_zed"} 0
# HELP services_mem Graphite metric services_mem
# TYPE services_mem gauge
services_mem{instance="nas",job="truenas",service="avahi_daemon"} 0.8371094
services_mem{instance="nas",job="truenas",service="certmonger"} 3.535156
services_mem{instance="nas",job="truenas",service="chrony"} 1.671875
services_mem{instance="nas",job="truenas",service="containerd"} 51.27344
services_mem{instance="nas",job="truenas",service="cron"} 0.6875
services_mem{instance="nas",job="truenas",service="dbus"} 1.976562
services_mem{instance="nas",job="truenas",service="docker"} 77.17188
services_mem{instance="nas",job="truenas",service="gssproxy"} 1.2578125
services_mem{instance="nas",job="truenas",service="middlewared"} 1407.37615
services_mem{instance="nas",job="truenas",service="netdata"} 185.04333
services_mem{instance="nas",job="truenas",service="nfs_blkmap"} 0.3671875
services_mem{instance="nas",job="truenas",service="nfs_idmapd"} 0.6171875
services_mem{instance="nas",job="truenas",service="nfs_mountd"} 0.78125
services_mem{instance="nas",job="truenas",service="nfsdcld"} 0.6601562
services_mem{instance="nas",job="truenas",service="nginx"} 4.496094
services_mem{instance="nas",job="truenas",service="nmbd"} 2.886719
services_mem{instance="nas",job="truenas",service="nscd"} 1.19375
services_mem{instance="nas",job="truenas",service="rpc_statd"} 0.6210938
services_mem{instance="nas",job="truenas",service="rpcbind"} 0.7734375
services_mem{instance="nas",job="truenas",service="scst"} 1.1679688
services_mem{instance="nas",job="truenas",service="smartmontools"} 2.71875
services_mem{instance="nas",job="truenas",service="smbd"} 10.500781
services_mem{instance="nas",job="truenas",service="syslog_ng"} 6.878906
services_mem{instance="nas",job="truenas",service="systemd_journald"} 4.375
services_mem{instance="nas",job="truenas",service="systemd_logind"} 1.710938
services_mem{instance="nas",job="truenas",service="systemd_udevd"} 14.488281
services_mem{instance="nas",job="truenas",service="winbind"} 4.6875
services_mem{instance="nas",job="truenas",service="wsdd"} 15.46875
services_mem{instance="nas",job="truenas",service="zfs_zed"} 1.6328125
# HELP statsd_metric_mapper_cache_gets_total The count of total metric cache gets.
# TYPE statsd_metric_mapper_cache_gets_total counter
statsd_metric_mapper_cache_gets_total 319056
# HELP statsd_metric_mapper_cache_hits_total The count of total metric cache hits.
# TYPE statsd_metric_mapper_cache_hits_total counter
statsd_metric_mapper_cache_hits_total 318189
# HELP statsd_metric_mapper_cache_length The count of unique metrics currently cached.
# TYPE statsd_metric_mapper_cache_length gauge
statsd_metric_mapper_cache_length 867
# HELP system_io Graphite metric system_io
# TYPE system_io gauge
system_io{instance="nas",job="truenas",op="in"} 695064.68
system_io{instance="nas",job="truenas",op="out"} -286.5371
# HELP system_load Graphite metric system_load
# TYPE system_load gauge
system_load{instance="nas",job="truenas",kind="load1"} 3.615
system_load{instance="nas",job="truenas",kind="load15"} 3.885
system_load{instance="nas",job="truenas",kind="load5"} 3.78
# HELP system_net_io Graphite metric system_net_io
# TYPE system_net_io gauge
system_net_io{instance="nas",job="truenas",op="received"} 10.1979461
system_net_io{instance="nas",job="truenas",op="sent"} -47.8993905

# ##########################################
# Container - 1ba9d94d6c8f
# ##########################################

# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_10 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_10
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_10 gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_10 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_300 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_300
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_300 gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_300 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_60 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_60
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_60 gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_full_60 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_stall_time_time Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_stall_time_time
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_stall_time_time gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_full_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_limit_used Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_limit_used
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_limit_used gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_limit_used 0.0003625
# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_10 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_10
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_10 gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_10 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_300 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_300
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_300 gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_300 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_60 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_60
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_60 gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_some_60 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_stall_time_time Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_stall_time_time
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_stall_time_time gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_some_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_system Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_system
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_system gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_system 0.00098
# HELP truenas_nas_cgroup_1ba9d94d6c8f_cpu_user Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_cpu_user
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_cpu_user gauge
truenas_nas_cgroup_1ba9d94d6c8f_cpu_user 0.00047
# HELP truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_10 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_10
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_10 gauge
truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_10 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_300 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_300
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_300 gauge
truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_300 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_60 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_60
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_60 gauge
truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_full_60 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_stall_time_time Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_stall_time_time
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_stall_time_time gauge
truenas_nas_cgroup_1ba9d94d6c8f_io_full_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_io_read Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_io_read
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_io_read gauge
truenas_nas_cgroup_1ba9d94d6c8f_io_read 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_10 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_10
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_10 gauge
truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_10 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_300 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_300
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_300 gauge
truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_300 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_60 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_60
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_60 gauge
truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_some_60 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_stall_time_time Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_stall_time_time
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_stall_time_time gauge
truenas_nas_cgroup_1ba9d94d6c8f_io_some_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_io_write Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_io_write
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_io_write gauge
truenas_nas_cgroup_1ba9d94d6c8f_io_write 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_anon Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_anon
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_anon gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_anon 7.496094
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_anon_thp Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_anon_thp
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_anon_thp gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_anon_thp 2
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_file Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_file
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_file gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_file 4.546875
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_10 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_10
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_10 gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_10 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_300 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_300
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_300 gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_300 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_60 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_60
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_60 gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_full_pressure_full_60 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_kernel_stack Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_kernel_stack
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_kernel_stack gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_kernel_stack 0.15625
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_slab Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_slab
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_slab gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_slab 0.4021301
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_sock Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_sock
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_sock gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_sock 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_10 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_10
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_10 gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_10 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_300 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_300
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_300 gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_300 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_60 Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_60
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_60 gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_some_pressure_some_60 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_limit_available Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_limit_available
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_limit_available gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_limit_available 32071.38
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_limit_used Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_limit_used
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_limit_used gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_limit_used 8.484375
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_ram Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_ram
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_ram gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_ram 8.484375
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_swap Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_swap
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_swap gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_usage_swap 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_mem_utilization_utilization Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_mem_utilization_utilization
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_mem_utilization_utilization gauge
truenas_nas_cgroup_1ba9d94d6c8f_mem_utilization_utilization 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_memory_full_pressure_stall_time_time Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_memory_full_pressure_stall_time_time
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_memory_full_pressure_stall_time_time gauge
truenas_nas_cgroup_1ba9d94d6c8f_memory_full_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_memory_some_pressure_stall_time_time Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_memory_some_pressure_stall_time_time
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_memory_some_pressure_stall_time_time gauge
truenas_nas_cgroup_1ba9d94d6c8f_memory_some_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_pgfaults_pgfault Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_pgfaults_pgfault
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_pgfaults_pgfault gauge
truenas_nas_cgroup_1ba9d94d6c8f_pgfaults_pgfault 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_pgfaults_swap Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_pgfaults_swap
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_pgfaults_swap gauge
truenas_nas_cgroup_1ba9d94d6c8f_pgfaults_swap 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_serviced_ops_read Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_serviced_ops_read
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_serviced_ops_read gauge
truenas_nas_cgroup_1ba9d94d6c8f_serviced_ops_read 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_serviced_ops_write Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_serviced_ops_write
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_serviced_ops_write gauge
truenas_nas_cgroup_1ba9d94d6c8f_serviced_ops_write 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_throttled_duration_duration Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_throttled_duration_duration
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_throttled_duration_duration gauge
truenas_nas_cgroup_1ba9d94d6c8f_throttled_duration_duration 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_throttled_throttled Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_throttled_throttled
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_throttled_throttled gauge
truenas_nas_cgroup_1ba9d94d6c8f_throttled_throttled 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_writeback_dirty Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_writeback_dirty
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_writeback_dirty gauge
truenas_nas_cgroup_1ba9d94d6c8f_writeback_dirty 0
# HELP truenas_nas_cgroup_1ba9d94d6c8f_writeback_writeback Graphite metric truenas_nas_cgroup_1ba9d94d6c8f_writeback_writeback
# TYPE truenas_nas_cgroup_1ba9d94d6c8f_writeback_writeback gauge
truenas_nas_cgroup_1ba9d94d6c8f_writeback_writeback 0


# HELP truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_10 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_10
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_10 gauge
truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_10 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_300 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_300
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_300 gauge
truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_300 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_60 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_60
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_60 gauge
truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_full_60 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_stall_time_time Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_stall_time_time
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_stall_time_time gauge
truenas_nas_cgroup_system_slice_docker_service__control_cpu_full_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_10 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_10
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_10 gauge
truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_10 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_300 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_300
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_300 gauge
truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_300 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_60 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_60
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_60 gauge
truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_some_60 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_stall_time_time Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_stall_time_time
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_stall_time_time gauge
truenas_nas_cgroup_system_slice_docker_service__control_cpu_some_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_cpu_system Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_cpu_system
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_cpu_system gauge
truenas_nas_cgroup_system_slice_docker_service__control_cpu_system 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_cpu_user Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_cpu_user
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_cpu_user gauge
truenas_nas_cgroup_system_slice_docker_service__control_cpu_user 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_10 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_10
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_10 gauge
truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_10 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_300 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_300
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_300 gauge
truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_300 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_60 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_60
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_60 gauge
truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_full_60 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_stall_time_time Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_stall_time_time
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_stall_time_time gauge
truenas_nas_cgroup_system_slice_docker_service__control_io_full_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_10 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_10
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_10 gauge
truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_10 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_300 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_300
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_300 gauge
truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_300 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_60 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_60
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_60 gauge
truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_some_60 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_stall_time_time Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_stall_time_time
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_stall_time_time gauge
truenas_nas_cgroup_system_slice_docker_service__control_io_some_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_10 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_10
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_10 gauge
truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_10 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_300 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_300
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_300 gauge
truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_300 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_60 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_60
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_60 gauge
truenas_nas_cgroup_system_slice_docker_service__control_mem_full_pressure_full_60 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_10 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_10
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_10 gauge
truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_10 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_300 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_300
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_300 gauge
truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_300 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_60 Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_60
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_60 gauge
truenas_nas_cgroup_system_slice_docker_service__control_mem_some_pressure_some_60 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_memory_full_pressure_stall_time_time Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_memory_full_pressure_stall_time_time
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_memory_full_pressure_stall_time_time gauge
truenas_nas_cgroup_system_slice_docker_service__control_memory_full_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_memory_some_pressure_stall_time_time Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_memory_some_pressure_stall_time_time
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_memory_some_pressure_stall_time_time gauge
truenas_nas_cgroup_system_slice_docker_service__control_memory_some_pressure_stall_time_time 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_throttled_duration_duration Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_throttled_duration_duration
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_throttled_duration_duration gauge
truenas_nas_cgroup_system_slice_docker_service__control_throttled_duration_duration 0
# HELP truenas_nas_cgroup_system_slice_docker_service__control_throttled_throttled Graphite metric truenas_nas_cgroup_system_slice_docker_service__control_throttled_throttled
# TYPE truenas_nas_cgroup_system_slice_docker_service__control_throttled_throttled gauge
truenas_nas_cgroup_system_slice_docker_service__control_throttled_throttled 0
# HELP truenas_nas_netdata_plugin_chartsd_nut_ups_run_time Graphite metric truenas_nas_netdata_plugin_chartsd_nut_ups_run_time
# TYPE truenas_nas_netdata_plugin_chartsd_nut_ups_run_time gauge
truenas_nas_netdata_plugin_chartsd_nut_ups_run_time 0
# HELP uptime Graphite metric uptime
# TYPE uptime gauge
uptime{instance="nas",job="truenas"} 6637.578
# HELP zfs_actual_hits Graphite metric zfs_actual_hits
# TYPE zfs_actual_hits gauge
zfs_actual_hits{instance="nas",job="truenas",op="hits"} 100
zfs_actual_hits{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_actual_hits_rate Graphite metric zfs_actual_hits_rate
# TYPE zfs_actual_hits_rate gauge
zfs_actual_hits_rate{instance="nas",job="truenas",op="hits"} 531.0421281
zfs_actual_hits_rate{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_arc_size Graphite metric zfs_arc_size
# TYPE zfs_arc_size gauge
zfs_arc_size{instance="nas",job="truenas",op="arcsz"} 4129.2787
zfs_arc_size{instance="nas",job="truenas",op="max__high_water_"} 31055.87
zfs_arc_size{instance="nas",job="truenas",op="min__hard_limit_"} 1002.4958
zfs_arc_size{instance="nas",job="truenas",op="target"} 4169.621
# HELP zfs_arc_size_breakdown Graphite metric zfs_arc_size_breakdown
# TYPE zfs_arc_size_breakdown gauge
zfs_arc_size_breakdown{instance="nas",job="truenas",op="frequent"} 100
zfs_arc_size_breakdown{instance="nas",job="truenas",op="recent"} 0
# HELP zfs_demand_data_hits Graphite metric zfs_demand_data_hits
# TYPE zfs_demand_data_hits gauge
zfs_demand_data_hits{instance="nas",job="truenas",op="hits"} 100
zfs_demand_data_hits{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_demand_data_hits_rate Graphite metric zfs_demand_data_hits_rate
# TYPE zfs_demand_data_hits_rate gauge
zfs_demand_data_hits_rate{instance="nas",job="truenas",op="hits"} 1.2097011
zfs_demand_data_hits_rate{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_dhits Graphite metric zfs_dhits
# TYPE zfs_dhits gauge
zfs_dhits{instance="nas",job="truenas",op="hits"} 100
zfs_dhits{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_dhits_rate Graphite metric zfs_dhits_rate
# TYPE zfs_dhits_rate gauge
zfs_dhits_rate{instance="nas",job="truenas",op="hits"} 531.0788272
zfs_dhits_rate{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_hash_chains Graphite metric zfs_hash_chains
# TYPE zfs_hash_chains gauge
zfs_hash_chains{instance="nas",job="truenas",op="current"} 30581.8
zfs_hash_chains{instance="nas",job="truenas",op="max"} 3
# HELP zfs_hash_elements Graphite metric zfs_hash_elements
# TYPE zfs_hash_elements gauge
zfs_hash_elements{instance="nas",job="truenas",op="current"} 527393.7
zfs_hash_elements{instance="nas",job="truenas",op="max"} 527399
# HELP zfs_hits Graphite metric zfs_hits
# TYPE zfs_hits gauge
zfs_hits{instance="nas",job="truenas",op="hits"} 100
zfs_hits{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_hits_rate Graphite metric zfs_hits_rate
# TYPE zfs_hits_rate gauge
zfs_hits_rate{instance="nas",job="truenas",op="hits"} 531.0858307
zfs_hits_rate{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_important_ops Graphite metric zfs_important_ops
# TYPE zfs_important_ops gauge
zfs_important_ops{instance="nas",job="truenas",op="deleted"} 0
zfs_important_ops{instance="nas",job="truenas",op="evict_skip"} 0
zfs_important_ops{instance="nas",job="truenas",op="hash_collisions"} 0.3669513
zfs_important_ops{instance="nas",job="truenas",op="mutex_miss"} 0
# HELP zfs_list_hits Graphite metric zfs_list_hits
# TYPE zfs_list_hits gauge
zfs_list_hits{instance="nas",job="truenas",op="mfu"} 525.216018
zfs_list_hits{instance="nas",job="truenas",op="mfu_ghost"} 0
zfs_list_hits{instance="nas",job="truenas",op="mru"} 5.844492
zfs_list_hits{instance="nas",job="truenas",op="mru_ghost"} 0
# HELP zfs_mhits Graphite metric zfs_mhits
# TYPE zfs_mhits gauge
zfs_mhits{instance="nas",job="truenas",op="hits"} 60
zfs_mhits{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_mhits_rate Graphite metric zfs_mhits_rate
# TYPE zfs_mhits_rate gauge
zfs_mhits_rate{instance="nas",job="truenas",op="hits"} 529.8551012
zfs_mhits_rate{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_phits Graphite metric zfs_phits
# TYPE zfs_phits gauge
zfs_phits{instance="nas",job="truenas",op="hits"} 0
zfs_phits{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_phits_rate Graphite metric zfs_phits_rate
# TYPE zfs_phits_rate gauge
zfs_phits_rate{instance="nas",job="truenas",op="hits"} 0
zfs_phits_rate{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_pool Graphite metric zfs_pool
# TYPE zfs_pool gauge
zfs_pool{instance="nas",job="truenas",pool="boot_pool",state="degraded"} 0
zfs_pool{instance="nas",job="truenas",pool="boot_pool",state="faulted"} 0
zfs_pool{instance="nas",job="truenas",pool="boot_pool",state="offline"} 0
zfs_pool{instance="nas",job="truenas",pool="boot_pool",state="online"} 1
zfs_pool{instance="nas",job="truenas",pool="boot_pool",state="removed"} 0
zfs_pool{instance="nas",job="truenas",pool="boot_pool",state="unavail"} 0
zfs_pool{instance="nas",job="truenas",pool="pool_ssd",state="degraded"} 0
zfs_pool{instance="nas",job="truenas",pool="pool_ssd",state="faulted"} 0
zfs_pool{instance="nas",job="truenas",pool="pool_ssd",state="offline"} 0
zfs_pool{instance="nas",job="truenas",pool="pool_ssd",state="online"} 1
zfs_pool{instance="nas",job="truenas",pool="pool_ssd",state="removed"} 0
zfs_pool{instance="nas",job="truenas",pool="pool_ssd",state="unavail"} 0
zfs_pool{instance="nas",job="truenas",pool="storage",state="degraded"} 0
zfs_pool{instance="nas",job="truenas",pool="storage",state="faulted"} 0
zfs_pool{instance="nas",job="truenas",pool="storage",state="offline"} 0
zfs_pool{instance="nas",job="truenas",pool="storage",state="online"} 1
zfs_pool{instance="nas",job="truenas",pool="storage",state="removed"} 0
zfs_pool{instance="nas",job="truenas",pool="storage",state="unavail"} 0
# HELP zfs_prefetch_data_hits Graphite metric zfs_prefetch_data_hits
# TYPE zfs_prefetch_data_hits gauge
zfs_prefetch_data_hits{instance="nas",job="truenas",op="hits"} 0
zfs_prefetch_data_hits{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_prefetch_data_hits_rate Graphite metric zfs_prefetch_data_hits_rate
# TYPE zfs_prefetch_data_hits_rate gauge
zfs_prefetch_data_hits_rate{instance="nas",job="truenas",op="hits"} 0
zfs_prefetch_data_hits_rate{instance="nas",job="truenas",op="misses"} 0
# HELP zfs_reads Graphite metric zfs_reads
# TYPE zfs_reads gauge
zfs_reads{instance="nas",job="truenas",op="arc"} 531.0968265
zfs_reads{instance="nas",job="truenas",op="demand"} 531.0968265
zfs_reads{instance="nas",job="truenas",op="l2"} 0
zfs_reads{instance="nas",job="truenas",op="metadata"} 529.8870978
zfs_reads{instance="nas",job="truenas",op="prefetch"} 0