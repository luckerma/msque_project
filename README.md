# msque_project

Wireless Network Modeling and Simulation

Report available at:\
https://luckerma.github.io/msque_project/

## Install OMNeT++ and INET locally

```bash
pip install opp_env
opp_env install --init -w inet-workspace inet-4.5.4 omnetpp-6.1.0
```

## Start OMNeT++

```bash
cd inet-workspace
opp_env shell
omnetpp
```

## Run Simulation

```bash
/inet-workspace/inet-4.5.4/tutorials/wireless/omnetpp.ini
```

## Report (Quarto)

### Preview Report (HTML)

```bash
quarto preview ./report/
```

### Render Report (PDF)

```bash
quarto render ./report/ --to pdf
```

### Render Report (IEEE PDF)

```bash
cd report/
quarto add dfolio/quarto-ieee
quarto render . --to ieee-pdf
```
