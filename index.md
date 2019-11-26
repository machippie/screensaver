
## Default Variables

### screensaver_ask_for_password

Ask for a password to leave screensaver

#### Default value

```yaml
screensaver_ask_for_password: true
```

### screensaver_idle_time

Define idle timeout duration

#### Default value

```yaml
screensaver_idle_time: 300
```

### screensaver_password_delay

Password promt delay

#### Default value

```yaml
screensaver_password_delay: 0
```

### screensaver_show_clock

Show a clock on screensaver

#### Default value

```yaml
screensaver_show_clock: true
```

### screensaver_user

User to run user-specific commands

#### Default value

```yaml
screensaver_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
