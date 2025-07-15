[简体中文](./README.md) | English

<p align="center">

[![HitCount](http://hits.dwyl.com/eeveek/oms.svg)](http://hits.dwyl.com/eeveek/oms)
![GitHub All Releases](https://img.shields.io/github/downloads/eeveek/oms/total)
[![GitHub issues](https://img.shields.io/github/issues/eeveek/oms)](https://github.com/eeveek/oms/issues)
![GitHub closed issues](https://img.shields.io/github/issues-closed/eeveek/oms)
[![GitHub forks](https://img.shields.io/github/forks/eeveek/oms)](https://github.com/eeveek/oms/network)
[![GitHub stars](https://img.shields.io/github/stars/eeveek/oms)](https://github.com/eeveek/oms/stargazers)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/eeveek/oms)
[![GitHub license](https://img.shields.io/github/license/eeveek/oms)](https://github.com/eeveek/oms/blob/master/LICENSE)
</p>

# 🔺[Open Source New Retail Business Platform OMS](https://www.k8s9.com)
```
The omni-channel inventory and order management system OMS is built on a cutting-edge microservice architecture to create a general e-commerce business platform. It enables rapid deployment, helping enterprises accelerate business integration and digital transformation. Businesses can handle orders from all channels, reduce inventory positions to improve cash turnover by at least 50%, cut internal loss by roughly 2%-10% of order value, shrink deployment cycles to weeks and keep development costs around one million yuan while keeping the system in sync with evolving business needs.
```
## 🔺Introduction
```
The core of the OMS omni-channel inventory and order management system is a universal platform that can be deployed quickly. It helps enterprises continue independent development iterations to complete their digital transformation.

The provided platform includes a general business center, a powerful technology center, design of follow-up development plans, and training for technical and management personnel.

The business center manages orders, inventory, finance, products and marketing to build a management system suited for new retail conditions so that enterprises can upgrade in the digital era.

The technology center uses a microservice architecture and pipeline deployment so that programmers with average skills can develop complex platforms, reducing technical investment.

Through solution design and personnel training, the enterprise can cultivate a capable technical team that controls its own systems, keeping up with the fast-changing market, shortening overall go-live time and lowering operational costs.
```
**Helping enterprises and individuals solve the following problems**
```
1. Difficulty consolidating omni-channel orders and managing online/offline orders together.

2. Inventory cannot be shared leading to heavy inventory positions.

3. Finances cannot be accounted in real time leading to slow cash turnover.

4. Product, pricing, marketing and permission data are scattered, causing substantial internal losses.

5. Long development cycles, high personnel requirements, high costs and constrained iterations.

6. Market changes are too fast for systems to keep up with the business.
```
## 🔺Software Demonstration and Architecture

![img](https://github.com/FJ-OMS/oms-erp/blob/main/%E4%B8%9A%E5%8A%A1.png)
![img](https://github.com/FJ-OMS/oms-erp/blob/main/%E9%85%8D%E7%BD%AE.png)

**Business Architecture**

    By aggregating orders from JD.com, Taobao, Tmall, TikTok and Pinduoduo, converting them into internal orders in the platform and integrating the order center, purchasing center, inventory center and financial center, enterprises form a strong triangle of order, inventory and finance data.

![img](https://github.com/eeveek/oms/blob/main/%E4%B8%9A%E5%8A%A1%E6%9E%B6%E6%9E%84.png)

**Technical Architecture**

    Built on the Spring Cloud microservice framework with multi-tenant support, microservice workflow with Zeebe and Activiti and custom reporting. Services such as Redis, MyBatis, distributed transactions (saga), distributed locks and search are componentized for secondary development.

![img](https://github.com/FJ-OMS/oms-erp/blob/main/%E6%8A%80%E6%9C%AF%E6%9E%B6%E6%9E%84.png)

## 🔺Highlights

**Cloud Native**
```
Based on distributed deployment and unified operations, building a technology product system using distributed cloud, containers, microservices and DevOps.
```
**Development**
```
Includes integrated GitLab code management, supports various artifact repositories, integrates CI/CD pipelines, and provides built-in code scanning and quality analysis to track the entire development process.
```
**Deployment**
```
Includes cluster, environment and resource management. Supports unified management and centralized allocation, automated deployment pipelines and one-click manual deployment for efficient operations.
```
**Testing**
```
Includes test case, test plan, test execution and defect management as well as test report management. Supports manual testing and automated API, performance, regression and UI testing. Test tasks can be embedded in the development pipeline for continuous testing to ensure product quality.
```

## Usage
1. **Frontend configuration:** The project uses element-ui and vue. Ensure these libraries are installed and configured correctly. Run `npm run dev`.
2. **Backend configuration:** The project uses MySQL and Redis. Configure connection information in `application.yml`.
   - MySQL URL: `jdbc:mysql://<local_ip>:3306/skyer_after_sales?useUnicode=true&characterEncoding=utf-8&useSSL=false`
   - Username: `<local_username>`
   - Password: `<local_password>`
   - Redis host: `<local_redis_ip>`
3. **Login:** After starting the server on port 8080, visit `http://127.0.0.1:8080`. The username and password are stored in the user information table of the database.
4. **Backend framework:** Spring Boot.
5. **Import SQL files:** Import the SQL files under `oms-erp-main\skyer-order\sql`, `oms-erp-main\skyer-tags\sql` and `oms-erp-main\skyer-channel\src\main\resources\skyer_channel.sql` into the database using your database tool or the command line.
6. **Start the project:** Run `Application.java` directly. Ensure your development environment is correctly configured and dependencies are installed.

## 🔺Contact and Demo
```
Demo address: https://www.k8s9.com/ (click "Free Trial" in the navigation)
Username: demo
Password: abcd1234
WeChat: blowbing
```
![img](https://github.com/eeveek/oms/blob/main/front-end/we.png)  ![img](https://github.com/eeveek/oms/blob/main/front-end/gzh.png)

## 🔺Installation Guide

## 🔺Usage

## 🔺Contributing
