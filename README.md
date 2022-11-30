ESM_CONTEXT_UPDATE
=========

Ansible role to upload and apply ArcSight ESM Context updates.

Requirements
------------

None

Role Variables
--------------

| Name         | Descripton                                       |  Default Vaules                                        |
| -------------| -------------------------------------------------| -------------------------------------------------------|
| zip_file     | Zip file name                                    | "ArcSight_Context_Update_November_2022.1109_033024.zip"|
| user         | The user the ESM is running under                | "arcsight"                                             |
| context_path | Default path where context updates are installed | "/opt/arcsight/manager/config/server"                  |

Dependencies
------------

None

Example Playbook
----------------

See example playbook within repo. 

License
-------

MIT
