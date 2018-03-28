## Some Playbooks written for usecases

### install packages

#### Variables

| variable             | default | required | values                                           |
|----------------------|---------|----------|--------------------------------------------------|
| action_triggered     | null    | yes      | install uninstall reinstall                      |
| msi_arguments        | /quiet  | no       | see module win_package                           |
| windows_package_path | null    | yes      |  Ex.: \\domain\programs\7z.msi or C:\temp\7z.msi |
