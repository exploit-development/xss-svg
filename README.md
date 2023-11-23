# XSS SVG

This repository contains a Proof of Concept (PoC) for Cross-Site Scripting (XSS) using an SVG image. The SVG file demonstrates a simple alert triggered by loading the image.

## Overview

The PoC illustrates how an attacker introduce XSS to a web application. The included SVG file (`1.svg`) is designed to be a minimal example for educational purposes and awareness about XSS risks.

## Features

- **SVG Image:** A blue square SVG image that serves as the carrier for the XSS payload.
  
- **XSS Payload:** The SVG file contains an embedded script that triggers an alert on load.

## Usage

1. **Clone this repository:**

    ```bash
    git clone https://github.com/codesecure-org/xss-svg.git
    ```

2. **Upload the SVG file (`1.svg`) to your web server:**
   
After cloning the repository, upload the 1.svg file. This typically works well for profile pictures.

## Note

This PoC is created for educational purposes to demonstrate the potential risks associated with XSS vulnerabilities. Always practice responsible disclosure and obtain proper authorization before conducting security research.

## Disclaimer

This PoC is provided "as is" without warranty of any kind. Use it responsibly and only in environments where you have explicit permission to test for vulnerabilities.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This PoC is released under the [MIT License](LICENSE).
