./BHHS
    │   .gitignore
    │   README.md
    │
    ├───app
    │   │   .gitignore
    │   │   README.md
    │   │
    │   ├───modules
    │   └───roots
    │       │   locals.tf
    │       │   main.tf
    │       │   outputs.tf
    │       │   server-compss.tf
    │       │   server-health-store-regional.tf
    │       │   server-health-store.tf
    │       │   server-resmd.tf
    │       │   storage-health-store-data.tf
    │       │   variables.tf
    │       │   versions.tf
    │       │
    │       └───env
    │               dev.tfvars
    │               pre-prod.tfvars
    │               productions.tfvars
    │
    ├───network
    │   │   .gitignore
    │   │   README.md
    │   │
    │   ├───modules
    │   └───roots
    │       │   main.tf
    │       │   networking-loadbalancer-compass.tf
    │       │   networking-loadbalancer-internal.tf
    │       │   networking-loadbalancer-regional.tf
    │       │   networking-loadbalancer-resmd.tf
    │       │   networking-site-recovery.tf
    │       │   networking-subnets.tf
    │       │   networking-vnet-peering.tf
    │       │   networking-vnet.tf
    │       │   networking-waf.tf
    │       │   outputs.tf
    │       │   variables.tf
    │       │
    │       └───env
    │               dev.tfvars
    │               pre-prod.tfvars
    │               productions.tfvars
    │
    ├───operations
    │   │   .gitignore
    │   │   README.md
    │   │
    │   ├───modules
    │   └───roots
    │       │   main.tf
    │       │   operations-bastion.tf
    │       │   operations-log-analytics.tf
    │       │   operations-logs-storage.tf
    │       │   operations-monitor.tf
    │       │   operations-service-health.tf
    │       │   outputs.tf
    │       │   variables.tf
    │       │
    │       └───env
    │               dev.tfvars
    │               pre-prod.tfvars
    │               productions.tfvars
    │
    └───security
        │   .gitignore
        │   README.md
        │
        ├───modules
        └───roots
            │   locals.tf
            │   main.tf
            │   outputs.tf
            │   security-ddos.tf
            │   security-key-vault.tf
            │   security-network-watcher.tf
            │   security-nsg.tf
            │   security-security-center.tf
            │   security-sentinel.tf
            │   variables.tf
            │
            └───env
                    dev.tfvars
                    pre-prod.tfvars
                    productions.tfvars
