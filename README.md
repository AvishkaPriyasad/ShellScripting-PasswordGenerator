

```markdown
# Simple Password Generator

A Bash-based script to generate secure, random passwords with user-defined lengths. This tool leverages `openssl` for cryptographic randomness and provides an interactive interface to generate multiple passwords efficiently.

## Features
- Generate secure passwords of custom lengths.
- Generate multiple passwords in a single execution.
- Lightweight and easy to use.

## Technologies Used
- **Bash**: For scripting and automation.
- **OpenSSL**: For cryptographically secure random strings.
- **Linux/Unix Shell**: Runtime environment for the script.

## How to Use
1. Clone this repository or copy the script.
   ```bash
   git clone https://github.com/AvishkaPriyasad/ShellScripting-PasswordGenerator.git
   cd ShellScripting-PasswordGenerator
   ```

2. Make the script executable.
   ```bash
   chmod +x password_generator.sh
   ```

3. Run the script.
   ```bash
   ./password_generator.sh
   ```

4. Enter the desired password length when prompted, and the script will generate 5 secure passwords of that length.

## Example Output
```plaintext
This is a simple password generator
Please enter the length of the password: 
12
qJz1xP6DkL9T
a8FsTp3Wv2nX
Lk4Fg9TxWp8Y
Nm2Dz6XpL3Fy
Tq8Wk4L9Pz3X
```

## Prerequisites
- Linux/Unix environment
- OpenSSL installed (usually pre-installed on most systems)

## License
This project is open-source and available under the [MIT License](LICENSE).

