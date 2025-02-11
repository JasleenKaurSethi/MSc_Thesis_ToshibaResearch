# MSc Major Project: Coverage Digital Twin for Multi-Floor Indoor Environments (In collaboration with Toshiba Europe Ltd.)

**_Please note: The code for this project cannot be shared due to confidentiality agreements._**

## Project Overview
The project at Toshiba focuses on developing a **coverage digital twin** to predict the **path loss** and **received signal strength** in a multi-floor indoor environment using a fully connected deep learning neural network. The model integrates real-time measured data with data simulated using ray-tracing techniques and empirical models.

## Project Objectives

- **Data Collection and Integration:**
  - Collecting real-time data and simulating the physical environment using ray-tracing methods to generate synthetic data.
  - Conducting a comparative analysis of the accuracy of integrating the real-time data with the synthetic data, validating the effectiveness of the integration by assessing the closeness to actual real-time data.

- **Virtual Propagation Model Development:**
  - Developing a virtual propagation model to construct a coverage map that optimizes signal coverage.
  - Determining the ideal placement and number of transmitters by analyzing maximum average received power across all points and selecting the configuration that provides the highest overall signal strength while considering multi-path propagation, channel interference, and path loss.

- **Neural Network Model Development:**
  - Designing a neural network to predict signal strength by training on unified data, which includes material properties and simulated measurements.
  - Validating the trained model’s accuracy for a multi-floor environment by assessing key performance indicators (KPIs) such as absolute error, mean squared error, and comparing actual versus predicted path loss. Visualization tools are used to ensure the effective integration of real and synthetic data within the Digital Twin framework.


