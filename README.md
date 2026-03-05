# Static Routing Lab (PNETLab / VyOS)

## Topology

PC1 ---- R1 ---- R2 ---- PC2

Networks:
192.168.10.0/24
10.0.0.0/30
192.168.20.0/24

## Objective

Allow communication between two LANs using static routing.

## Addressing

PC1: 192.168.10.10
R1: 192.168.10.1 / 10.0.0.1
R2: 10.0.0.2 / 192.168.20.1
PC2: 192.168.20.10

## Static routes

R1 → 192.168.20.0 via 10.0.0.2  
R2 → 192.168.10.0 via 10.0.0.1

## Test

ping 192.168.20.10
ping 192.168.10.10
