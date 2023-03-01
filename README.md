```xml
                  █████   ████  ████████  ███████████   █████ ██████████ █████       █████ ███████████
                  ░░███   ███░  ███░░░░███░░███░░░░░███ ░░███ ░░███░░░░░█░░███       ░░███ ░█░░░███░░░█
                   ░███  ███   ░░░    ░███ ░███    ░███  ░███  ░███  █ ░  ░███        ░███ ░   ░███  ░ 
                   ░███████       ██████░  ░██████████   ░███  ░██████    ░███        ░███     ░███    
                   ░███░░███     ░░░░░░███ ░███░░░░░███  ░███  ░███░░█    ░███        ░███     ░███    
                   ░███ ░░███   ███   ░███ ░███    ░███  ░███  ░███ ░   █ ░███      █ ░███     ░███    
                   █████ ░░████░░████████  █████   █████ █████ ██████████ ███████████ █████    █████   
                  ░░░░░   ░░░░  ░░░░░░░░  ░░░░░   ░░░░░ ░░░░░ ░░░░░░░░░░ ░░░░░░░░░░░ ░░░░░    ░░░░░    

<appconfig>
  <diplomaList type="List<Diploma>" count="0"></diplomaList>
  <jobList type="List<Job>" count="0"></jobList>
  <noteList type="List<Note>" count="1">
    <note type="string" id="unemploymentReason">Not enough diplomas</note>
  </noteList>
  <income type="long" value="0" minvalue="0" maxvalue="{Hungary.MinimalberProvider.GetMinimalber();}"/>
</appconfig>
```
