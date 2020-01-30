1) add wjh: true to /etc/netq/netq.yml (see example file)
2) Add the fake data file: .wjh.data to /etc/netq/ folder
3) Modify the netq-agent start_wjh method to not check for cl4
4) netq config restart agent
