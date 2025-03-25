# CSRF Demo

This is a demo about Cross-Site Request Forgery (CSRF) attacks.

## Requirements

- Install XAMPP
- Run Apache and MySQL
- Use port 8080 to run the application

## Installation and Running

1. **Install XAMPP**: Download and install [XAMPP](https://www.apachefriends.org/index.html).
2. **Start Apache and MySQL** from the XAMPP Control Panel.
3. **Place the project in the htdocs folder**:
   ```sh
   cd C:\xampp\htdocs
   git clone https://github.com/datletechxd/csrf-demo.git
   ```
4. **Access the web application**: Open a browser and visit:
   ```
   http://localhost:8080/csrf-demo/
   ```

## Security Mechanism

This project contains two versions of a vulnerable website:

- **victim_site/** (Vulnerable): This version does not have CSRF protection, making it possible to execute unauthorized requests using a crafted attack page.
- **victim_site_secure/** (Secured): This version includes CSRF protection by implementing CSRF tokens.

## Contact

If you have any questions, please reach out via [GitHub Issues](https://github.com/datletechxd/csrf-demo/issues).
