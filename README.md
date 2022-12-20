# ansible-role-win-localusers

Role to manage local windows users and groups

## Table of content

- [Default Variables](#default-variables)
  - [win_local_admin_group_add_to_list](#win_local_admin_group_add_to_list)
  - [win_local_admin_group_remove_from_list](#win_local_admin_group_remove_from_list)
  - [win_local_backup_group_add_to_list](#win_local_backup_group_add_to_list)
  - [win_local_backup_group_remove_from_list](#win_local_backup_group_remove_from_list)
  - [win_local_groups_add_list](#win_local_groups_add_list)
  - [win_local_groups_remove_list](#win_local_groups_remove_list)
  - [win_local_rdp_group_add_to_list](#win_local_rdp_group_add_to_list)
  - [win_local_rdp_group_remove_from_list](#win_local_rdp_group_remove_from_list)
  - [win_local_user_group_add_to_list](#win_local_user_group_add_to_list)
  - [win_local_user_group_remove_from_list](#win_local_user_group_remove_from_list)
  - [win_local_users_add_list](#win_local_users_add_list)
  - [win_local_users_remove_list](#win_local_users_remove_list)
  - [win_path_seperator](#win_path_seperator)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### win_local_admin_group_add_to_list

Specifies a list of accounts to be added to local admin group

#### Default value

```YAML
win_local_admin_group_add_to_list: []
```

### win_local_admin_group_remove_from_list

Specifies a list of accounts to be removed from local admin group

#### Default value

```YAML
win_local_admin_group_remove_from_list: []
```

### win_local_backup_group_add_to_list

Specifies a list of accounts to be added to local backup operator group

#### Default value

```YAML
win_local_backup_group_add_to_list: []
```

### win_local_backup_group_remove_from_list

Specifies a list of accounts to be removed from local backup operator group

#### Default value

```YAML
win_local_backup_group_remove_from_list: []
```

### win_local_groups_add_list

Specify a list of local groups to be added

win_local_groups_add_list:

- { name: "group1", description: "desc1" }

- { name: "group2", description: "desc2" }

- { name: "group3", description: "desc3" }

#### Default value

```YAML
win_local_groups_add_list: []
```

### win_local_groups_remove_list

Specify a list of local groups to be removed

win_local_groups_remove_list:

- "group1"

- "group2"

- "group3"

#### Default value

```YAML
win_local_groups_remove_list: []
```

### win_local_rdp_group_add_to_list

Specifies a list of accounts to be added to local remote desktop group

#### Default value

```YAML
win_local_rdp_group_add_to_list: []
```

### win_local_rdp_group_remove_from_list

Specifies a list of accounts to be removed from local remote desktop group

#### Default value

```YAML
win_local_rdp_group_remove_from_list: []
```

### win_local_user_group_add_to_list

Specifies a list of accounts to be added to local user group

#### Default value

```YAML
win_local_user_group_add_to_list: []
```

### win_local_user_group_remove_from_list

Specifies a list of accounts to be removed from local user group

#### Default value

```YAML
win_local_user_group_remove_from_list: []
```

### win_local_users_add_list

Specify a list of local users to be added

win_local_users_add_list:

- { name: "user1", description: "desc1", fullname: "", password: "", password_expired: false, password_never_expires: false }

- { name: "user2", description: "desc2" }

- { name: "user3", description: "desc3" }

#### Default value

```YAML
win_local_users_add_list: []
```

### win_local_users_remove_list

Specify a list of local users to be removed

win_local_users_remove_list:

- "user1"

- "user2"

- "user3"

#### Default value

```YAML
win_local_users_remove_list: []
```

### win_path_seperator

backslash in variable for easy handling

#### Default value

```YAML
win_path_seperator: \
```



## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888
