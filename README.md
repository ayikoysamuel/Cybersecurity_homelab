# Cybersecurity_homelab
This is for cybersecurity projects, both for the Blue team and Red team.


Blue team is for SOC Analysis, which shall handle defensive security 
Red team or white team will handle the basics and real-world hacking like the bad guys, all in a safe environment.

### HomeLab Machines:
- Kali Linux --- attacker,
- Metaspoiltable2 ---- victim
- Windows VM --- victim
- Ubuntu server --- Holds wazuh SEIM tool for capturing telemetry/
- Wazuh agents --- Connected to all the victims.

- Attacks that are simulated on the victims, the telemetry will be captured by the Wazuh SEIM/
  * Captures logs, 

### Flow of the projects 
- Attacks will be launched from Kali Linux on a Victim.
- The footprints of the attacks and telemetry will be captured by the Wazuh SEIM tool
- The Telemetry will be read from the Wazuh Dashboard generated from the captures.
- Critical alerts are then investigated, and all the measures are going to be taken.

## Blue Team projects:



