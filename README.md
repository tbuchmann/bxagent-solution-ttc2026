# bxagent-solution-ttc2026
The BXAgent solution for the TTC 2026 Families-to-Persons Case

## Settings

- used Ollama on local hardware
- NVIDIA RTX 4090 GPU with 24GB VRAM
- Ubuntu Linux 24.04 LTS
- OpenJDK 21
- LLM used: devstral-small-2

## Used natural language description

```
"Transform FamilyMember: combine member.eContainer.name + \", \" + member.name into single name field of Person, in backward transformation split name at the comma. Retrieve the matching family. two configuration parameters: prefer existing family and prefer parent over child role. Depending on the role in the family: father + sons a Male object from the persons model is created, for mother + daughters a Female object is created."
```
