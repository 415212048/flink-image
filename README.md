<p align="center">
  <h1 align="center">Flink Stream Data Analysis Tool</h1>
  <p align="center">
    <a href="README_ZH.md"><strong>简体中文</strong></a> | <strong>English</strong>
  </p>
</p>

## Table of Contents

- [Repository Introduction](#repository-introduction)  
- [Prerequisites](#prerequisites)  
- [Image Specifications](#image-specifications)
- [Getting Help](#getting-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction  
[Apache Flink](https://github.com/apache/flink) is an open-source distributed processing engine primarily designed for stateful computations over unbounded and bounded data streams. It enables high-speed in-memory data processing with elastic scalability.

**Core Features:**  
1. **Batch & Stream Processing Unification**: Flink supports both batch and stream processing, allowing developers to handle different computation tasks with a single system. Batch processing works for bounded datasets while stream processing handles unbounded data streams.  
2. **State Management**: Provides rich state management APIs including ValueState, ListState, and MapState to simplify complex state management.  
3. **Event Time Processing**: Supports event-time based data processing, tolerating data delays and disorder to ensure accuracy.  
4. **High Availability & Fault Tolerance**: The checkpoint mechanism ensures data consistency and state recovery during failures.  

This project offers pre-configured [**Flink Stream Analysis Tool**](https://marketplace.huaweicloud.com/hidden/contents/992480da-64a3-4ba8-90cb-686d1832e96a#productid=OFFI1111485128289529856) images with Flink and its runtime environment pre-installed, along with deployment templates. Follow the guide to enjoy an "out-of-the-box" experience.

> **System Requirements:**  
> - CPU: 2GHz or higher  
> - RAM: 4GB or more  
> - Disk: At least 40GB  

## Prerequisites  
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Specifications  

| Image Version | Description | Notes |  
|--------------|-------------|-------|  
| [Flink1.13.0-arm-v1.0](https://github.com/HuaweiCloudDeveloper/flink-image/tree/Flink1.13.0-arm-v1.0?tab=readme-ov-file) | Deployed on Kunpeng servers with Huawei Cloud EulerOS 2.0 64bit |  | 
| Flink1.17.0-arm-v2.0 | - |  |  

## Getting Help
- Submit an [issue](https://github.com/HuaweiCloudDeveloper/Flink-image/issues)
- Contact Huawei Cloud Marketplace product support

## How to Contribute
- Fork this repository and submit a merge request.
- Update README.md synchronously based on your open-source mirror information.
