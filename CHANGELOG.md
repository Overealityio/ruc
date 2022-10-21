# Change log

#### v3.0.0

- Add support for remote command execution based on the SSH protocol
- Remove syntactic sugar for printing information in the 'Debug' format
    - eg, `d!(@a_struct)` should be replaced with `d!("{:?}", a_struct)` in v3.0.x
- Optimize documentations