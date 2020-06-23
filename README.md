### wjh-netq-wjh_data

### Description:

This will simulate Mellanox's "What Just Happened" data from leaf02 in a Production Ready Automation / Golden Turtle PoC

You will be able to perform the following:

1. Setup a "Cumulus in the Cloud" topology in Cumulus AIR

2. Optional: Apply the EVPN configuration that you are looking to showcase as part of the PoC

3. Run the following on the OOB Management server:

```
git clone
```

4. Run this playbook with the following command:

```
ansible-plabook whj.yml
```

5. Next, in the NetQ GUI, click the three line menu icon in the top left > Network > What Just Happened

Here you will be able to show a customer the simulated What Just Happened data that came from leaf02.
