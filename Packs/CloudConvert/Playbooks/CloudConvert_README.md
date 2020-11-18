Use this playbook to convert a file to the required format using CloudConvert.

## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

### Sub-playbooks
* GenericPolling

### Integrations
* CloudConvert


### Commands
* cloudconvert-export
* cloudconvert-import
* cloudconvert-convert
* cloudconvert-check-status

## Playbook Inputs
---

| **Name** | **Description** | **Default Value** | **Required** |
| --- | --- | --- | --- |
| url | The URL of the imported file. |  | Optional |
| entry_id | The entry ID of the imported file. |  | Optional |
| output_format | The required output format.|  | Required |
| export_via | The method for exporting the converted file - URL or war_room_entry. |  | Required |

## Playbook Outputs
---
There are no outputs for this playbook.

## Playbook Image
---
![CloudConvert](https://user-images.githubusercontent.com/72340690/99377797-54253d00-28cf-11eb-874b-e09a9b128e6d.png)