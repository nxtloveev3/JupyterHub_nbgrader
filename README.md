# JupyterHub_nbgrader_Jetstream2_Set_Up_Scripts
This repository contains the latest versioned scripts for deploying a JupyterHub instance with nbgrader on the Jetstream2 cloud platform. These scripts are designed to streamline setup and ensure consistency across instructional environments.

Instructors can refer to the full setup guide and explanation in our ChemRxiv preprint: [10.26434/chemrxiv-2025-07k5s](https://doi.org/10.26434/chemrxiv-2025-07k5s)

🚀 Quick Start Guide
1. Set up a Jetstream2 allocation and create an instance using our pre-configured image.

2. Once the instance is running, navigate to the Web_Shell_Scripts file and follow the provided setup scripts.

3. After initial configuration, access the JupyterHub interface.

4. Open a terminal within JupyterHub and proceed with nbgrader setup by following the scripts in the nbgrader_set_up_scripts file.

5. As part of this step, you will need to generate a Python configuration file by following the template in nbgrader_configuration_scripts.py.

6. After completing these steps, you should have a fully functional JupyterHub instance integrated with nbgrader.


⚙️ Additional Customization
1. To install additional Python packages, refer to Install_package_scripts.

2. To add a new kernel, such as C++ or Bash, see the example scripts in:

    Install_CPP_Kernel_Scripts
    
    Install_bash_kernel_scripts
