## Some Playbooks written for usecases

### install_msi_packages_on_windows.yml

Installs or uninstall packages as playbook for a awx template.
For easy use, ask all variables via survey. [Documentation](http://docs.ansible.com/ansible-tower/latest/html/userguide/job_templates.html#surveys)

#### Variables

| variable             | default | required | values                                           |
|----------------------|---------|----------|--------------------------------------------------|
| action_triggered     | null    | yes      | install uninstall reinstall                      |
| msi_arguments        | /quiet  | no       | see module win_package                           |
| windows_package_path | null    | yes      |  Ex.: \\domain\programs\7z.msi or C:\temp\7z.msi |
