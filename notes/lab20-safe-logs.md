# Lab 20 — Rewrite Unsafe Logs

## Unsafe example
"Activating customer CUS-1001 Amina Khan with payload {...}"  // leaks identifiers and internals

## Safe rewrite (Amina/CUS-1001)
"Activate request received for customer"  // no IDs, no names, no payload

## Safe Ravi activate start
"Starting activate workflow"  // generic, no Ravi/CUS-1002, no sensitive fields

## Scope
Pre-lab only.
