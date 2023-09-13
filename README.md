# Linode-Cli
To manage Linode Using Termux app.


To install Linode CLI in Termux, you can follow these steps:

1. Install Termux:
   - Download and install the Termux app from the Google Play Store or F-Droid.
   - Open the app and wait for it to initialize.

2. Update packages:
   - Run the following command in Termux to update the package repositories:
     ```
     apt update
     ```

3. Install Python:
   - Run the following command to install Python in Termux:
     ```
     pkg install python -y
     ```

4. Install Pip:
   - Run the following command to install Pip in Termux:
     ```
     pkg install python-dev -y
     ```

5. Install Git:
   - Run the following command to install Git in Termux:
     ```
     pkg install git -y
     ```

6. Clone the Linode CLI repository:
   - Run the following command to clone the Linode CLI repository from GitHub:
     ```
     git clone https://github.com/linode/cli.git
     ```

7. Change directory:
   - Run the following command to navigate into the "cli" directory:
     ```
     cd cli
     ```

8. Install Linode CLI:
   - Run the following command to install Linode CLI using Pip:
     ```
     pip install --editable .
     ```

9. Authenticate with Linode API:
   - Visit the Linode Manager and generate an API key under your profile settings.
   - In Termux, run the following command to configure Linode CLI with your API key:
     ```
     linode-cli configure
     ```
   - Enter your Linode API key when prompted.

10. Verify installation:
    - Run the following command to verify if Linode CLI is installed properly:
      ```
      linode-cli-cli
      ```

You have now successfully installed Linode CLI in Termux. You can use the `linode-cli` command to interact with the Linode API and manage your Linode services from Termux.
