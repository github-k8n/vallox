# Vallox ESPHome component
Vallox SE ventilation control software for ESPHome (and thus Home Assistant)


# **IMPORTANT: Development was migrated to codeberg.**

https://codeberg.org/k8n/vallox

Fixes for recent changes in esphome are available there.

Just use the following in your yaml

    external_components:
      - source:
          type: git
          url: https://codeberg.org/k8n/vallox
        components: [ vallox ]
        refresh: 0s
