### Config DNA

* user-centric - users grow and develop their own preferences
* system-independent - users don't care where settings are
* software tuning - you can not satisfy everybody with defaults

### Format

    software { key: value } software2 { key: value}
    software { key: value, key: value }
    
Spaces are not important, linefeeds are not important,
interpretation of values and keys is left to the command that
processes the code.

    gnome-terminal { f1: off }

For file names it is recommended to keep it in `config.dna` to
easily gather all settings from repositories and build stats.

### Applications

Share user preferences, building stats, visualizing, detecting
most popular options, detect weird defaults, storing software
configs in blockchain.

### Processors

* gnome-terminal
  * f1: off  - release F1 shortcut for other programs
