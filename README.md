# screensaver

[![Build Status](https://cloud.drone.io/api/badges/machippie/screensaver/status.svg)](https://cloud.drone.io/machippie/screensaver)

Ansible role to configure screensaver

## Table of content

* [Default Variables](#default-variables)
  * [screensaver_ask_for_password](#screensaver_ask_for_password)
  * [screensaver_idle_time](#screensaver_idle_time)
  * [screensaver_password_delay](#screensaver_password_delay)
  * [screensaver_show_clock](#screensaver_show_clock)
  * [screensaver_user](#screensaver_user)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### screensaver_ask_for_password

Ask for a password to leave screensaver

#### Default value

```YAML
screensaver_ask_for_password: true
```

### screensaver_idle_time

Define idle timeout duration

#### Default value

```YAML
screensaver_idle_time: 300
```

### screensaver_password_delay

Password promt delay

#### Default value

```YAML
screensaver_password_delay: 0
```

### screensaver_show_clock

Show a clock on screensaver

#### Default value

```YAML
screensaver_show_clock: true
```

### screensaver_user

User to run user-specific commands, defaults to homebrew_user

## Dependencies

None.

## License

Apache-2.0

## Author

Thomas Boerger
