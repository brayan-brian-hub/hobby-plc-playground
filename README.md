# hobby-plc-playground

> A simple soft-PLC setup using OpenPLC + Factory IO conveyor sim.
I wrote some ladder logic to sort boxes by size.

## HMI Demo

![HMI Demo](docs/images/hobby-hmi.gif)

_A quick loop of the conveyor HMI in action, March 2024._

## Container Lab

A quick Docker Compose setup to spin up a soft-PLC (OpenPLC), an MQTT broker, and Grafana for easy IIoT 
testing. Perfect for tinkering with PLC-to-dashboard data flows.

## Project Planner

```mermaid
gantt
  dateFormat  YYYY-MM-DD
  title       PLC Playground Roadmap
  excludes    weekends
  section Setup
    Scaffold Repo        :done,    des1, 2024-01-15, 1d
    Heartbeat Commits     :done,    des2, 2024-01-16, 11m
    Initial ST Logic      :done,    des3, 2024-02-01, 1d
  section Demos
    HMI Demo Placeholder  :done,    des4, 2024-03-01, 1d
    Container Lab Blurb   :done,    des5, 2024-04-01, 1d
    Docker Stub           :done,    des6, 2024-04-01, 1d
  section Next Steps
    Add Zeek/Snort Snippet:active,  des7, 2024-05-01, 2d
    Polish GIF & Dashboards:         des8, after des7, 1d
```


